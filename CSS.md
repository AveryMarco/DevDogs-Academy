# CSS Tutorial

CSS (Cascading Style Sheets) is used to style HTML elements on screen.

## Syntax

![Image from W3Schools](https://www.w3schools.com/css/img_selector.gif)

A CSS rule consists of a selector and a declaration block.

All the declarations together are the declaration block (enclosed with brackets {}), 
and each declaration in the block is separated by a semicolon.

## Selectors

A CSS selector selects which HTML element or element should be styled.
There are five categories of selectors in CSS: Simple selectors, Combinator selectors, 
Pseudo-class selectors, Pseudo-elements selectors, and attribute selectors.

** All examples are from W3Schools. Link in additional resources.

Simple Selectors: 

They select HTML elements based on name, id, or class.

 - Name: finds the HTML elements based on the elements' name. 
```
// all <p> elements all become center-aligned and red

p {
  text-align: center;
  color: red;
}
```
 - Id : finds HTML element based on element's ID in order to pick a specific element.
```
//To use ID selector, a # must be before the ID of the element.
// will change para1 to red.

#para1 {
  color: red;
}
```
 - Class: finds the HTML elements based on the elements' class. 
```
// all elements with class = "center" all become center-aligned and red

.center {
  text-align: center;
  color: red;
}

// This narrows search to only <p> elements in class="center"

p.center {
  text-align: center;
  color: red;
}
```
 - Universal Selector: Selects all HTML elements
```
* {
  text-align: center;
  color: red;
}
```
 - Grouping Selector: can separate elements with commas to select them instead of writing repeat code for each
```
// will turn <p>, <h1>, and <h2> elements red

p, h1, h2 {
  color: red;
}
```
Combinator Selectors: 

Combinator selectors combine simple selectors to style HTML elements.

 - Descendant ( ): Selects HTML elements that are descendants of a specified element
```
// changes the color in all <p> elements that are inside <div> elements
// Uses a space to separate elements

div  p {
  background-color: yellow;
}
```
 - Child (>): Selects HTML elements that are children of a specified element
```
// changes the color in all <p> elements that are children of <div> elements
// Uses a > to separate elements

div > p {
  background-color: yellow;
}
```
 - Adjacent Sibling (+): Selects HTML elements that are directly after another specified element.
   They must also have the same parent element.
```
// changes the color in all <p> elements that immediately after <div> elements
// Uses a + to separate elements

div + p {
  background-color: yellow;
}
```
 - General Sibling (~): Selects HTML elements that are siblings (same parent) with the specified element
```
// changes the color in all <p> elements that are siblings with <div> elements
// Uses a ~ to separate elements

div ~ p {
  background-color: yellow;
}
```

Other Selectors:

To learn more about these selectors or selectors in the other categories 
(Psuedo-class, Psuedo-elements, and attribute), visit:
https://www.w3schools.com/css/css_selectors.asp

## Box Model
<img src="https://media.geeksforgeeks.org/wp-content/uploads/box-model-1.png" width="450" height="300">
* Image from GeeksforGeeks

The CSS Box Model deals with the layout and design of web pages.  



## Grid

## Flex

## BLock

## Inline Styling

## How-To Center

## Additional Resources

Learn More:

https://www.w3schools.com/css/css_intro.asp

https://www.geeksforgeeks.org/css-box-model/

Practice:

https://www.w3schools.com/css/css_exercises.asp

Games:

https://medium.com/geekculture/learn-css-by-playing-games-cf70a79a38

https://flexboxfroggy.com/

