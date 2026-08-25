# 💼 Job Application Form

A responsive and interactive job application form built with **HTML and CSS** as part of the **freeCodeCamp Responsive Web Design** curriculum.

This project focuses on building a structured form and using CSS pseudo-classes to provide visual feedback when users interact with the form.

## 📸 Preview

The form includes:

* 👤 Full name field
* 📧 Email address field
* 💼 Position selection
* 🕐 Availability options
* 📝 Message textarea
* ✅ Submit button
* 🎨 Interactive validation and focus states

The design uses a modern dark theme with blue accents and green/red validation feedback.

## 🛠️ Technologies Used

* HTML5
* CSS3
* CSS pseudo-classes
* Form validation
* Responsive sizing
* Flexbox

## 📂 Project Structure

```text
job-application-form/
├── index.html
└── styles.css
```

### `index.html`

Contains the complete structure of the job application form, including:

* Form container
* Full name input
* Email input
* Job position dropdown
* Availability radio buttons
* Message textarea
* Submit button

### `styles.css`

Contains the visual styling and interactive behavior for the form, including:

* Dark-themed layout
* Form field styling
* Focus states
* Validation states
* Custom radio button styling
* Hover effects
* Rounded input styling
* Responsive container sizing

## 📚 What I Learned

### Form Structure

The project provided practice with several HTML form elements:

```html
<form>
<input>
<select>
<option>
<fieldset>
<legend>
<textarea>
<button>
```

These elements allow a webpage to collect different types of user information.

### Label Association

Every form control is associated with a `<label>` using matching `for` and `id` attributes.

For example:

```html
<label for="email">Email Address</label>
<input type="email" id="email" name="email">
```

This improves usability and accessibility.

### CSS `:focus`

The form provides visual feedback when a user focuses on an input or textarea:

```css
input:focus,
textarea:focus {
    border-color: royalblue;
    outline: none;
}
```

The default browser outline is removed and replaced with a custom border color.

### CSS Validation States

The form uses `:valid` and `:invalid` to visually communicate whether the entered information meets the form requirements.

```css
input:invalid,
select:invalid,
textarea:invalid {
    border-color: red;
}

input:valid,
select:valid,
textarea:valid {
    border-color: green;
}
```

This provides immediate visual feedback to the user.

### Custom Radio Button States

The availability options use the `:checked` pseudo-class:

```css
.radio-group input[type="radio"]:checked {
    border-color: lightgreen;
    background-color: lightgreen;
    box-shadow: 0 0 8px lightgreen;
}
```

The associated label also changes color when its radio button is selected:

```css
.radio-group input[type="radio"]:checked + label {
    color: lightgreen;
}
```

### `:first-of-type`

The first input field receives a different border radius:

```css
input:first-of-type {
    border-radius: 15px;
}
```

This demonstrates how structural pseudo-classes can be used to target specific elements.

### Hover Effects

The submit button changes its background color when the user hovers over it:

```css
button:hover {
    background-color: midnightblue;
}
```

This provides clear visual feedback that the button is interactive.

## 🎨 Design

The project uses a dark interface with contrasting colors for different states:

* Dark navy background
* Semi-transparent form container
* Whitesmoke text
* Royal blue interactive elements
* Green valid states
* Red invalid states
* Light green selected radio buttons

The design was intentionally kept simple while adding enough visual feedback to make the form feel interactive.

## 🎯 Project Goal

The goal of this lab was to practice creating a complete job application form and using CSS pseudo-classes to create interactive and responsive user feedback.

## 🚀 How to View

1. Open the `job-application-form` folder.
2. Open `index.html` in a web browser.
3. Enter information into the form fields.
4. Select a job position.
5. Choose an availability option.
6. Enter a message.
7. Interact with the form fields to see the focus and validation states.
8. Hover over the submit button to see its hover effect.

## 🎓 Course

This project was completed as part of:

**freeCodeCamp — Responsive Web Design**

Lab: **Job Application Form**

## 🧠 Skills Practiced

* HTML5
* HTML forms
* Labels and form controls
* Input types
* Select menus
* Radio buttons
* Textareas
* Fieldsets and legends
* CSS selectors
* `:focus`
* `:valid`
* `:invalid`
* `:hover`
* `:checked`
* `:first-of-type`
* Adjacent sibling selectors
* Form validation styling
* Responsive widths
* Flexbox
* UI styling

## 👤 Author

**Scott Rasheed**

GitHub: [@scottrasheed](https://github.com/scottrasheed)

---

*Part of my journey learning web development through freeCodeCamp.*
