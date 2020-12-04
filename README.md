# HTML, CSS, and JavaScript

## Learn the language of the Internet

### Integrated Development Environment (IDE)

- Go to [repl.it](https://repl.it/) and sign up for free access on an online IDE

- Click the plus icon (+) in the top right

-  Select language HTML, CSS, JS

- Click Create repl

### HTML

- HTML is used by nesting tags in the in the `index.html` file

- Learn more about tags by going to the [HTML](./docs/html.md) Doc

- Add the follow tags inside the `<body>` tag
    
    * `<div>` Defines a section in a document

    * `<label>` Defines a label for an `<input>` element

    * `<input>` Defines an input control 

```html
<div>
    <label for="firstName">First Name</label> 
    <input type="text" id="firstName"> 

    <label for="lastName">Last Name</label>
    <input type="text" id="lastName">

    <input type="button" value="Alert!">
</div>
```

- Press Run to see changes

### JavaScript

- JavaScript is used by creating functions in the `script.js` file

- Learn more about functions by going to the [JavaScript](./docs/javascript.md) Doc

- `script.js` is connected to `index.html` with the tag `<script src="script.js"></script>`

- Create the following function in the `script.js` file

```js
function alertFullName() {
    // Create references to the input with the id firstName and lastName
    var firstNameInput = document.getElementById('firstName');
    var lastNameInput = document.getElementById('lastName');

    // Get values from input
    var firstName = firstNameInput.value;
    var lastName = lastNameInput.value;

    // Combined first and last name & add space between names
    var fullname = firstName + " " + lastName;

    // Tell browser to alert fullname
    alert(fullname);
}
```

- Connect function `alertFullName` to button

```html
<input type="button" onclick="alertFullName()" value="Alert!">
```

- Press Run to see changes

### CSS

- CSS is used by creating selectors in the `style.css` file

- Learn more about selectors by going to the [CSS](./docs/css.md) Doc

- `style.css` is connected to `index.html` with the tag `<link href="style.css" rel="stylesheet" type="text/css" />`

#### Change Display for Label and Input

- Use tag selector to add css to `<label>` and `<input>`

```css
label, input {
    display: block;
}
```

- Press Run to see changes

#### Adding a Class to Change Style

- Add `card` class to `<div>` tag

```html
<div class="card">
```

- Use `card` class selector to add css to `<div class="card">`

```css
.card {
    padding: 12px; /* adds space inside div */
    margin: 8px; /* adds space outside div */
    border-radius: 4px; /* adds rounded corners */
    background-color: floralwhite; /* adds color using a color name */
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* adds the "card" effect */
}
```

- Press Run to see changes

### Responsive Design using Flexbox

- Flexbox uses CSS property references in the `style.css` file

- Learn more by going to the [Responsive Web Design](./docs/responsive.md) Doc

#### Create a Container Class to Center Items

- Use class selector to create a new class

```css
.container {
    display: flex; /* enable flexbox */
    flex-direction: column; /* how flex items are placed in the flex container*/
    justify-content: center; /* horizontal alignment*/
    align-items: center; /* vertical alignment*/
}
```

- Add Class to `<body>`

```html
<body class="container">
```

- Press Run to see changes

#### Cascade Height to Container Class

- Use tag selector to define `height` for `<html>`

```css
html {
    height: 100%;
}
```

- Use tag selector to define `height` for `<body>`

- Remove browser defaults by setting `margin` and `padding` to `0`.

```css
body {
    height: 100%;
    margin: 0;
    padding: 0;
}
```

- Press Run to see changes


## Documents

> [HTML](./docs/html.md)
>
> [JavaScript](./docs/javascript.md)
>
> [CSS](./docs/css.md)
>
> [Responsive Web Design](./docs/responsive.md)
>
