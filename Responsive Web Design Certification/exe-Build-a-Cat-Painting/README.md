# Build a Cat Painting

A cat's face drawn entirely with **HTML and CSS** — no images. Every feature
(ears, eyes, nose, mouth, whiskers) is a positioned `<div>` shaped with borders,
border-radius and transforms. A practice exercise from the freeCodeCamp
**Responsive Web Design** certification.

## What it does

- Renders a centered cat head using an absolutely positioned, rounded container.
- Builds the ears, inner ears, nose and mouth from CSS **border triangles** and
  partial `border-radius` values.
- Adds eyes with rotated ellipses, plus thin `<div>` lines rotated into place to
  form the whiskers.

## Tech & concepts

- **CSS positioning** — `position: absolute` with `top`/`left`/`right`/`bottom`
  and `margin: auto` for centering.
- **Border tricks** — transparent borders to draw triangles (ears, nose, mouth).
- **`transform: rotate()`** — to angle ears, eyes and whiskers.
- **`border-radius`** (including the `/` syntax) and **linear-gradient** fills.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Structure of the cat's facial features |
| `index.css`  | All shaping, positioning and styling |

## How to run

Open `index.html` in any web browser.
