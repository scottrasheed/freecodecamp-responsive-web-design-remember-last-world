# 💝 Debug a Donation Form

A simple HTML form debugging project focused on fixing syntax errors and improving form accessibility. This project demonstrates how to properly connect labels with form inputs and use appropriate input types and validation attributes.

## 👀 Preview

The project displays a donation form where users can provide:

* Their full name
* Email address
* Donation amount
* Newsletter subscription preference

The form also includes a submit button for sending the donation information.

## 📖 Overview

This project was created as part of a freeCodeCamp lab focused on debugging and accessibility.

The original form contained several HTML issues, including invalid closing tags for `<input>` elements, missing labels, an incorrect input type for the email field, and missing accessibility associations between labels and inputs.

The goal was to correct these issues while keeping the original structure and functionality of the form.

## 🧠 What I Learned

Through this project, I practiced:

* Debugging HTML syntax errors
* Understanding void elements
* Creating accessible form labels
* Using the `for` attribute on `<label>` elements
* Matching `for` attributes with input `id` attributes
* Using the correct `email` input type
* Using the `required` attribute for form validation
* Understanding which form fields should and should not be required
* Structuring accessible HTML forms

## 📁 Files

```text
debug-donation-form/
│
├── index.html
└── README.md
```

## 🛠️ Technologies Used

* HTML5

## 🚀 How to View

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. The donation form will be displayed.
4. Try submitting the form without completing the required fields to see the built-in validation.

## ✅ Expected Output

The completed form should contain:

* **Full Name:** — required text input
* **Email Address:** — required email input
* **Donation Amount ($):** — required number input
* **Subscribe** — optional checkbox
* **Send** — submit button

All form inputs should have an associated `<label>` for accessibility.

## 🎓 Course Reference

This project was created as part of the **freeCodeCamp Responsive Web Design** curriculum.

## 👤 Author

**Scott Rasheed**

GitHub: `scottrasheed`

---

*Built while learning HTML, accessibility, and web development.*
