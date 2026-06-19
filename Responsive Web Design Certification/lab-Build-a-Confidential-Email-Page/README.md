<h1 align="center">🕵️ Build a Confidential Email Page</h1>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white">
  <img alt="freeCodeCamp Lab" src="https://img.shields.io/badge/freeCodeCamp-Lab-0A0A23?style=flat&logo=freecodecamp&logoColor=white">
</p>

> Practice lab from the **Responsive Web Design** certification (freeCodeCamp).

## 📖 Overview

A playful **confidential email** mockup styled like a classified secret-agent memo. The page
renders a parchment-style card with rotated **CONFIDENTIAL** and **TOP SECRET** stamps, and uses
the CSS `blur()` filter to **redact** sensitive parts of the message — recreating the look of a
censored document with pure HTML and CSS.

## ✨ Features

- **Memo card** — a centered `<main>` with fixed width, padding, a rounded border and a soft
  `box-shadow`, on a parchment-like `#FAF0E6` background.
- **Rotated stamps** — the **CONFIDENTIAL** and **TOP SECRET** badges are styled with red borders
  and tilted using `transform: rotate()` for an authentic stamped look.
- **Redacted text** — sensitive spans carry a `.blurred` class that applies `filter: blur(3px)`,
  censoring key words inline while keeping the rest readable.
- **Responsive meta** — includes the `viewport` meta tag and `box-sizing: border-box` for
  predictable sizing.
- **Semantic structure** — content wrapped in `<main>` with `<p>` paragraphs and inline `<span>`
  redactions.

## 🧠 Concepts practiced

| Concept | Where it's used |
|---------|-----------------|
| CSS transforms | `transform: rotate()` on the stamps |
| CSS filters | `filter: blur()` for redacted text |
| Inline vs block styling | `display: inline-block`, inline `<span>` |
| Box model & depth | `box-shadow`, `border-radius`, `box-sizing` |
| Centered layout | `margin: auto`, fixed `width` |

## 📂 Files

```
lab-Build-a-Confidential-Email-Page/
├── index.html   → memo structure, stamps and redacted spans
├── index.css    → card, stamp and blur styling
└── README.md
```

## 🚀 How to run

Open `index.html` in any modern browser — no build step or dependencies required.

---

<p align="center"><sub>Part of my <a href="../../README.md">Dev Portfolio</a> · freeCodeCamp practice lab</sub></p>
