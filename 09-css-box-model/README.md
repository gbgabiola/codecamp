# CSS Box Model

Every element in CSS has box around it.

Each box consist of couple different properties.

- [Content Box](#content-box)
- [Border](#border)
- [Padding](#padding)
- [Margin](#margin)
- [Box Sizing](#box-sizing)
- [Background Clipping](#background-clipping)
- [Display Property: Block vs. Inline vs. Inline-Block](#display-property-block-vs-inline-vs-inline-block)
- [Homework!](#homework)


## Content Box

Content box is the box for the element and it has color blue box in the Chrome DevTools Browser.


## Border

**`border`** is the border around each box or element's box and it also has color yellow box in the Chrome DevTools Browser.

```css
h1 {
  border: 2px solid purple;
  border-top-color: cyan;
  border-right-color: magenta;
  border-bottom-color: yellow;
  border-left-color: magenta;
  border-bottom-width: 5px;
  border-top-style: dotted;
  /* border-color: teal; */
}
```


## Padding

**`padding`** shows the spacing between the content box and the border, it also has green color box in the Chrome DevTools Browser.

```css
img {
  padding: 20px; /* Apply to all four sides */
  padding-bottom: 40px;
  padding: 40px 10px; /* vertical | horizontal */
  padding: 10px 20px 30px 40px; /* top | right | bottom | left */
}
```


## Margin

**`margin`** is the space between the border and the other elements in the page, it also has orange color box in the Chrome DevTools Browser.

```css
img {
  margin: 20px; /* Apply to all four sides */
  margin-bottom: 40px;
  margin: 40px 10px; /* vertical | horizontal */
  margin: 10px 20px 30px 40px; /* top | right | bottom | left */
}
```


## Box Sizing

**`box-sizing`** property allows us to set total width and height of an element.

Setting the `box-sizing` into a `border-box` will tell the css that width and height to be the entire content box including padding up to border.

```css
img {
  box-sizing: border-box;
}
```


## Background Clipping

**`background-clip`** property sets whether an element's background extends underneath its border box, padding box, or content box.

- `content-box` extends around the inner content box
- `padding-box` extends to the outside edge of the padding, but not to the edge of the border
- `border-box` is the default and it extends to the outside edge of the border
- `text` extends within the foreground text


## Display Property: Block vs. Inline vs. Inline-Block

- Block element works perfectly with `width`, `height`, `padding`, and `margin`.
- Inline elements doesn't work with `width` and `height`. `padding` and `margin` for top and bottom doesn't work also.
- Inline-Block doesn't take up its own line, but apply the `width`, `height`, `padding`, and `margin`.


## Homework!

- [Homework](./homework/index.html)

---

Credits to Colt's Code Camp
