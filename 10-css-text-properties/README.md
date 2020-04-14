# CSS Text Properties

- [Font Size](#font-size)
- [Text Align](#text-align)
- [Font Weight](#font-weight)
- [Font Style](#font-style)
- [Font Family](#font-family)
- [Line Height](#line-height)
- [Word Spacing](#word-spacing)
- [Letter Spacing](#letter-spacing)
- [Text Decoration](#text-decoration)
- [Text Transform](#text-transform)
- [Text Shadow](#text-shadow)


## Font Size

`font-size` property sets the size of the text.

```css
h1 {
  font-size: 40px;
}
```


## Text Align

`text-align` property sets the horizontal alignment of a block element.

- `left`
- `right`
- `center`
- `justify`

```css
h1 {
  text-align: right;
}
```


## Font Weight

`font-weight` property sets the weight of the font.

- `normal`
- `bold`
- `lighter`
- `bolder`
- `400`
- `700`


```css
h2 {
  font-weight: 400; /* normal */
}
```


## Font Style

`font-style` property sets whether a font should be styled with:

- `normal`
- `italic`
- `oblique`

```css
h1 {
  font-style: italic;
}
```


## Font Family

`font-family` property is how to change the font itself.

### Generic Name

- `serif`
- `sans-serif`
- `monospace`
- `cursive`
- `fantasy`

```css
h1 {
  font-family: 'Lucida Console', Monaco, monospace;
}
```


## Line Height

`line-height` property controls the height of each individual line of text.

```css
p {
  line-height: 1em;
}
```


## Word Spacing

`word-spacing` property controls the spacing for each individual words.

```css
p {
  word-spacing: 5px;
}
```


## Letter Spacing

`letter-spacing` property controls the spacing for each individual letters.

```css
#brand {
  letter-spacing: 10px;
}
```


## Text Decoration

`text-decoration` property sets the decorative lines, color, or style on text. It's also a shorthand for `text-decoration-line`, `text-decoration-color`, `text-decoration-style`, and `text-decoration-thickness` property.

```css
a {
  text-decoration: none;
}

h1 {
  text-decoration: underline solid blue;
}
```


## Text Transform

`text-transform` property specifies the casing of a text.

- `capitalize`
- `uppercase`
- `lowercase`
- `none`

```css
h1 {
  text-transform: uppercase;
}
```


## Text Shadow

`text-shadow` property adds shadow to text.

```css
h2 {
  text-shadow: -2px 2px 5px magenta, -4px 4px cyan, -6px 6px yellow; 
}
```

---

Credits to Colt's Code Camp
