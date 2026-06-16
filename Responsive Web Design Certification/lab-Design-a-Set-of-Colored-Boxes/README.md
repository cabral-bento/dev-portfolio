<h1 align="center">🎨 Design a Set of Colored Boxes</h1>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white">
  <img alt="freeCodeCamp Lab" src="https://img.shields.io/badge/freeCodeCamp-Lab-0A0A23?style=flat&logo=freecodecamp&logoColor=white">
</p>

> Practice lab from the **Responsive Web Design** certification (freeCodeCamp).

## 📖 Overview

A small page that renders a **row of five colored boxes** to practice the different ways CSS lets
you define colors. Each box is filled using a **different color notation**, making it a clear,
side-by-side reference for the main CSS color models.

## 🌈 The color models used

| Box | Value | Notation |
|-----|-------|----------|
| 1 | `#ff5733` | **HEX** |
| 2 | `rgb(52, 152, 219)` | **RGB** |
| 3 | `green` | **Named color** |
| 4 | `hsl(300, 60%, 50%)` | **HSL** |
| 5 | `orange` | **Named color** |

## ✨ Features

- **Flexbox layout** — the boxes live in a `.color-grid` container using
  `display: flex` with `justify-content: center` and a `gap` of `50px` to space them evenly and
  keep them centered on the page.
- **Consistent box styling** — every `.color-box` shares the same `150px × 150px` size and a
  `10px` `border-radius` for soft, rounded corners.
- **Clean typography** — centered heading on a light `#f4f4f4` background.

## 🧠 Concepts practiced

| Concept | Where it's used |
|---------|-----------------|
| CSS color models | HEX, RGB, HSL and named colors |
| Flexbox | `display: flex`, `justify-content`, `gap` |
| Box sizing & shape | `width`, `height`, `border-radius` |
| Reusable classes | shared `.color-box` + per-box modifier classes |

## 📂 Files

```
lab-Design-a-Set-of-Colored-Boxes/
├── index.html   → page structure and the five boxes
├── index.css    → layout and the color definitions
└── README.md
```

## 🚀 How to run

Open `index.html` in any modern browser — no build step or dependencies required.

---

<p align="center"><sub>Part of my <a href="../../README.md">Dev Portfolio</a> · freeCodeCamp practice lab</sub></p>
