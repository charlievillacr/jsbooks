# JavaScript Beginner
- Coding from the ground up
- by Keith Dvorjak

## Table of Contents - Chapters

1. Introduction
2. Main features of JavaScript
3. Real-life uses of JavScript
4. Your first JavaScript program
5. Embedding JavaScript code in HTML
6. Basic display operations in JavaScript
7. Variables, data types & constants
8. Basic Operators
9. Functions in JavaScript
10. Understanding objects
11. Scope of a variable
12. Working with numbers in JavaScript
13. Working with strings in JavaScript
14. Working with date and time in JavaScript
15. Events in JavaScript
16. Conclusion

## Chapter 1: Introduction


Known as the "language of the web" because it is used in the development of an incredibly high number of applications on the web and the mobile paradigm alike. 

It is the language which makes web applications dynamic so that users can interact with them, which provides a rich user experience.

When JavaScript came into existence around 1995, most of the logical calculations and input validations in web pages were primarily done using server-side languages like PHP. 

The process was very long and unnecessarily involved two-way trips, first to send a request to the server and the get the data/error back to the client's computer. It was a huge letdown to UX. The need of that time was to make validations right on the client's computer before sending to the server, thereby reducing the bandwidth, which at that time was a major issue so that the user would not have to wait just to see if he made any errors while typing out that form.

JavaScript was created by Brendan Eich as "LiveScript" in 1995, which got renamed to "JavaScript." It was initially named "Mocha" but named JavaScript to gain traction with the language Java that was getting popular at the same time. The first major standarization ocurred in the form of ECMA standarization. The fist version developed still lacked features like RGEX ans JSON and some important built-in functions. The language kept getting developed and adding features to its repertoire.

It was the ECMA v3 that saw the birth of AJAX (Asynchronous JavaScript and XML), which today is at the core of every web application framework.

At present, the language is packed with exciting new features. Let's look at the advantges one gets with JavaScript:

- JavaScript is a lightweight, interpreted programming language.

- Designed for creating simple as well as complex web applications.

- Furthers the functionality of web pages.

- Animation and Visual effects can be done easily.

- UI/UX improvements.

Owning to the language's success and usability, many frameworks and libraries like jQuery, Angular JS, React JS have been developed which make writing code in JavaScript a delight.

JavaScript is the scripting language that is being actively used by developers around the globe in creating interactive, functional and animated by the use of this language as a scripting tool.

JavaScript began as a client-side scripting language but is being used on the backend side of the web also in the form of Node.js. Many libraries and frameworks have sprung up in the meantime to make the developer's life easy.

JavaScript has built-in as well as user defined methods/functions that allow themselves to get bound to certain buttons  or elements and can be called whenever and wherever. The functions are being actively used to automate tasks like the:

- setTimeout()
- or setInterval() 

functions that can be called aftter a certain period of time to do dome task. 

JavaScript can be used in the HTML file itself, if it is written into the ```<script></script>``` tags, and can also be attached to it as an external file. The extension of a JavaScript program is '.js.'

JavaScript is often abbreviated as JS. Some of the main features of the language are as follows:

- High-level, Weakly Typed
- Interpreted
- Functional
- Object-Oriented

Object-Oriented design is perhaps the most important feature of JavaScript, as it allows us the creation of objects and establishes relationships between them, commonly know as Inheritance and Encapsulation, which you'll come to know about in the proceeding chapters.

## Chapter 2: Main features of JavaScript

Most of the features of JavaScript are more or less same as that of other common programming languages. Almost all the programming languages have these features. The main features are as follows.

1. JavaScript Variables

One of the very important features of JavaScript is variables. They act as the storage containers for values. In other words, they are the names of the memory locations at which the values are stored.

These values can be an integer, decimal values, strings or single characters. The variable names have to be unique. 

This is important because otherwise, this will create a great amout of confusion. The name of the variable can start from an alphabet, dollar sign or underscore signs.

The names are case-sensitive. You will get to know exact rules for naming a variable in the later chapter.

Examples of some varibales are:

var abcd:

var $abc;

2. JavaScript Objects

Objects are nothing but a collection of some date values. These generally are written as name-value pairs. 

For example:

var name = {firstName:"Amit",
                lastName:"Kumar",
                age:70};

To access the valus in an object, we use dot notation. 

For example: 
If you want to access the lastName present in name object, we can write that as name.lastName. Arrays are a type of object.

3. JavaScript Comments

Comment is a feature which is often neglected by novice programmers, but as one starts getting experienced at coding, they realize the great value i brings to the code. Thise are basically a way to create notes in the code. This improves th readability of the code. They are not executed by the compiler.

There are two types of comments:

a. Single line comments

    As the name suggets, is used when the comments are single line.

    For example:
    var name; // name of the customer

b. Multi-line comments

    This is used of the length of the comment goes beyond a line.

    For example:
    /* This program calculates the factorial of a number */

4. JavaScript Functions OR methods

Functions form an integral part of any programming language. Functions helps us write code in an efficient manner which not only improves the readability but also contribute a great deal while maintaining it. A function is a set of statements which are used to carry out a particular task.

For example:

function addTwoNumbers(num1, num2) {
    return num1+num2; // Calculates and returns the sum
}

You will learn about functions in detail in later chapters.

5. Conditional statements

Conditional statements are used when we need to make certain decisions based on some conditions. 

For example: 

If there is a program to find out if a person is eligible to vote or not, we input the age of the person and compare it with 18. If it is more than 18, we say that person is elible to vote or else not.

For example:
if(age > 18)
    alert ("elible to vote");
else
    alert("Ineligible to vote");

6. Looping constructs in JavaScript

Loops are used to execute a certain part of code several time repeatedly. There are various ways in which we can implement loops. E.g. For loop, while loop, do-while loop.

For example:
for(i = 0;i < 10; i++)
{
    alert(i);
}

7. Event handling in JavaScript

Events are some activity which happens on the web page. 

For example, a mouse click on the web page, loading of the web page, etc. Event handling is a way to handle what happens when cuch event occurs. 

Some common event handlers are: 

- onclick
- onload
- onmouseover
- onmouseout

This is a very important concept. Developing any web application without event handlers does no make any sense.

<!-- Buscar más sobre: Event handlers -->

This chapter talks about the main features of JavaScript in shot. The later chapters of this book explain these features in great detail.

## Chapter 3 - Real-Life Uses of JavaScript

JavaScript is being used on almost every website out there on the web.

It adds so much functionality to any page that uses this scripting language. If it wasn't for JavaScript, we would probably be stuck in the 90s where websites offered nun functionalitiesto the users, It was not at all intuitive as far as user-experience (UX) is concerned, which is perhaps the best thing that this language has given to us.

JavaScript is practically everywhere. From the forms that you submit to he drop-down button on the menus of the modern websites to the numerous errors that it shows when you leave a field blank to the most annoying yet useful alert boxes, they all are made using JavaScript.

By now, you probably would hace guessed what JavaScript brings to the table.

Learning the basic, simple syntax of the language can give you the power to build a whole calculator that looks decent enough, and in case you happen to sprinkle a little of the CSS magic, that would look just amazing. And that is where the practical usage of the language literally begins.

Let's look at some practical, real-life scenarios where JavaScript has proved to be useful:

Case 1: Form Validation

A good form on the internet is said to be that one that utilizes the power of JavaScript to validate user-input and display errors whenever there is an empty field, inappropiate field inputs occur. Let's assume the case if JavaScript was not used here. 

In that case, the user who is filling the form would have to first submit the form, and since he does not know whether he's made any errors yet, and when it is submitted, it is sent to the server be processed by a POST request, and then the server responds with any error(s) that might have ocurred.
This is a two-way trip.

Much of this can be saved if we used client-side validation using JavaScript. And here comes the power of JavaScript when it responds in split seconds if the user makes any error(s) while filling the form itself.

Case 2: DOM Manipulation

Most of the time, the server responds with a static web page that the browser renders and displays it on the browser. But, what if we get the power to manipulate a few elements on the web page? 

Wouldn't it feel exciting if we could change the state of things, their order, their properties and even their attributes and it could become a whole new thing altogether? Well, it turns out JavaScript does give us all that might to make all that happen. Pretty sweet.

Case 3: Event Listeners

The only way a user truly gets engaged with a web page is when they are allowed to click a button and they get a responde back, like some new page or it changes come data on the web page, or it allows them to carry out some calculation on-the-fly. 

JavaScript allows us to add that functionality by attaching functions tu buttons or elements on the web page, often called DOM (Document Object Model) elements that bind themselves to that element and only execute or fire when th requisite action is carried out. This makes the user-experience satisfied.

There are many uses of JavaScript that are adding to the rich UX of the web pages. In the modern websites, nowadays, Client Side Rendering has made way for a new category of web pages called as Single Page Applications(SPAs) that are capable of generating HTML pages on the fly by using JSON data from the server only. This has bridged the gap between the frontend and the backend of web development.

## Chapter 4: Your first JavaScript Program

HTML adds structure to a web page and CSS (Cascading Style Sheets) adds the relevant style required to make th page look elegant.

But, how do you make the page talk? How do you make it dynamic?

That's where JavaScript come in.

JavaScript adds additional functionality to a rather static web page and lets users interact with the various elements present in the page.

In this chapter, you'll make your very first JavaScript program, the famous "Hello, World!" that will introduce you to this vast yet simple language that is often touted as the "Language of the Web". 

It is presumed here that you are aware of HTML and CSS syntax, as they'll be used thought the text.

Web Browsers render HTML and CSS and display it on the screen, and have built-in JavaScript interpreter that understands the language and executes the tasks of the program.

But for browsers to know where to start with th interpretation of JavaScript, we need to make use of the ```<script>``` tag that tells the browser the starting point of the program. 

```</script>``` tells the browser that it has reached the end of the program.

JavaScript is written within the tags:
```<script> </script>```, and these tags are most commonly placed just above the 
```</body>```tag.

This is done to make the script load after the initial page load that makes the page load faster.

Your first program

Let's create a program that makes and alert box with the message "Hello, World!".

```
<html>
    <head>
        <title>First Program</title>
    </head>
    <body>
       <h1>This is your first JavaScript program</h1> 
       <script>
           alert('Hello Carlos!');
       </script>
    </body>
</html>
```

If you're using a modern browser like Chrome or Firefox or Safari, they support HTML5. But if you're on and old browser which does not support HTML%, you'll need to add the attribute of type to the ```<script>``` tag, and it'll look like this:

```
<script type="text/javascript"></script>
```

// Tells the browser that a comment will follow and ignore the line. This is particulary usefull to document your code so that anyone is able to understand what you've written.

JavaScript has various inbuilt function, which you can think of as little pre-written programs designed to do some tasks. One such function that we have used in our first JavaScript program is the alert() function.

The alert() function takes in a string in between the parentheses and displays an alert box showing that text.

Here, we want the alert box to say "Hello, World!". So, we have written "Hello, World!" inside the parentheses.

Congratulations! You have just made your very first Javascrip program. While JavaScript offers many functionalities, this was one to let you get started with the language that is aptly said to be the language of the web.

## Chapter 5: Embedding JavaScript code in HTML

You can use JavaScript with HTML for dynamic and delightfull user experience. In this chapter, we will learn about the various ways through which we can embed JavaScript in an HTML document.

In order to embed JavaScript directly in a page, you can use the:

```<script>``` tag

The syntax of the script tag is as follows:

```

<script>

// JavaScript code goes here, example:
alert("Hello from JavaScript");

</script>

```

Various optional attributes are available for use with the script tag for more customiztion. Here is the list of available attributes that can be used with the tag:

## type

type: This tag is used to specify the language writtem between the script tag, but since JavaScript is the primary scripting language used for all web browsers, it is not mandatory to use this attribute, as it is set by default.

Here is an example:

```

<script type="text/JavaScript">

//JavaScript code here

</script>

```

## src

src: If you want to load JavaScript code externally then this is the attribute which you should be looking at. The URL of the external JavaScript code is set as the value of this attribute.

```

<script src="url/to/external/JavaScript/file.js"></script>

```

## defer

defer: If this attribute is present in the script tag then the JavaScript file associated with script tag is executed after the page has been fully parsed, i.e. after the DOMContentLoaded event is fired.

Example:

```
<script src="path/to/file.js" defer></script>

```

## async

If this attribute is present in the script tag then the JavaScript file associated with script tag is executed asynchronously while the page continues to load. 

If this tag is not present then the script is first executed, and the the page load continues.

Example:

```
<script src="path/to/file.js" async></script>

```

Note that this attribute is only for JavaScript code loaded externally, i.e., if the ```src``` attribute is present in the same script tag as the defer attribute.

There is one more way to embed JavaScript in HTML, which is to write JavaScript code in event handler attributes of elements. This way when that event fires, the JavaScript code which has been written as the attribute value is executed!

```

<button onclick="alert('JavaScript from event handler');">Click me</button>

```

In the above example when the button is clicked an alert dialog pops up with the message "JavaScript from event handler," showing that the JavaScript in attribute value was executed.

Do not worry if you could not understand the above code example. Events and event handler attributes are discussed in detail later in this book.

So that was all for this chapter, now you are ready to embed JavaScript into your HTML document and make it more awesome!

## Chapter 6: Basic display operations in JavaScript

Following are some of the ways by which JavaScript displays data:

- Writing into an HTML element, using innerHTML.
- Writing into the HTML output using document.write().
- Writing into an alert box, using window.alert().
- Writing into the browser console, using console.log()

### innerHTML

"innerHTML" as the name suggests, represents the inner content of an HTML element. So basically we can use innerHTML property to change the content inside any HTML element.

However, there is a small catch.

How will the JavaScript know which element we are actually interested in changing? What if it changes the content of all the elements present in the web page?

To solve this problem, we assign an id to the HTML element whose content we are interested in changing. That way we will be sure as to which element should reflect the changes.

The next situation which arises in front of us is how we access an HTML element based on the id. In such case, we make use of a method called document.getElementbyId("ID").

Changing the ```innerHTML``` property of an HTML element is a common way to display data in HTML.

## document.getElementbyId("ID")

Let us look at an example here:

```

<!DOCTYPE html>
<html>
<body>

<h1>Chapter 9</h1>
<p>Use of innerHTML to display data</p>

<p id="new"></p>

<script>
document.getElementById("new").innerHTML = "This is how it's done";
</script>
</body>
</html>

```

## document.write()

Another insteresting way to display data in a web page using JavaScript is document.write().

The complete web page can be termed as a document. So as the name of this function suggests, it is used to write on th document.

If is is used after the page is loaded, it not only writes but also replaces the existing (old) value with the new one.

Therefore, one should be very careful while working with them. 

It is mainly used for testing purposes.

Let's understand this through and example:

```

<!DOCTYPE html>
<html>
<body>
<h1>Chapter 6</h1>
<p>Use of document.write() to display data</p>

<script>
document.write(1+2);
</script>

</body>
</html>


```

 As I was saying, using document.write() after an HTML document is fully loaded will delete all existing HTML. Let us see this through an example:

``` 
 
 <!DOCTYPE html>
 <html>
 <body>

 <h1>My First Web Page</h1>
 <p>My frist paragraph.</p>
 <button onclick="document.write(1+2)">Magic Button!!</button>

 </body>
 </html>

 ```

## window.alert()

You have probably seen on many websites an alert like "You seem to have entered a wrong password." These appear in the form of small dialog boxes and are often used to alert the user of something.

```

<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<button onclick="window.alert(1+2)">Add 1 & 2</button>

</body>
</html>

```

 ## console.log()

 ```console.log()``` is a savior for developers. It is used for debugging purposes. The result from ```console.log()``` is not displayed on the web page. 
 
 Instead, it is displayed in the console. This is useful feature because sometimes you don't want testing data to be displayed on the web page.

 Those data are used by developer to know if everything is working fine on the website or not. 
 
 In case you are wondering what a console looks like, press: ctrl + shift + I in Google Chrome on the desired web page.

``` 
 
<!DOCTYPE html>
<html>
<body>

<script>
console.log("it is in console");
<script>

</body>
</html>

 ```

You will get more familiar with console.log() when you start creating applications in JavaScript.

The above were the four ways in which we display data in JavaScript. However, it must be kept in mind that their usage depends on the requirement. You need to select the required method based on the desired result.

## Chapter 7: Variables, Data types & Constants

### Variables

Variables are always an important aspect of any programming language. They are used to store values which can be later addressed using those variable names. Same goes with JavaScript. Let us look at the syntax for creating a variable:

##### Variables Syntax

```

var <variableName>; //Declares a variable

<variableName> = value; //Assigning value to the variable

```

or

```
var <variableName> = value; //Declaration & assignment in the same line

```

In the first method, we declare the variable first and then assign a value to it at some later point in the program.

The only thing one must keep in mind here is that declaration must always come before the assigment.

However, in the second method, both the declaration as well as the assignment happen in a single line.

Examples:

```
var abc;                //Declaration

abc = "New variable";   //Assignment

var num = 33;           //Declaration & Assignment
```

In the above example, the variable "abc" will store the string value "New Variable" while the variable "num" will store the number value 33.


More examples:

```
var marksScience = 85;                 //Variable name
var marksMaths = 100;
var total = marksScience + marksMaths; //Add & store the result

```

In the above example, the variable total will store the calculated value i.e. 185.

All the variables which are used in the program, must have unique names or else it might end up creating a ruckus while executing code.

These unique names are called identifiers. For naming a variable, certain rules must be followed.

#### Rules for naming a variable

- Names must start with a letter, dollar($), or underscore(_).

- You can include letters, digits, underscores, and dollar signs in a variable name.

- Variable names in JavaScript are case-sensitive.

- You cannot used reserved words / keywords as varibale names.

Some of the examples of valid variable names are as follows:

```
Marks1
$abc
_fun
marks2
```

You would have noticed that we make use of an "equal to" symbol to assign some values to a variable. 

This "equal to" symbol is called assignment operator and is used to initialize a variable.

#### Few important points to remember

1. When you simply declare a variable, it holds no value.

For example:

```
var abc;
```

Here the variable "abc" will not contain any value until we assign it some value.

2. Many variables can be declared in a single statement. To do that, we start the statement with ```var``` and separate the variables by a comma.

For example:

```
var firstName="Amitabh", lastName="Kumar", age=70;
```

3. The declaration of variables can span multiple lines.

```

var firstName="Amitabh",
    lastName="Kumar",
    age=70;
```

4. Most of the time, variables are simply declared and are initialized at some later point in the program. 

As mentioned in the first point, after the declaration, the variable holds no value. To be precise, it holds the value undefined. 

For  example:

```
var name;
```

The variable "name" will contain the value undefined after the above statement is executed.

5. Even if you re-declare a JavaScript variable, it retains its previous value.

For example:

```
var name="Amitabh";
var name;
```

Even after the execution of these statements, the variable "name" will still have the value "Amitabh."


## Data Types

Data types, as the name suggests, signifies the type of data a variable can hold. A JavaScript variable can hold several types of data.

For example: string, number, object, Boolean, etc.

```
var age = 70            //stores a Number
var lastName = "Kumar"  //stores a String
var name = {firstName:"Amitabh", lastName:"Kumar"}; 
                        //stores an object
var case = true;        //stores a Boolean

```

Data types are an important aspect of programming because it specifies what kind of data a variable is holding.

This helps the compiler to understand what kind of operations ca be performed on them. 

The addition operator will have different results if applied to two numers and a radically different result if applied on two strings.

For example:

```
var name = "Amit"+" "+"Kumar";
var age = 30+40;
```

The variable "name" will store the concatenated value of both the string i.e. "Amit Kumar" while the variable age will store the added value of 30 & 40 i.e. 70.

<!-- Page 35 -->

Now consider the next example:

```
var abc = 70 + "Amit";
```

If we try and relate the above example with normal arithmetic, it does not make much sense. Adding a number to a string is not possible in normal arithmetic.

However, it would be interesting to see how JavaScript will treat the above example.

JavaScript will interpret the above example as follows:

```
var abc = "70" + "Amit";
```

Whenever we try to add a number with a string, JavaScript will treat the number as a string. However, what if our expression is a mix of several numbers and several strings! What will be the result in that case? 

Let's look at the following two examples:


```

var temp = "Amit" + " " + "Kumar" + 30 + 40;
var temp1 = 30 + 40 + "Amit" + " " + "Kumar";

```

In the above examples, the temp will store the value "Amit kumar3040" whereas the variable temp1 will store "70Amit Kumar". 

How similar looking expressions produced different results?

Let's see how JavaScript treats the above two example. JavaScript starts evaluating expressions from left to right. 

So in the first case when it encountered a string, it considers all the remaining as string itself. Therefore 30 and 40 becomes two separate strings. 

However, in the second example, since the numbers are written first, it first adds them and then concatenates with the remaining string.

Before we dive into each type of JavaScript data types,I must point out that JavaScript has dynamic types. Let me explain what that means. 

In C language, we use data types such as int, float, char, etc. Those are static data types which mean they cannot take any other type of value during the execution of the program. However, we see no such types here. 

We simply declare a variable using the keyword "var" and then go on to mutate it the way we want. 

Even if we have stored string value in the variable, at some later point in the program, we can assign a number to it. Therefore the types in JavaScrip are dynamic in nature.

For example:

```
var rand;               //rand is undefined
var rand =  "Random";   //rand stores an string
var rand = 70;          //Now rand stores a number

```

Now that we have looked at the properties of data types, let's look at each data type in detail.

Two kinds of data types in JavaScript:

- Primitive data
- Non-primitive or complex data

Primitive is the predefined types of data which are inbuilt to a language. There are five primitive data types in JavaScript.

- String
- Number
- Boolean
- Null
- Undefined

Non-primitive or complex data are not provided by default but are defined by the programmer.

For example:

- arrays
- objects
- etc.

## Strings

Strings are nothing but a series of characters. They are either enclosed in a single or double quotes. Addition operation on them is nothing but a simple concatenation.

For example:

```
var name = "Amit Kumar";
var name2 = 'Javed';

```
Quotes inside a string are not a problem as long as they are different than the quotes surrounding the string.

For example

```
var xyz = "It's done";
var xyz1 = 'Friends call him "James"';
```

## Numbers

Unlike most of the other programming laguage, JavaScript does not have a concept of integer, float, etc. Instead, it just has a single concept of numbers which may or may not contain decimals.

```
var x = 74.00;      // Decimals
var y = 33;         // Without decimals

If the number is extremely large, it can be writtrn using scientific notation.

For example:

var x = 333e5;      // 33300000
var y = 23e-5;      // 0.00023

```

## Booleans

The concept of Boolean is almost same as that of other programming languages. Booleans have only two values: "true" and "false." The major use of these comes while forming condinitonal statements.

```
var a = true;
var b = false;
```

## Null

Null means "nothing." The value null signifies the intentional absence of any object value. An object can be emptied by setting it to null.

```
var name = null;    //value becomes null
```

## Undefined

The variables which are not assigned any value will contain undefined.

For example:

```
var abc; // value is undefined
```

People generally get confused betweeen null and unefined. I will explain the diffrence at some later point in this chapter.

Those were the primitive types. Now let us look at some none-primitive data types.

<!-- End of primitive types -->


## Arrays

Arrays are nothing but a collection of some values. The set of those values is written using curly braces.

Like all other programming languages, the index starts with 0.

```
var names[] = {"Ram", "Rahim", "Jaspaal"};

//names[0] = "Ram";

```

## Objects

Objects in JavaScript are written as name-value pairs.

For example:

```
var name = {firstName:"Amit",
                lastName:"Kumar",
                age:70};
```

## typeof Operator

At various points in the program we need to know which type of data the variable contains. We can determine that using typeof operator.

For example:

```
typeof "Amit"                   // "string"
typeof ""                       // "string" (empty string)
typeof 314                      // "number"
typeof 3.14                     // "number"
typeof (3+4)                    // "number"
typeof false                    // "boolean"
typeof [1,2,3,4]                // "object" because arrays are considered as objects in JavaScript
typeof {name:'Amit', age:70}    // "object"

```

Now that I have explained typeof operator let us look at what exactly is the difference between undefined and null.

If we operate typeof on null, it returns an objecy whereas if we operate typeof on undefined, undifined is returned.

## Constants

Constant as the name suggets are those variable whose value cannot be changed.

These are declared using const Keyword and must be assigned a value during the time of declaration. 

It can either be local to a function or can be global variable. Constants once assigned cannot be changed. 

Thier value remains read-only throughout the program.

For example:

```
const = 3.14;   //Declaring & initializing a constant

```

This chapter explained variables, data types, and constants.

## Chapter 8: Basic operators

### What are operators?

Operators are basically symbols which act as a function, though they differ from functions syntax-wise. They take input(operands) and produce a certain output based on the operands.

For example:

- "5+2", "5" and "2" are operands(the input), andthe "+" symbol is the operator, which results to "7".

### Classification of operators

Operators are generaly classified on the basis of the type of operation they do. Operators like typeof, instanceof, etc. are unique and thus cannot be classified under the categories about which you will read below.

### Arithmetic Operators

As the name hunts, these are operators which perform arithmetic tasks on the operand(s). Listed below are the arithmetic operators.

##### Addition[+]

This operator performs an addition operation on two operands on two operands if both of them are numerical, if anyone or both of the two operands  are numerical, if anyone or both of the two operands are of string type then this operator concatenates / joins the two operands.

```
Examples:

4 + 2                   //evaluates to 6
'example' + 5           //evaluates to "example5"
'thisIs' + 'Example'    //evaluates to "thisIsExample"
```

##### Subtraction[-]

This operator performs a subtraction operation on two operands.

Example: "4-2" produces the result "2".

##### Division[/]

This operator performs division operation on two operands, where the operand on the leftside(dividend) is divided by the operand on the right side(divisor). 

Example: "15/3" produces the result "3".

##### Multiplication[*]

This operator performs multiplication operation on two operands. 

Example: "4*2" produces the result "8".

##### Modulus[%]

Also known as a Remainder operator, this operator results in the remainder of the two operands when they are divided.

Example: "5%2" produces the result "1", "5%3" produces the result "2".

#### Increment[++]

Increases the value of its numerical operand by one. The position of this operator matters, i.e., whether it is placed before operand or after it.

If placed before operand, then this situation is called prefix(example ++x), and the value is returned after the incrementing operation, and placed after the operand the this situation is called postfix(example x++), and value is returned before the incrementing operation.

Example:

```
//say x value is 5
console.log(++x);
//value of x at this point is 6
```

```
//say y value is 5 too
console.log(y++); //prints 5 NOT 6
//but value of y at this point is 6 so incrementation was done but after the expression returned value

```

##### Decrement[--]

Decreases the value of its numerical operand by one. Similar to increment operator, this postfix and prefix rule applies here too.

Example:

```
//say x value is 5
console.log(--x); //prints 4
//value of y at this oint is 4

```

## Assignment Operator

These operators are used to assign value to variables. Value is assigned to the left operand which is based on the right operand value. Listed below are the assignment operators.

### Equal[=]

This operator simple assigns the value of tis right operand to the left operand. 

Example: "x=5" this assigns 5 to x, so now the value of x is 5.

### Addition assignment[+=]

This operator adds the value of the left and the right operand and then assigns the result to the left operand.

Example: say x = 2 then "x += 3" will make x's value 5.

### Subtraction assignment[-=]

This operator substracts the value of the right operand from the left operand and then assigns the result to he left operand.

Example: say x = 8 then "x -= 3" will make x's value 5.

### Multiplication assignment[*=]

This operator multiplies the left and right operand and assigns the result to the left operand.

Example: say x = 5 the "x *= 2" will make x's value 10.

### Division Assignment[/=]

This operator divides the left operand(dividend) by the right operand(divisor) and then assigns the result to the left operand.

Example: say x = 10 then "x /= 2" will make x's value 5.

### Modulus Assignmet[%=]

This operator divides the left operand(dividend) byt the right  operand(divisor) and then assigns th REMAINDER to the left operand.

Example: say x = 5 the "x %= 2" will make x's value 8.

## Other Operators

These are the type of operators which cannot be categorized under the above-mentioned categrories. Listed below are such operator.

### typeof operator

This operator returns the type of operand in string format. 

Examples:

```
typeof 2                //evaluates to "number"
typeof 1.23             //evaluates to "number"

```
```
typeof "2"              //evaluates to "string"
typeof 'hi'             //evaluates to "string"
```
```
typeof true             //evaluates to "boolean"
typeof false            //evaluates to "boolean"
```
```
typeof {ob:1}           //evaluates to "object"
typeof new Date()       //evaluates to "object" 
```
```
typeof Math.cos         //evaluates to "function"
typeof function(){}     //evaluates to "function"
```


### instanceof operator

This operator checks if the first operand, which should be an object, is of a specific type, where the type to be checked is specified as the second operand.

It returns true or false based on wther the object type is matched or not.

Examples:

```
new String("Astring) instanceof String
    //evaluates to true
```

```
["this, "is", "array"] instanceof Array
    //evaluates to true
```

```
new String("Astring") instanceof Array
    //evaluates to false
```
```
["this", "is", "array"] instanceof String
    //evaluates to false
```

### delete operator

This operator removes a property from and object.

Example:

```
var myObject = {
    prop1: "test",
    prop2: "test2",
};

delete my Object.prop1;     //deletes the prop1 property of object myObject
```

### in operator

This operator checks whether a specified property(first operand) is in the specified object(second operand). It returns true of flase based on whether the property is in the object or not.

Examples:

```
var myObject = {
    prop1: "test",
    prop2: "test2"
};

"prop1" in myObject;        //evaluates to true
"prop45" in my Object;      //evaluates to false
```

This chapter explained operators in JavaScript.

## Chapter 9: Functions in JavaScript

Functions form an integral part of any programming language. If it wasn't for the function, our program would contain lots of redundant code.

Function helps us write code in an efficent manner which not only improves the readability but also contribute a great deal while maintaining it.

Let us explore what a function is and why it is required!

### Definition

A function is a set of statements which are used to carry out a particular task.

It is a simple as saying that you have a function which carries out the addition of two numbers.

So at any point in the program, if you need to calculate the sum of two numbers, you just call this particular function and pass the two values to be added.

The function will then retutn the desired value. LEt us first look at the syntax to declaring and defining a function and then we will discuss in detail about it.

```
function functionName(paramenter1, parameter2, parameter3) {
    //set of statements to be executed
}
```

As you can see above, a function definition starts with the keyword "function", followed by a unique function name, followed by a parentheshis ().

The task which the function is supposed to execute is written curly braces {}.

So whenever a function is called, all the statements whitin the curly braces will be executed.

If you notice in the above syntax, there are a set of parameter whitin the parenthesis which are separated by commas.

These are the values which the function requires in order to produce the disired result. Or in other words, these re the values one must pass while calling the function.

Let us look at a simple example of a function which accepts two values and return their sum.

```
function addTwoNumbers(num1, num2){
    return num1+num2; //Calculates and returns the sum
}
```

One must note that a function remains dormant or inactive until and unless it is invoked or called in the mian program. 

Example:
Consider these analogous to a toes maker present in the kitchen. Toast maker is supposed to toast a bread which you supply to it. It remains inactive unless you need it.

When you need it, you just put the bread inside and switch it on. It then does the usual. Same happens with a function too. It is executed when it is called or invoked.

Each function should have its own unique function name. This is important because when you call a function, there should de no ambiguous situation.

The parameters behave as local variables inside the function. If you have knowledge about some other programming lamguages, you might have heard of procedure or subroutine. What is subroutine to them is function in JavaScript.

A function is executed when it is invoked. This can happen because of one of the following scenarios:

- When it is called from a JavaScript program.
- Automatically invoked.
- When some events occur(Events generally refers t an activy which happens on the web page).

Whenever a return statement is encountered, the value is returned to the place where it is called from. Any statement beyond the return statement in the function is not executed.

Therefore it is extremely important that the retutn statement is placed at the edn of the function.

In some cases, we might have to place the return in the beginning, but then again that will happen in the case of conditional statements.

Let us look at another example which calculates the product to two numbers. This will hep us in understanding the concept of function call in a better way.

```
function productCalc(num1, num2) {
    return num1 * num2; //Product calculated & returned
}

var prod = productCalc(5,6)
```

In the above example, the productCalc function is called, and the returned value is stored in the value prod. You can then use wherever required.

Now that we have seen what function is and how to use them according to our need, let us look at why the function is very important in today's world of efficient programming.

Advantages of functions:

1. Reusability

The main advantage of a function is the fact that it can be reused throughout the program. You can write a function which performs a certain task and the simply call it whenever you are required to perform the task.

For example, if you have to sort some numbers, you can write a function which does that and then no matter how many times you are requiered to sort numbers, you can just call the function, and your job will be done.

You escape from writing the same code for sorting again and again.

2. Maintainability

Maintainability refers to he task of refactoring a piece of code at a later point in time.

Let us say, the code you wrote to sort a list of numbers has a bug. Now imagine you dont have the concept of functions. So basically wherever you have used that buggy code, you need to search it and then rectify a bug. With function, however, you just look at one place and correct the code. You need not visit several places. This saves you a lot of time and effort.

3. Reduced code lenght

With function in place, you don't need to write the same of codes everywhere. This reduces the length of the code significantly.

Few points to remember about function

1. You can use document.getElementById() to show the result of function anywhere in the HTML page.

For example:

```
function add(a,b) {
    return a+b;
}
document.getElementById("result".innerHTML = add(7,14);
```

2. Always use the () operator to invoke a function. In case you miss, the whole text of the function is returned.

In the previous example, if you simply call add instead of add(), the HTML will contain the whole function text.

3. The function can be directy used as the value of a variable.

For example:

var x = add(5,7);
var printString = "The result is " + x;

Or,

var printString = The result is " + add(5,7);

In both the cases, the output will be the same.

Always remember if you write a set code which is repeating several times throughout the program, create a function out of it. Also, the lenght of the function should be kept as small as possible.

## Chapter 10: Understanding Objects

JavaScript is based on the paradigm of OOP(Object Oriented Pogramming) heance almost everything in it is an object or at least behaves like one, be it and array, function or regular expression(regex). An object is the most fundamental block of JavaScript.

### What are objects?

An object is a collection of properties and has a type. Just as in other programming languages, one can understand the concept of an object by comparing it to real-life objects.

Let's take a car, for example, the same model car may have different color, i.e., have different properties, but it belongs to the same category which is a car, i.e., it is of the same type.

Here is an example for understanding the object's concept as described above more clearly:

```
function cars(color, numberPlate) {
    //this is like blueprint of an object, not the object it self
    this.color = color;
    this.numberPlate = numberPlate;
}
//Creating Objects:

var car1 = new car("Green", 1234); //they are of same type
var car2 =  new car("Red", 5678);   //but have different properties

console.log(car1);  //outputs car details, i.e. Green and 1234 on console

console.log(car2);  //outputs car2 details, i.e., Red and 5678 on console

```

## Accesing object's properties

In JavaScript, you can access the object properties in the two ways, viz, the dot notation and the bracket notation. The syntax of both ways are as follows:

```
myObject.propertyName;      //dot notation
myObject['propertyName'];   //bracket notation

```

Note that if the object property is integra;, then it can be accesed onl with bracker notation, example:

```
myObject.55     //WRONG
myObject['55']; //RIGHT
```

### Creatin objects In JavScript

Listed below are the ways to create objects in JavaScript:

#### Object Literal

This is the most commmon and probably the easieast way of creating an object in JavaScript.

Example

```
var myObject = {
    objectProperty1: 45,
    objectProperty2: 'something else',
    objectMethod: function() {//using function as an object property
    console.log(this.objectProperty1, this.objectProperty2);   //prints object property on console
    }
};

myObject.objectMethod(); //example call to object method/function

```

#### Using the 'new' keyword:

You can create objects by calling the object constructor( a function used to initialize new objects) with 'new' keyword.

Example

```
var myObject = new Object(); //contructor to initialize new object
myObject.property1 = 45;
myObject.property2 = 'something else';
myObject.objectMethod = function() {/*...*/};
```
You can also define your own cosntructor function to create new objects; the constructor function is like a blueprint of your object, you can create many objects ensuring that they are all of the same types, though thay may have different properties.

Example of custom constructor function:

```
function students(name, age, class) {
    this.name = name;
    this.age = age;
    this.class = class
}

// using 'new' keyword to create object from custom constructor function:

var student1 = new stuent("Sam", 14, 2);    //a student with name sam and age 17 of class 2

var student2 = new student("Joe", 17, 11);  //a student of age 17 and class 11

```

### Nested objects

You can create an object within an object.This can be done by assigning an object to an object's property. This is called nesting.

Example
```
var student = {
    name: "Mark",
    marks: { //nesting
        maths: 80,
        english: 95
    }
};
```

