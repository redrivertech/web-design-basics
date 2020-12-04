# JavaScript

* JavaScript is the programming language of HTML and the Web.
* JavaScript is used to program the behavior of web pages. It can:
  * Change HTML content.
  * Change HTML attribute values.
  * Change the style of an HTML element.
  * Hide HTML elements.
  * Show hidden HTML elements.

[https://www.w3schools.com/js/js_examples.asp](https://www.w3schools.com/js/js_examples.asp)

## Adding JavaScript to HTML

* In HTML, JavaScript code must be inserted between `<script>` and `</script>` tags.
* You can place any number of scripts in an HTML document.
* Scripts can be placed in the `<body>`, or in the `<head>` section of an HTML page, or in both.
* To use an external script, put the name of the script file in the src (source) attribute of a `<script>` tag:

[https://www.w3schools.com/js/js_whereto.asp](https://www.w3schools.com/js/js_whereto.asp)

### Examples

```html
<!DOCTYPE html>
<html>
  <head>
  <!-- myFunction1 is in <head> and run before <body> is rendered -->
    <script>
      function myFunction1() {
        document.getElementById('demo').innerHTML = 'Button 1 was clicked.';
      }
    </script>
    <!-- myFunction2 is in external file -->
    <script src="script.js"></script>
  </head>
  <body>
    <h2>JavaScript in Head</h2>

    <p id="demo">Click a button.</p>

    <button type="button" onclick="myFunction1()">1</button>
    <button type="button" onclick="myFunction2()">2</button>
    <button type="button" onclick="myFunction3()">3</button>

    <!-- myFunction3 is last tag inside <body>, but before ending </body> tag. Scripts will run after <body> is rendered -->
    <script>
      function myFunction3() {
        document.getElementById('demo').innerHTML = 'Button 3 was clicked.';
      }
    </script>
  </body>
</html>
```

[http://next.plnkr.co/edit/25j2P5c6q9L4RQYK?preview](http://next.plnkr.co/edit/25j2P5c6q9L4RQYK?preview)

## Syntax

JavaScript syntax is the set of rules, how JavaScript programs are constructed

```js
var x, y, z;       // How to declare variables
x = 5; y = 6;      // How to assign values
z = x + y;         // How to compute values
```

* Variables
  * Used to store data values.
  * `var` keyword to declare variables.
  * An equal sign is used to assign values to variables.
* Operators
  * JavaScript uses arithmetic operators ( `+` `-` `*` `/` ) to compute values.
  * JavaScript uses an assignment operator ( `=` ) to assign values to variables.

```js
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```

* A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
* Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).
* The parentheses may include parameter names separated by commas: (parameter1, parameter2, ...)
* The code to be executed, by the function, is placed inside curly brackets: {}

[https://www.w3schools.com/js/js_functions.asp](https://www.w3schools.com/js/js_functions.asp)

[https://www.w3schools.com/js/js_syntax.asp](https://www.w3schools.com/js/js_syntax.asp)

## JavaScript Guides

[https://www.codecademy.com/learn/introduction-to-javascript](https://www.codecademy.com/learn/introduction-to-javascript)

[https://www.learn-js.org/](https://www.learn-js.org/)

[https://www.w3schools.com/js/](https://www.w3schools.com/js/)

[https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

## JS Reference

[https://developer.mozilla.org/en-US/docs/Web/JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

[https://www.w3schools.com/jsref/](https://www.w3schools.com/jsref/)
