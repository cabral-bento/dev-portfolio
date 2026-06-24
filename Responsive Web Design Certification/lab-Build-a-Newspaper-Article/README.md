<h1 align="center">Build a Newspaper Article</h1>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white">
  <img alt="freeCodeCamp Lab" src="https://img.shields.io/badge/freeCodeCamp-Lab-0A0A23?style=flat&logo=freecodecamp&logoColor=white">
</p>

> Practice lab from the **Responsive Web Design** certification (freeCodeCamp).

## Overview

A classic **newspaper article** layout rendered with pure HTML and CSS. The page recreates the
look of a printed paper — a centered column on a tinted background, an uppercase masthead in a
serif typeface, an italic sub-headline, a byline, and body paragraphs with an old-school
**drop cap** on the first letter.

## Features

- **Centered article column** — a fixed-width `.newspaper` card centered with `margin: auto` on a
  soft `#D4EBF2` page background.
- **Typographic hierarchy** — masthead (`.name`), date, headline, italic sub-headline, byline and
  body text each get distinct sizing, weight and spacing.
- **Relative units in action** — base `font-size` set on `html` (24px) and `.newspaper` (16px),
  with headings sized in `rem` vs `em` to show how the two units resolve differently.
- **Drop cap** — the `::first-letter` pseudo-element enlarges and bolds the first character of each
  body paragraph for a print-style flourish.
- **Print-like details** — uppercase masthead/byline via `text-transform`, indented paragraphs with
  `text-indent`, and a thin `font-weight: 100` italic sub-headline.

## Concepts practiced

| Concept | Where it's used |
|---------|-----------------|
| `rem` vs `em` units | headings sized relative to root vs parent font-size |
| Pseudo-elements | `::first-letter` drop cap |
| Text styling | `text-transform`, `text-indent`, `font-style`, `font-weight` |
| Multiple selectors | grouped `.name, .author` rule |
| Centered fixed layout | `margin: auto` + fixed `width` |

## Files

```
lab-Build-a-Newspaper-Article/
├── index.html   → article structure (masthead, headline, byline, body)
├── index.css    → typography, drop cap and layout
└── README.md
```

## How to run

Open `index.html` in any modern browser — no build step or dependencies required.

---

<p align="center"><sub>Part of my <a href="../../README.md">Dev Portfolio</a> · freeCodeCamp practice lab</sub></p>
