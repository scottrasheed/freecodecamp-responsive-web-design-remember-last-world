# 🎉 Design a Greeting Card

A simple interactive birthday greeting card built with **HTML and CSS** as part of the **freeCodeCamp Responsive Web Design** curriculum.

This project focuses on creating a styled greeting card, adding CSS transitions and pseudo-elements, and using the `:target` pseudo-class to display different sections when the user clicks a link.

## 📸 Preview

The project features a birthday greeting card with:

* 🎉 Birthday-themed heading decorations
* 💬 A personalized birthday message
* 🔗 Send Card and Share on Social Media links
* 🖱️ Hover effects and transitions
* 🎯 Interactive sections controlled with URL fragments
* 📱 Responsive viewport configuration

## 🛠️ Technologies Used

* HTML5
* CSS3
* CSS pseudo-elements
* CSS pseudo-classes
* CSS transitions
* Flexbox

## 📂 Project Structure

```text
design-a-greeting-card/
├── index.html
└── styles.css
```

### `index.html`

Contains the structure and content of the greeting card, including:

* The main greeting card
* Birthday message
* Send Card link
* Share on Social Media link
* Send confirmation section
* Share confirmation section

### `styles.css`

Contains all visual styling and interactive behavior, including:

* Card layout and styling
* Colors and typography
* Hover effects
* Transitions
* Flexbox positioning
* `::before` and `::after` pseudo-elements
* `:hover`, `:active`, `:focus`, and `:visited` pseudo-classes
* `:target` section behavior

## 📚 What I Learned

Through this workshop, I practiced several important CSS concepts.

### CSS Transitions

The greeting card uses a transition to smoothly animate changes to its size and background color.

```css
transition: transform 0.3s, background-color 0.3s ease;
```

### CSS Pseudo-Elements

The birthday emojis are added using `::before` and `::after` rather than placing them directly into the HTML.

```css
h1::before {
  content: "🥳 ";
}

h1::after {
  content: " 🥳";
}
```

### CSS Pseudo-Classes

The project uses several pseudo-classes to create interactive states:

```css
.card:hover
.card-links a:hover
.card-links a:active
.card-links a:focus
.card-links a:visited
```

These allow elements to respond to different user interactions.

### `:target`

The project uses the `:target` pseudo-class to control which section is visible after a link is clicked.

```css
section {
  display: none;
}

section:target {
  display: block;
}
```

This allows the page to show the appropriate message without JavaScript.

### Flexbox

The card's links are arranged using Flexbox:

```css
.card-links {
  display: flex;
  justify-content: space-around;
}
```

## 🎯 Project Goal

The goal of this workshop was to practice combining HTML structure with CSS styling and interactive states to create a functional greeting card.

The completed project demonstrates how CSS alone can provide basic interaction and visual feedback without requiring JavaScript.

## 🚀 How to View

1. Open the project folder.
2. Open `index.html` in a web browser.
3. Hover over the greeting card to see the card animation.
4. Hover over the links to see their interactive styling.
5. Click **Send Card** to display the sending confirmation.
6. Click **Share on Social Media** to display the sharing confirmation.

## 🎓 Course

This project was completed as part of:

**freeCodeCamp — Responsive Web Design**

Workshop: **Design a Greeting Card**

## 🧠 Skills Practiced

* HTML document structure
* Semantic elements
* CSS selectors
* CSS pseudo-elements
* CSS pseudo-classes
* CSS transitions
* Flexbox
* Element positioning
* Interactive links
* URL fragment targeting
* Basic responsive setup

## 👤 Author

**Scott Rasheed**

GitHub: [@scottrasheed](https://github.com/scottrasheed)

---

*Part of my journey learning web development through freeCodeCamp.*
