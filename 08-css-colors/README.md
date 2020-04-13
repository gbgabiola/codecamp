# CSS Colors

- [Named Colors](#named-colors)
- [RGB Colors](#rgb-colors)
- [Hexadecimal Colors](#hexadecimal-colors)
- [HSL Colors](#hsl-colors)


## Named Colors

147ish built-in colors.

- `salmon`
- `springgreen`
- `teal`
- `purple`
- `mediumorchid`
- `rebeccapurple`
- etc.


## RGB Colors

Each color channel is a value from 0-255.

- Red
- Green
- Blue
- Alpha for transparency

```css
color: rgb(RED, GREEN, BLUE);
color: rgb(0, 0, 0); /* black */
color: rgb(255, 255, 255); /* white */
color: rgb(255, 0, 0); /* red */
color: rgb(0, 255, 0); /* green */
color: rgb(0, 0, 255); /* blue */
```


## Hexadecimal Colors

Still represents RGB colors, but in different format.

Hexadecimal is Base 16 which means there is 16 choices for each number, from 0-9 and A-F.

First two digit represents Red channel, the second two digits are for Green channel, and the third/last two digits are for Blue channel.

Add two digits at the last to add a transparency from 00-FF.

```css
h1 {
  color: #000000; /* black */
  color: #ffffff; /* white */
  color: #ff0000; /* red */
  color: #00ff00; /* green */
  color: #0000ff; /* blue */
  color: #0000ff9f; /* with transparency */
}
```


## HSL Colors

- Hue (0-360) for color position in a color wheel
- Saturation (0%-100%) defines the intensity of a color
- Lightness (0%-100%)
- Alpha (0-1) for transparency

```css
hsla(45, 80%, 50%, 0.7);
```

---

Credits to Colt's Code Camp
