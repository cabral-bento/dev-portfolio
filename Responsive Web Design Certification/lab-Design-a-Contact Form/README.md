<h1 align="center">✉️ Design a Contact Form</h1>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white">
  <img alt="freeCodeCamp Lab" src="https://img.shields.io/badge/freeCodeCamp-Lab-0A0A23?style=flat&logo=freecodecamp&logoColor=white">
</p>

> Practice lab from the **Responsive Web Design** certification (freeCodeCamp).

## 📖 Overview

A compact, centered **contact form** built with semantic HTML and pure CSS. The page collects a
visitor's **name, email and message** and relies on the browser's native HTML validation
(`required` fields and the `email` input type) to ensure the form is filled in correctly before
submission — no JavaScript required.

## ✨ Features

- **Centered, responsive card** — the `.container` is capped at `max-width: 400px` and centered
  with `margin: auto`, while the inner `.form-container` uses a percentage width so it scales
  cleanly from mobile to desktop.
- **Three required fields:**
  - A text input for the **name**.
  - An `email` input with built-in email-format checking.
  - A `<textarea>` for the **message**.
- **Native validation** — every field is marked `required`, so the browser blocks submission of
  empty fields automatically.
- **Accessible markup** — each field is tied to its `<label>` through matching `for`/`id`
  attributes.
- **Dark-red theme** — rounded corners (`border-radius`), generous padding and a `skyblue` submit
  button that turns blue on `:hover`.

## 🧠 Concepts practiced

| Concept | Where it's used |
|---------|-----------------|
| Semantic form structure | `form`, `label`, `input`, `textarea`, `button` |
| Native HTML validation | `required`, `type="email"` |
| Responsive centering | `max-width`, `margin: auto`, percentage widths |
| Interactive styling | `button:hover` |
| Visual design | `border-radius`, `padding`, color theming |

## 📂 Files

```
lab-Design-a-Contact Form/
├── index.html   → form structure and fields
├── index.css    → layout, theming and button styling
└── README.md
```

## 🚀 How to run

Open `index.html` in any modern browser — no build step or dependencies required.

---

<p align="center"><sub>Part of my <a href="../../README.md">Dev Portfolio</a> · freeCodeCamp practice lab</sub></p>
