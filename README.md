## CSS Basics
CSS is a crucial technology for web development that allows you to control the presentation and styling of your HTML documents. Whether you're a beginner or want to refresh your CSS knowledge, you'll find useful information here.

## CSS Overview
Cascading Style Sheets (CSS) is a stylesheet language used for describing the presentation of a document written in HTML. CSS separates the content from its visual representation, allowing you to control layout, colors, fonts, and more.

## Basic Syntax
CSS consists of rules that define how HTML elements should be displayed. A basic CSS rule looks like this:
```
selector {
  property: value;
}
```

- The selector selects the HTML element(s) to style.
- The property specifies what aspect of the element you want to style (e.g., color, font-size, margin).
- The value defines the style or appearance of the property (e.g., red, 16px, 10px 20px).

## Selectors
Selectors are used to target HTML elements for styling. Common selectors include:

- Element selector: p { ... } (selects all
elements)

- Class selector: .my-class { ... } (selects elements with class="my-class")
- ID selector: #my-id { ... } (selects the element with id="my-id")
- Descendant selector: div p { ... } (selects all elements inside a)
- Attribute selector: [type="text"] { ... } (selects elements with type="text" attribute)
 
## Properties and Values
CSS offers a wide range of properties and values to control styling, including:

- Text properties: font-family, font-size, color
- Layout properties: margin, padding, width, height
- Background properties: background-color, background-image
- Border properties: border, border-radius
- Positioning properties: position, display
- 
You can find an extensive list of CSS properties and their values in CSS documentation.

## Adding CSS to HTML
You can add CSS to your HTML documents in several ways:

- Inline CSS: Add the style attribute to an HTML element.
- Internal CSS: Use the style element within the HTML document.
- External CSS: Link an external CSS file to your HTML using the link element.
```
<link rel="stylesheet" type="text/css" href="styles.css">
```
## Resources
- Mozilla Developer Network (MDN) CSS Reference
- W3Schools CSS Tutorial

Explore these resources to gain a deeper understanding of CSS and its capabilities.
