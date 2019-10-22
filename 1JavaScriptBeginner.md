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

It is the language which makes web applications dynamic so that users can interact with them, wich provides a rich user experience.

When JavaScript came into existence around 1995, most of the logical calculations and input validations in web pages were primarily donde using server-side languages like PHP. 

The process was very long and unnecessarily involved two-way trips, first to end a request to the server and the get the data/error back to the client's computer. It was a huge letdown to UX. The need of that time was to make validations right on the client's computer before sending to the server, thereby reducing the bandwidth, which at that time was a major issue so that the user would not have to wait just to see if he made any errors while typing out that form.

JavaScript was created by Brendan Eich as "LiveScript" in 1995, wich got renamed to "JavaScript." It was initially named "Mocha" but named JavaScript to gain traction with the language Java that was getting popular at the same time. The first major standarization ocurred in the form of ECMA standarization. The fist version developed still lacked features like RGEX ans JSON and some important built-in functions. The language kept getting developed and adding features to its repertoire.

It was the ECMA v3 that saw the birth of AJAX (Asynchronous JavaScript and XML), wich today is at the core of every web application framework.

At present, the language is packed with exciting new features. Let's look at the advantges one gets with JavaScript:

- JavaScript is a lightweight, interpreted programming language.

- Designed for creating simple as well as complex web applications.

- Furthers the functionality of web pages.

- Animation and Visual effects can be done easily.

- UI/UX improvements.

Owning to the language's success and usability, many frameworks and libraries like jQuery, Angular JS, React JS have been developed wich make writing code in JavaScript a delight.

JavaScript is the scripting language that is being actively used by developers around the globe in creating interactive, functional and animated by the use of this language as a scripting tool.

JavaScript began as a client-side scripting language but is being used on the backend side of the web also in the form of Node.js. Many libraries and frameworks have sprung up in the meantime to make the developer's life easy.

JavaScript has built-in as well as user defined methods/functions that allow themselves to get bound to certain buttons  or elements and can be called whenever and wherever. The functions are being actively used to automate tasks like the:

- setTimeout()
- or setInterval() 

functions that can be called aftter a certain period of time to do dome task. 

JavaScript can be used in the HTML file itself, if it is written into the <!-- <script></script> --> tags, and can also be attached to it as an external file. The extension of a JavaScript program is '.js.'

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

Functions form an integral part of any programming language. Functions helps us write code in an efficient manner wich not only improves the readability but also contribute a great deal while maintaining it. A function is a set of statements which are used to carry out a particular task.

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

It adds so much functionality to any page that uses this scripting language. If it wasn't for JavaScript, we would probably be stuck in the 90s whre websites offered nun functionalitiesto the users, It was not at all intuitive as far as user-experience (UX) is concerned, which is perhaps the best thing that this language has given to us.

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

But for browsers to know where to start with th interpretation of JavaScript, we need to make use of the <!-- <script> --> tag that tells the browser the starting point of the program. 

<!-- </script> --> tells the browser that it has reached the end of the program.

JavaScript is written within the tags:
<!-- <script> and </script> -->, and these tags are most commonly placed just above the 
<!-- </body> --> tag.

This is done to make the script load after the initial page load that makes the page load faster.

Your first program

Let's create a program that makes and alert box with the message "Hello, World!".

<!--
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
-->

If you're using a modern browser like Chrome or Firefox or Safari, they support HTML5. But if you're on and old browser which does not support HTML%, you'll need to add the attribute of type to the <!-- <script> tag -->, and it'll look like this:

<!-- 
<script type="text/javascript"></script>
-->

// Tells the browser that a comment will follow and ignore the line. This is particulary usefull to document your code so that anyone is able to understand what you've written.

JavaScript has various inbuilt function, which you can think of as little pre-written programs designed to do some tasks. One such function that we have used in our first JavaScript program is the alert() function.

The alert() function takes in a string in between the parentheses and displays an alert box showing that text.

Here, we want the alert box to say "Hello, World!". So, we have written "Hello, World!" inside the parentheses.

Congratulations! You have just made your very first Javascrip program. While JavaScript offers many functionalities, this was one to let you get started with the language that is aptly said to be the language of the web.

## Chapter 5: Embedding JavaScript code in HTML

You can use JavaScript with HTML for dynamic and delightfull user experience. In this chapter, we will learn about the various ways through which we can embed JavaScript in an HTML document.

In order to embed JavaScript directly in a page, you can use the: <!-- <script> tag -->

The syntax of the script tag is as follows:

<!-- 

<script>

// JavaScript code goes here, example:
alert("Hello from JavaScript");

</script>

 -->

Various optional attributes are available for use with the script tag for more customiztion. Here is the list of available attributes that can be used with the tag:

type: This tag is used to specify the language writtem between the script tag, but since JavaScript is the primary scripting language used for all web browsers, it is not mandatory to use this attribute, as it is set by default.

Here is an example:

<!-- 

<script type="text/JavaScript">

//JavaScript code here

</script>

 -->

src: If you want to load JavaScript code externally then this is the attribute which you should be looking at. The URL of the external JavaScript code is set as the value of this attribute.

<!--

<script src="url/to/external/JavaScript/file.js"></script>

-->

defer: If this attribute is present in the script tag then the JavaScript file associated with script tag is executed after the page has been fully parsed, i.e. after the DOMContentLoaded event is fired.

Example:

<!--

<script src="path/to/file.js" defer></script>

-->