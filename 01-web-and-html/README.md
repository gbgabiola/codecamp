# Web and HTML

- [How Does the Web Work](#how-does-the-web-work)
- [What are HTTP requests?](#what-are-http-requests)
- [Front-End Vs. Back-End](#front-end-vs-back-end)
- [Client Vs. Server](#client-vs-server)
- [What do HTML, CSS, and JS Do?](#what-do-html-css-and-js-do)
- [Writing Basic HTML!](#writing-basic-html)
- [Homework!](#homework)


## How Does the Web Work

Request is sent from the browser, the server sends back the instruction manual, the browser gets the instruction and turns it into a webpage composing of HTML, CSS, and JavaScript


## What are HTTP requests?

- Foundation of communication on the World Wide Web
- HyperText Transfer Protocol (HTTP)
- Request -> I would like this information please
- Response -> Ok, here you go!


## Front-End Vs. Back-End

- Front End (Client Side)
  - Resto Dining Table Order
  - Everything that happens in the browser
- Back End (Server Side)
  - Resto Kitchen Preparing
  - Google Server where all the logic is happening to send back response


## Client Vs. Server

- Server is a computer that is able to listen for incoming request and respond with something (which is the instructions)
- Client display the parse instruction and convert it into a webpage


## What do HTML, CSS, and JS Do?

There are Only 3 Languages that the Browser Knows How to Run.

- HTML
  - Structural Language
  - Basic structure of sites
  - Skeleton, Content, Nouns - CARROTs
- CSS
  - Styling Language
  - Control presentation, formatting, and layout
  - Skin, Style, Adjectives - HUGE
- JS
  - Programming Language
  - Control the behavior of different elements
  - Motion, Action, Verbs - DANCED


## Writing Basic HTML!

### HTML Elements

Common Elements include:

- `<p>` element - represents a paragraph of text
- `<h1>` element - represents the main header on a page
- `<a>` or anchor element - turns the item into a link
- `<img>` element - embeds an image
- `<form>` element - represents a form
- `<b>` element - to bold some text
- `<i>` element - to italicize some text
- `<ul>` element - is an unorder list, for the list `<li>` items
- `<ol>` element - is an order list, for the list `<li>` items

### HTML Tags

We create elements by writing tags.

Most (but not all) elements consist of an opening and closing tag.

```html
<p>I am a paragraph.</p>
```

### Attribute

Attribute is a addtional information that can be pass to an element

- `href` or _Hypertext REFerence_ attribute to add a path to a link
- `src` or source attribute to add a path to the image 
- `alt` or alternate text that will display when image is not available

### Inline Vs. Block Elements

- Inline elements fit in alongside other elements
- Block level elements take up a whole "block" of space

### HTML Skeleton

We write our HTML in a standard "skeleton" or _boilerplate_.

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Page</title>
</head>
<body>
  <!-- Content Goes Here -->
</body>
</html>
```

- `<!DOCTYPE html>` element means that we're using the most modern HTML
- `<html>` element is a way of telling that this is html
- `<head>` element is where we put all the meta information about the page
- `<body>` element where we put every content we want to see on the page
- `<title>` is what we see in the tab of the browser


## Homework!

- [Day 1 Homework](./homework.html)

---

Credits to Colt's Code Camp
