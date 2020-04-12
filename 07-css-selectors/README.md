# CSS Selectors

- [Basic Selectors](#basic-selectors)
- [Grouping Selectors](#grouping-selectors)
- [Combinators](#combinators)
- [Pseudo](#pseudo)
- [Homework!](#homework)


## Basic Selectors

### Universal Selector

**Universal selector** (`*`) matches elements of any type.

```css
* {
  color: black;
}
```

### Element Selector

**Element** or **type selector** matches all the elements of the given type or element within a document.

```css
a {
  color: red;
}
```

### Class Selector

**Class selector** matches elements based on the contents of their _class_ attribute. Classes can be used multiple times in a document using a dot (`.`) selector and a class name.

```css
.complete {
  color: green;
}
```

### ID Selector

**ID selector** matches an element based on the value of its _id_ attribute. An _id_ is unique and must only be used once in a document.

```css
#logo {
  width: 80px;
}
```

### Attribute Selector

**Attribute selector** matches elements based on the presence or value of a given attribute.

```css
input[type="text"] {
  width: 300px;
}

a[href^="#"] {
  color: lavender;
}

input[checked] {
  width: 100%;
}
```


## Grouping Selectors

### Selector List

**Selector list** (`,`) selects all the matching nodes.

```css
h1,
h2 {
  color: pink;
}

#logo, img, .icon {
  border: 2px solid red;
}
```


## Combinators

### Descendant Combinator

**Descendant selector** or **combinator** typically represented by a single space (` `) character to select nodes that are descendants of the first element.

```css
ul li {
  display: inline;
}
```

### Adjacent Combinator

**Adjacent sibling combinator** (`+`) separates two selectors and matches the second element only if it immediately follows the first element, and both are children of the same parent element.

```css
h2 + p {
  color: orangered;
}
```

### Child Combinator

**Child combinator** (`>`) selects nodes that are direct children of the first element.

```css
ul > li {
  margin: 2em;
}
```


## Pseudo

### Pseudo Classes

**Pseudo Classes** (`:`) pseudo allow the selection of elements based on state information that is not contained in the document tree.

- `:active`
- `:checked`
- `:first`
- `:first-child`
- `:hover`
- `:focus`
- `:visited`
- `:not()`
- `:nth-child()`
- `:nth-of-type()`

### Pseudo Elements

**Pseudo-element** (`::`) represent entities that are not included in HTML.

- `::after`
- `::before`
- `::first-letter`
- `::first-line`
- `::selection`


## Homework!

- [Homework](./homework/index.html)

---

Credits to Colt's Code Camp
