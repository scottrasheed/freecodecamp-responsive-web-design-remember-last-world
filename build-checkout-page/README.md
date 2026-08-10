# 🛒 Checkout Page

A simple HTML checkout page that demonstrates how to structure a shopping cart and payment form using semantic HTML and accessible form practices.

## 👀 Preview

The page contains two main sections:

* **Your Cart** — Displays a product, image, and price.
* **Payment Information** — Contains a form for entering cardholder and card information.

Required fields are visually indicated while remaining accessible to screen readers.

## 📖 Overview

This project was created as part of a freeCodeCamp lab focused on building an accessible checkout page.

The project uses semantic HTML elements such as `<section>`, `<form>`, `<label>`, and `<p>` to organize the checkout experience.

The payment form also uses accessibility attributes such as `aria-describedby` and `aria-hidden` to provide additional context without creating unnecessary screen-reader output.

## 🧠 What I Learned

Through this project, I practiced:

* Structuring a webpage with semantic HTML
* Using `<section>` elements to organize content
* Creating accessible form labels
* Associating labels with inputs using `for` and `id`
* Using the `required` attribute
* Visually indicating required fields
* Using `aria-hidden` for decorative symbols
* Using `aria-describedby` to connect help text to an input
* Providing meaningful `alt` text for images
* Creating a basic checkout form

## 📁 Files

```text
checkout-page/
│
├── index.html
└── README.md
```

## 🛠️ Technologies Used

* HTML5

## 🚀 How to View

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. The checkout page will be displayed.
4. Test the payment form by interacting with the required fields.

## ✅ Expected Output

The page should display:

### Your Cart

* A product image
* Product name
* Product price

### Payment Information

* Cardholder Name field
* Card Number field
* Required-field indicators
* Card number formatting instructions
* Complete Purchase button

## ♿ Accessibility

The form includes accessibility features such as:

* Labels associated with their corresponding inputs
* `alt` text for the product image
* Required-field indicators hidden from screen readers with `aria-hidden`
* Card number instructions connected through `aria-describedby`

## 🎓 Course Reference

This project was created as part of the **freeCodeCamp Responsive Web Design** curriculum.

## 👤 Author

**Scott Rasheed**

GitHub: `scottrasheed`

---

*Built while learning HTML, accessibility, and web development.*
