# 📝 Parent Teacher Conference Form

A responsive and styled parent-teacher conference form built with **HTML and CSS** as part of the **freeCodeCamp Responsive Web Design** curriculum.

The project demonstrates how to structure a multi-section HTML form and customize its appearance using CSS, including custom radio buttons, form fields, pseudo-elements, hover effects, Flexbox-related alignment techniques, and responsive sizing.

## 📸 Preview

The form includes sections for:

* 👩‍🎓 Student Information
* 👨‍👩‍👧 Parent/Guardian Information
* 📞 Preferred Contact Method
* 📝 Additional Notes
* ✅ Form submission

The design uses a dark midnight-blue theme with semi-transparent containers and custom-styled form controls.

## 🛠️ Technologies Used

* HTML5
* CSS3
* CSS pseudo-elements
* CSS pseudo-classes
* CSS transitions
* Responsive sizing
* Custom form controls

## 📂 Project Structure

```text
parent-teacher-conference-form/
├── index.html
└── styles.css
```

### `index.html`

Contains the complete HTML structure of the form, including:

* Main page container
* Page heading and description
* Student information fields
* Parent/guardian information
* Email and phone radio buttons
* Additional notes textarea
* Submit button

### `styles.css`

Contains the complete visual styling for the form, including:

* Page colors
* Container styling
* Typography
* Fieldset borders
* Input and textarea styling
* Custom radio buttons
* CSS pseudo-elements
* Transitions
* Button styling
* Hover effects

## 📚 What I Learned

### HTML Forms

This project provided practice creating forms using elements such as:

```html
<form>
<fieldset>
<legend>
<label>
<input>
<textarea>
<button>
```

These elements help organize user input into clear and accessible sections.

### Form Labels

Each form control is associated with a label using matching `for` and `id` attributes.

For example:

```html
<label for="student-name">Full Name: </label>
<input
  type="text"
  name="student-name"
  id="student-name"
>
```

This creates a clear relationship between the label and its corresponding input.

### Radio Buttons

The contact method section uses radio buttons that share the same `name` attribute:

```html
<input
  id="email"
  class="contact-method-radio-btn"
  type="radio"
  name="contact-method"
  value="email"
  checked
>
```

Because the buttons share the same name, the user can select only one contact method.

### Custom Radio Buttons

The browser's default radio-button appearance was removed with:

```css
.contact-method-radio-btn {
  appearance: none;
}
```

The radio buttons were then rebuilt using CSS.

The `::before` pseudo-element creates the inner circle:

```css
.contact-method-radio-btn::before {
  display: block;
  content: " ";
  width: 10px;
  height: 10px;
  border-radius: 50%;
}
```

The inner circle becomes visible when the radio button is selected:

```css
.contact-method-radio-btn:checked::before {
  transform: translate(3px, 3px) scale(1);
  background-color: lightgreen;
}
```

### CSS Selectors

The project uses several advanced selectors, including:

```css
label:not(.contact-method)
```

and:

```css
input:not(.contact-method-radio-btn)
```

The `:not()` pseudo-class allows specific elements to be excluded from a styling rule.

### CSS Transitions

The custom radio button uses a transition to smoothly animate the inner circle:

```css
transition: all 0.3s ease-in;
```

### Button Hover Effects

The submit button changes color when the user hovers over it:

```css
.submit-btn:hover {
  background-color: midnightblue;
}
```

This provides visual feedback that the button is interactive.

## 🎨 Design

The form uses a dark theme based around:

* Midnight blue
* Whitesmoke
* Semi-transparent white
* Gray borders
* Royal blue
* Light green

The container uses a semi-transparent white background and a shadow to create separation from the page background.

```css
.container {
  background-color: #ffffff1a;
  width: 80%;
  max-width: 600px;
  border-radius: 10px;
  margin: 20px auto;
  padding: 10px 20px;
  box-shadow: 0 5px 15px black;
}
```

## 🎯 Project Goal

The goal of this workshop was to practice building and styling a complete HTML form while learning how CSS can be used to create custom form controls and interactive elements.

## 🚀 How to View

1. Open the project folder.
2. Open `index.html` in a web browser.
3. Enter information into the form fields.
4. Select a preferred contact method.
5. Add any additional notes.
6. Hover over the submit button to see its interactive styling.

## 🎓 Course

This project was completed as part of:

**freeCodeCamp — Responsive Web Design**

Workshop: **Parent Teacher Conference Form**

## 🧠 Skills Practiced

* HTML5 forms
* Form labels
* Input elements
* Radio buttons
* Textareas
* Buttons
* Fieldsets and legends
* CSS selectors
* `:not()` pseudo-class
* `:checked` pseudo-class
* `::before` pseudo-element
* CSS transitions
* Custom form controls
* Responsive widths
* Borders and border-radius
* Hover states
* Basic UI design

## 👤 Author

**Scott Rasheed**

GitHub: [@scottrasheed](https://github.com/scottrasheed)

---

*Part of my journey learning web development through freeCodeCamp.*
