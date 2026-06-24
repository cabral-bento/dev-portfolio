<h1 align="center">Build a Job Application Form</h1>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white">
  <img alt="freeCodeCamp Lab" src="https://img.shields.io/badge/freeCodeCamp-Lab-0A0A23?style=flat&logo=freecodecamp&logoColor=white">
</p>

> Practice lab from the **Responsive Web Design** certification (freeCodeCamp).

## Overview

A responsive **job application form** built with semantic HTML and CSS. The page collects an
applicant's details and gives **instant visual feedback** on each field using native CSS
validation pseudo-classes — no JavaScript involved. It is a focused exercise on accessible form
markup and pure-CSS state styling.

## Features

- **Centered, responsive card** — `width: 80%` with `max-width: 600px`, so it adapts from mobile
  to desktop while staying readable, with rounded corners and a soft `box-shadow`.
- **Full set of form controls:**
  - Text input for the full name and an `email` input (with built-in email format checking).
  - A `<select>` dropdown to choose the **position** (marked `required`).
  - A `<fieldset>` / `<legend>` **radio group** for availability (Full-Time / Part-Time).
  - A `<textarea>` for a free-text "Why do you want this job?" answer.
  - A submit button to send the application.
- **Live validation styling (CSS only):**
  - `:focus` highlights the active field.
  - `:valid` turns borders **green**; `:invalid` turns them **red**.
- **Custom-styled radio buttons** — native appearance is removed with `appearance: none`
  (`-webkit-appearance` for Safari) and rebuilt as circular controls; the checked option and its
  label change color via `:checked` and the `:checked + label` adjacent-sibling selector.
- **Accessible markup** — every input is tied to its `<label>` through matching `for`/`id`
  attributes, and the radio group is grouped semantically inside a `fieldset`.

## Concepts practiced

| Concept | Where it's used |
|---------|-----------------|
| Semantic form structure | `form`, `fieldset`, `legend`, `label`, `section` |
| CSS validation pseudo-classes | `:valid`, `:invalid`, `:focus` |
| Custom form controls | `appearance: none` radio buttons |
| Advanced selectors | `:checked + label`, `:not()`, `:first-of-type` |
| Responsive layout | `max-width`, percentage widths, `margin: auto` |
| Visual depth | `box-shadow`, `border-radius` |

## Files

```
lab-Build-a-Job-Application-Form/
├── index.html   → form structure and fields
├── index.css    → layout, theming and validation styling
└── README.md
```

## How to run

Open `index.html` in any modern browser — no build step or dependencies required.

---

<p align="center"><sub>Part of my <a href="../../README.md">Dev Portfolio</a> · freeCodeCamp practice lab</sub></p>
