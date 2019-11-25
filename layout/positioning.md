### Positioning Elements

- used for more varied uses than floats
- elements can be positioned in one of 5 ways
- `static, relative, absolute, fixed, sticky`
- you might need `top, bottom, left, right` too

[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/css-positioning-schemes.png)](https://internetingishard.com/html-and-css/advanced-positioning/)

[W3Schools The position Property](https://www.w3schools.com/css/css_positioning.asp)  
[MDN position](https://developer.mozilla.org/en-US/docs/Web/CSS/position) + [MDN Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)


### Static

- default
- *not* affected by `top, bottom, left, right`

```css
div {
  position: static;
}
```


### Relative

- position relative to **original location**
- affected by `top, bottom, left, right`
- leaves original space empty

```css
div {
  position: relative;
  bottom: 0;
  right: 0;
}
```


### Absolute

- position relative to **nearest positioned ancestor**
- if no ancestor, then body is used
- **ancestor also needs to be positioned**
- moves with page when scrolling
- affected by `top, bottom, left, right`

```css
button {
  position: absolute;
  bottom: 0;
  right: 0;
}
```


### Fixed

- position relative to the **viewport**
- stays fixed even when scrolling
- affected by `top, bottom, left, right`

```css
nav {
  position: fixed;
  top: 0;
  left: 0;
}
```


### Sticky

- position relative to **user's scroll position**
- stays fixed after scrolling to sticky point
- affected by `top, bottom, left, right`

```css
nav {
  position: sticky;
  top: 0;
}
```


### Examples
<iframe width="100%" height="400" src="https://interactive-examples.mdn.mozilla.net/pages/css/position.html" style="background:#ccc"></iframe>

[MDN CSS Demo: position](https://interactive-examples.mdn.mozilla.net/pages/css/position.html)