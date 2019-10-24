# JavaScript Where To

## The <script> Tag

In HTML, JavaScript code must be inserted between ```<script>``` and ```</script>``` tags.

Example
```
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
```

Old JavaScript examples may use a type attribute: ```<script type="text/javascript">```.
The type attribute is not required. JavaScript is the default scripting language in HTML.

## JavaScript Functions and Events

A JavaScript ```function``` is a block of JavaScript code, that can be executed when "called"for.

For example, a function ca be called when an event occurs, like when the user clicks a button.

More abour functions and events in later chapters.

## JavaScript in <head> or <body>

you can place any number of scripts in an HTML document.

Scripts can be placed in the ```<body>```, or in the ```<head>``` section of an HTML page, or in both.

## JavaScript in <head>

In this example, a JavaScript ```function``` is placed in the ```<head>```

The function is invoked(called) when a button is clicked;

Example

```

<!DOCTYPE html>
<html>
<head>
<script>
function myFunction() {
    document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head>
<body>

<h1>A Web Page</h1>
<p id="demo">A Paragraph</p>
<button type="button" onclick="myFunction()">Try it</button>
</body>
</html>

```