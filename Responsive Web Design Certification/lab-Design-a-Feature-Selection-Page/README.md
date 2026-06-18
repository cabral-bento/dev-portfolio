<h1 align="center">🧩 Design a Feature Selection Page</h1>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white">
  <img alt="freeCodeCamp Lab" src="https://img.shields.io/badge/freeCodeCamp-Lab-0A0A23?style=flat&logo=freecodecamp&logoColor=white">
</p>

> Practice lab from the **Responsive Web Design** certification (freeCodeCamp).

## 📖 Overview

A **feature selection page** built with semantic HTML and pure CSS. Six product features are laid
out as a **two-column grid of cards**, each with a custom-styled checkbox so the user can pick the
options they want. The whole card is clickable thanks to the `<label>`-wrapping technique, and the
native checkbox appearance is fully restyled with CSS — no JavaScript involved.

## ✨ Features

- **CSS Grid layout** — `.feature-card-container` uses `grid-template-columns: repeat(2, 1fr)`
  with a `gap`, centered and capped at `max-width: 900px`, so the six cards sit in a tidy
  two-column grid.
- **Six feature cards** — Cloud Storage, 24/7 Customer Help, Advanced Analytics, Custom User
  Themes, Multi-User Collab and API Access, each with a short description.
- **Whole-card clickability** — each card is a `<label>` wrapping its `<input>`, so clicking
  anywhere on the card toggles the checkbox.
- **Custom checkboxes** — native appearance removed with `appearance: none` and rebuilt with a
  rounded border, a colored `:checked` state and a CSS-generated check mark (`::after { content: "✓" }`).
- **Hover feedback** — cards gain a glowing shadow and a highlighted border on `:hover`.
- **Visual depth** — `box-shadow`, `border-radius` and a translucent container background.

## 🧠 Concepts practiced

| Concept | Where it's used |
|---------|-----------------|
| CSS Grid | `grid-template-columns`, `gap`, `max-width` |
| Custom form controls | `appearance: none`, `:checked`, `::after` |
| Label-wrapped inputs | clickable `<label class="feature-card">` cards |
| Interactive states | `:hover`, `:checked`, `transition` |
| Visual design | `box-shadow`, `border-radius`, translucent backgrounds |

## 📂 Files

```
lab-Design-a-Feature-Selection-Page/
├── index.html   → page structure and feature cards
├── index.css    → grid layout, card styling and custom checkboxes
└── README.md
```

## 🚀 How to run

Open `index.html` in any modern browser — no build step or dependencies required.

---

<p align="center"><sub>Part of my <a href="../../README.md">Dev Portfolio</a> · freeCodeCamp practice lab</sub></p>
