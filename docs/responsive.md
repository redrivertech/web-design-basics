# Responsive Web Design

* Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones).
* Responsive design using flexbox and media queries.

## CSS Frameworks

* A CSS framework is a library allowing for easier, more standards-compliant web design.
* Most framworks are design oriented and focused around interactive UI patterns.
* Two notable and widely used examples are [Bootstrap](https://getbootstrap.com/) and [Foundation](https://foundation.zurb.com/).

## Flexbox

* Flexbox is a method for laying out items in rows or columns.
* Items flex to fill additional space and shrink to fit into smaller spaces.

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      .flex-container {
        display: flex;
        background-color: DodgerBlue;
      }

      .flex-container > div {
        background-color: #f1f1f1;
        margin: 10px;
        padding: 20px;
        font-size: 30px;
      }
    </style>
  </head>
  <body>

    <div class="flex-container">
      <div>1</div>
      <div>2</div>
      <div>3</div>  
    </div>

    <p>A Flexible Layout must have a parent element with the <em>display</em> property set to <em>flex</em>.</p>

    <p>Direct child elements(s) of the flexible container automatically becomes flexible items.</p>

  </body>
</html>
```

[https://next.plnkr.co/edit/cVMRxYJXBdLIdA20?preview](https://next.plnkr.co/edit/cVMRxYJXBdLIdA20?preview)

### Flexbox Guides

[https://css-tricks.com/snippets/css/a-guide-to-flexbox/](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

[https://www.w3schools.com/css/css3_flexbox.asp](https://www.w3schools.com/css/css3_flexbox.asp)

### Flexbox Game

[https://flexboxfroggy.com/](https://flexboxfroggy.com/)

## Media Queries

* It uses the `@media` rule to include a block of CSS properties only if a certain condition is true.

```html
<!DOCTYPE html>
<html>
  <head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
        background-color: lightgreen;
    }

    @media only screen and (max-width: 600px) {
        body {
            background-color: lightblue;
        }
    }
  </style>
  </head>
  <body>

    <p>Resize the browser window. When the width of this document is 600 pixels or less, the background-color is "lightblue", otherwise it is "lightgreen".</p>

  </body>
</html>
```

[https://next.plnkr.co/edit/SrKKsmhKjJxoTRlO?preview](https://next.plnkr.co/edit/SrKKsmhKjJxoTRlO?preview)

### Media Queries Guide

[https://www.w3schools.com/css/css_rwd_mediaqueries.asp](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
