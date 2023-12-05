# Sabar.js

Sabar.js is a JavaScript library designed to simplify HTML, CSS, and JavaScript writing. This library provides several functions that allow you to easily create HTML elements, apply styles to elements, add event listeners to elements, and change the text and attributes of elements.

## How to Use Sabar.js

First, you need to install Sabar.js through npm:

```
bash npm install sabar.js
```

Then, you can import Sabar.js into your project and use the provided functions:

```
// Import the Sabar.js library
const { createElement, applyStyles, addEventListener, setText, setAttribute } = require('sabar.js');

// Create a div element
const div = createElement('div', { className: 'container' });

// Apply styles to the element
applyStyles(div, { color: 'red', backgroundColor: 'black' });

// Add an event listener to the element
addEventListener(div, 'click', () => {
 console.log('Div clicked!');
});

// Change the element's text
setText(div, 'Hello, world!');

// Change the element's attribute
setAttribute(div, 'data-custom', 'custom value');

// Add the element to the body
document.body.appendChild(div);
```

## Documentation

For more information about the functions provided by Sabar.js, you can check out our [documentation](https://sabar.js.org/docs).

## Contribution

We welcome contributions from everyone! Please see our [contributing guide](CONTRIBUTING.md) for more details.

## License

Sabar.js is licensed under the [MIT License](LICENSE.md).
