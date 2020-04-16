# Dynamic Web Pages with JavaScript

## Selected notes from readings in *JavaScript & JQuery* by Jon Duckett

### Chapter 1/C - How Do I Write a Script for a Web Page?

#### Key Concepts of JavaScript
* JavaScript is the "behavioral layer" of a web page and adds interactivity to the HTML/CSS layers
* JavaScript can be embedded in HTML, but best-practice is to keep JS in a separate file(s) as part of the **separation of concerns**
* JavaScript is written in plain text - no special tools or software are needed to write it
* JavaScript scripts do not change the HTML source code when run

*Content Layer (HTML) --> Presentation Layer (CSS) --> Behavior Layer (JavaScript)*

### Objects & Methods

```document.write('Good Afternoon!');```

This is an example of **calling a method**, which uses the structure seen above of **object.method(parameters)**.

### Variables

A **variable** is a way for a script to temporarily store data and assign a value that can be recalled at a later time in the same document. Variables are undefined until you assign a value to them.

**Declaring** a variable at the start of a JavaScript document means that a programmer will be able to use the variable later. JavaScript requires variables to be declared before they can be used. This means to essentially give the variable a name.

There are six **rules of naming variables** to keep in mind:

1. Name bust begin with a letter, dollar ($) sign, or underscore (_).
1. Name can contain letters, numbers, dollar signs, or underscores, but NO dashes (-) or periods (.).
1. Cannot use **keywords** or **reserved words** - such as ```var```.
1. Variables are case sensitive.
1. Use a name that describes a variable's data/purpose wherever possible (such as: firstName, lastName, etc).
1. If a variable name is more than one word, capitalize the first letter of each word *after* the first word (such as: firstName, lastName, etc).

### Data Types for Variables

* **Numeric**: Handles numbers only.
* **String**: Letters and other characters (must be within quotation marks - single or double)
* **Boolean**: a simple, binary, TRUE/FALSE value (like an on/off light switch)

Return to the [Table of Contents](https://alex-whan.github.io/learning-journal/)