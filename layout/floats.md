### Floating Elements

> "places an element on the left or right side of its container, allowing text and inline elements to wrap around it" [*]

- used mainly for **page layout** (images within text)
- turns inline elements into **block**-level elements
- `left, right, none`

```css
img {
  float: right;
}
```

[*]: https://developer.mozilla.org/en-US/docs/Web/CSS/float


### Clearing Floats

- stops element after float from moving around
- `left, right, both`

```css
.clearfix {
  clear: both;
}
```


### Examples

**float 2 images right**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/float.png)](https://codepen.io/faniae/pen/PooXXxN)


**float images differentely**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/float2.png)](https://codepen.io/faniae/pen/oNNJmNv)


**clear right floats**  
[![](https://raw.githubusercontent.com/DaveEveritt/TECH3015/master/imgs/layout/clear.png)](https://codepen.io/faniae/pen/GRRPzpj)