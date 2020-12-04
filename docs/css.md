# Cascading Style Sheets

* CSS is a language that describes the style of an HTML document.
* CSS describes how HTML elements should be displayed.

## Style Tag

* The `<style>` tag is used to define style information for an HTML document.

```html
<head>
    <style>
        h1 { color:red; }
        p  { color:blue; }
    </style>
</head>
```

## Link Tag

* The `<link>` tag defines a link between a document and an external resource.
* The `<link>` tag is used to link to external style sheets.

HTML File

```html
<head>
  <link rel="stylesheet" type="text/css" href="theme.css">
</head>
```

CSS File

```css
h1 { color:red; }
p  { color:blue; }
```

## CSS Selectors

* In CSS, selectors are patterns used to select the element(s) you want to style.

[https://www.w3schools.com/cssref/css_selectors.asp](https://www.w3schools.com/cssref/css_selectors.asp)

## CSS Property Reference

[https://www.w3schools.com/cssref/default.asp](https://www.w3schools.com/cssref/default.asp)

[https://css-tricks.com/](https://css-tricks.com/almanac/)

## CSS Examples

### Tag Selector

```html
<!DOCTYPE html>
<html>
<head>

<title>Background Color</title>

<style>
    body {
        background-color: lightblue;
    }
</style>

</head>

<body>
    The content of the document...
</body>

</html>
```

[https://next.plnkr.co/edit/RLx7UHYDMLgNcprN?preview](https://next.plnkr.co/edit/RLx7UHYDMLgNcprN?preview)

### Class Selector

```html
<!DOCTYPE html>
<html>
<head>

<title>Centered Squares</title>

<style>
    section {
        background-color: #003b6f;
        height: 500px;
        width: 500px;
    }

    main {
        background-color: #F79862;
        height: 400px;
        width: 400px;
    }

    .center {
        position: absolute;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
    }
</style>

</head>

<body>
    <section class="center"></section>
    <main class="center"></main>
</body>

</html>
```

[https://next.plnkr.co/edit/CDpTB58wafJi1iWJ?preview](https://next.plnkr.co/edit/CDpTB58wafJi1iWJ?preview)

### Id Selector

```html
<!DOCTYPE html>
<html>
<head>

<title>Centered Circle</title>

<style>
    #cyan-dot {
        height: 200px;
        width: 200px;
        background-color: #008B8B;
        border-radius: 50%;
    }

    .center {
        position: absolute;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
    }
</style>

</head>

<body>
    <div id="cyan-dot" class="center"/>
</body>

</html>
```

[https://next.plnkr.co/edit/JRgTRDn6AHS7elyp?preview](https://next.plnkr.co/edit/JRgTRDn6AHS7elyp?preview)

## CSS Guide

[https://www.w3schools.com/css/default.asp](https://www.w3schools.com/css/default.asp)
