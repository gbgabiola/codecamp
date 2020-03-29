# Day 4


## Forms

- `<form>` element is used to create an HTML form for user inputs
  - `action` attribute specifies where the data should be sent/submmited
  - `method` attribute specifies how to send form-data
- `<input>` element is an inline element that specifies an input field where the user can enter data, it also has a lot of attributes:
  - `text` attribute is the default attribute of `<input>` and will display a text field
  - `email` attribute is a field to enter a valid email address which has validation to check if it's a valid email
  - `placeholder` attribute will display a temporary text
  - `value` attribute specifies the value of the element
  - `color` attribute gives you a control to open a color picker
  - `date` attribute gives you a control for entering a date
  - `number` attribute display a field to enter only a valid number
  - `name` attribute is used by the server to identify the piece of data in form submits
  - `password` attribute display a text field to enter a password and it will conceil it, so it doesn't should the real text  
  - `submit` attribute is rendered as buttons
  - `radio` attribute generates a radio button and the user can only select one item
  - `checkbox` attribute that will allow you to select and deselect items by ticking the box
  - `checked` is a _boolean_ attribute, if present it will select the item
- `<label>` element represents a caption which must be associated for the particular input to support assistive technology
  - `for` attribute is used to associate the `<label>` element into an `id` of `<input>` element
- `<button>` element represents a clickable button which is used to submit forms
- `<textarea>` element represents a multi-line plain text editing control
- `<select>` element represents a control that provides a menu of options
  - `<option>` element is used to define an item contained in a `<select>`
- `required` is a boolean attribute which specifies that an input field must be filled out before submitting the form

---

Credits to Colt's Code Camp
