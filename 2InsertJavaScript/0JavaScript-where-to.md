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

## JavaScript in <body>

In this example, a JavaScript ```function``` is placed in the ```body``` section of an HTML page.

The function is invoked(called) when a button is clicked:

Example

```
<!DOCTYPE html>
<html>
<body>

<h1>A Web Page</h1>

<p id="demo">A Paragraph</p>

<button type="button" onclick="myFunction()>Try it</button>

<script>
function myFunction() {
    document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>

</body>
</html>
```

### Placing scripts at the bottom of the <body> element improves the display speed, because script interpretation slows down the display.


## External JavaScript

Scripts can also be placed in external files:

External file: myScript.js

```
function myFunction() {
    document.getElementById("demo").innerHTML = "Paragraph changed.";
}
```

External scripts are practical when the same code is used in many different web pages.

JavaScript files have the files extensions ".js".

TO use and external script, put the name of the script file in the ```src``` (source) attribute of a ```<script>``` tag:

Example
```
<script src="myScript.js"></script>

```

You can place an external script reference in ```<head>``` or ```<body>``` as you like.

The script will behave as if it was located exactly where the ```<script>``` tag is located.

External scripts CANNOT contain ```<script>``` tags.

## External JavaScript Advantages

Placing scripts in external files has some advantages:

- It separates HTML and code.
- It makes HTML and JavaScript easier to read and maintain
- Cached JavaScript files can speed up page loads

To add several script files to one page - use several script tags:

Example
```
<script src="myScript1.js"></script>
<script src="myScript2.js"></script>

```

## External References

External scripts can be referenced with a full URL or with a path relatie to the current web page.

This example uses a full URL to link a script:

Example
```
<script src="https://www/s3schoolds.com/js/myScript1.js"></script>

```

This example uses a cript located in a specified folder on the current web site:

Example

```
<script src="/js/myScript1.js"></script>

```

This example links to a script located in the same folder as the current page:

Example

```
<script src="myScript1.js"></script>
```

(Read more about file paths in the chapter)[https://www.w3schools.com/html/html_filepaths.asp]

### HTML File Paths

```<img src="picture.jpg">```       // picture.jpg is located int he same folder a the current page.

```<img src="images/picture.jpg">``` //picture.jpg is located.

```<img src="/images/picture.jpg">``` //picture.jpg is located in the images folder at he root of the current web.

```<img src="../picture.jpg">```        //picture.jpg is located in the folder one level op from the current folder.

### HTML File Paths

A file path describes the location of a file in a web site's folder structure.

File paths are used when linking to external files like:

- Web pages
- Images
- Style sheets
- JavaScript

## Absolute File Paths

An absolute file path is the full URL to an internet file:

Example
```
<img src="https://www.w3schools.com/images/picture.jpg" alt="Mountain">
```