# CSS Units

- [Absolute Units](#absolute-units)
- [Relative Units](#relative-units)
- [What Should I Use?](#what-should-i-use)

There are two groups for units:

- absolute units
- relative units


## Absolute Units

- **Pixels** (**`px`**) is the most commonly used absolute unit
  - `1px` does not necessarily equal the width of exactly one pixel
  - not recommended for responsive websites 
- pt
- cm
- in
- mm

The specs mentioned that dimensions are _anchored_ either:

1. by relating the physical units to their physical measurements, or
2. by relating the pixel unit to the reference pixel

| unit | name                | equivalence         |
| :--- | :------------------ | :------------------ |
| cm   | centimeters         | 1cm = 96px/2.54     |
| mm   | millimeters         | 1mm = 1/10th of 1cm |
| Q    | quarter-millimeters | 1Q = 1/40th of 1cm  |
| in   | inches              | 1in = 2.54cm = 96px |
| pc   | picas               | 1pc = 1/6th of 1in  |
| pt   | points              | 1pt = 1/72th of 1in |
| px   | pixels              | 1px = 1/96th of 1in |


## Relative Units

- **Percentages** (**`%`**) are always relative to some other value
  - sometimes, it's a value from the parent and other times it's a value from the element itself
  - `width: 50%` is half the `width` of the parent
  - `line-height: 50%` is half the `font-size` of the element itself
- **EM**'s (**`em`**) are relative units
  - with `font-size`, `1em` equals the `font-size` of the parent, `2em` is twice the `font-size` of the parent, etc 
  - with other properties, `1em` is equal to the computed `font-size` of the element itself
- **Root EM**'s (**`rem`**) are relative to the **root html element**'s `font-size`
  - often easier to work with
  - if the root `font-size` is `20px`, `1rem` is always `20px`, `2rem` is always `40px`, etc
- **Viewport Height** (**`vh`**) and **Viewport Width** (**`vw`**)
  - `1vh`/`1vw` is 1% of the height/width of the viewport
  - `height: 100vh` would make an element take up the full height on screen


## What Should I Use?

- `px` should be avoid for `font-size`, use `px` for small details like borders and shadows
- `rem`/`em` for `font-size` and `padding`/`margin`
- `%` is useful for defining layouts and `width`s
- `vh`/`vw` is better to use for larger layout concerns like container

---

Credits to Colt's Code Camp
