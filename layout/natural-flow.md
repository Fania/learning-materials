## Natural/Normal Flow

- all html elements are either **block** or **inline**
- inline elements wrap lines, just as text would
- you can change the **display** property of elements
- if unsure inspect element in the browser


### Block-level elements

> "A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can)." [*]<!-- .element: data-preview-link -->

```css
div {
  display: block;
}
```

E.g. `<header>,<nav>,<div>,<section>,<h1>,<p>,<ul>,<form>,<table>,<figure>,<footer>`

[*]: https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements


### Inline elements

> "An inline element does not start on a new line and only takes up as much width as necessary." [*]

```css
span {
  display: inline;
}
```

E.g. `<a>,<span>,<code>,<button>,<strong>,<img>,<video>,<input>`

[*]: https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements


### Display Property

There are many different [display types](https://developer.mozilla.org/en-US/docs/Web/CSS/display):

- `none, inline, block, inline-block, table, list-item, flex, grid`
- **flex** and **grid** are for more advanced layouts

[W3Schools Try "The Display Property"](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_display)

[W3Schools Try "Inline-Block"](https://www.w3schools.com/css/tryit.asp?filename=trycss_inline-block_span1)


### Examples

**Inline**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/inline2.png)](https://codepen.io/faniae/pen/zYYyMEo)


**Block**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/block2.png)](https://codepen.io/faniae/pen/JjjweyN)


**Inline + Block**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/mix.png)](https://codepen.io/faniae/pen/yLLGRMx)


**Inline-Block**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/inline-block.png)](https://codepen.io/faniae/pen/dyywQBj)


**Images**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/images.png)](https://codepen.io/faniae/pen/GRRPwrG)


**Figures**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/figures.png)](https://codepen.io/faniae/pen/WNNLaYg)