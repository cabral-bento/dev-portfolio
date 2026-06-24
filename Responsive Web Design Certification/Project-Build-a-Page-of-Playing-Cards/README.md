<h1 align="center">🃏 Build a Page of Playing Cards</h1>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white">
  <img alt="freeCodeCamp Project" src="https://img.shields.io/badge/freeCodeCamp-Project-0A0A23?style=flat&logo=freecodecamp&logoColor=white">
</p>

> Certification project from the **Responsive Web Design** course (freeCodeCamp).

## Overview

A responsive page that recreates a hand of **playing cards** — the Ace of Spades, 2 of Clubs,
3 of Hearts, 4 of Clubs and 5 of Diamonds — built entirely with **HTML and CSS Flexbox**. Each
card reproduces the real layout of a deck: rank and suit in the top-left and bottom-right corners
(the bottom one rotated 180°), and the suit pips arranged in the centre according to the card's
value.

## Features

- **Flexbox table** — `#playing-cards` is a flex container with `flex-wrap` and `gap`, centring
  the cards and letting them reflow onto multiple rows on smaller screens.
- **Three-zone cards** — every `.card` uses `justify-content: space-between` to split content into
  `.left`, `.middle` and `.right` zones, matching a real card's corners and centre.
- **Rotated corners** — the bottom-right index is flipped with the `.element-180`
  (`transform: rotate(180deg)`) utility class, so the card reads correctly from both ends.
- **Suit-accurate pip layouts** — the centre of each card uses nested flex rows (e.g. the
  `.five-simble` 2-1-2 arrangement) to place the right number of pips for each rank.
- **Colour coding** — `.red-element` colours the Hearts and Diamonds cards red, while Spades and
  Clubs stay black, just like a standard deck.
- **Card styling** — fixed `width`/`height`, `border-radius` and `box-shadow` give each card a
  crisp, slightly raised look on a light `#E0FFFF` table.

## Concepts practiced

| Concept | Where it's used |
|---------|-----------------|
| Flexbox layout | `display: flex`, `justify-content`, `align-items` |
| Wrapping & spacing | `flex-wrap: wrap`, `gap` on `#playing-cards` |
| Flex alignment | `align-self` for top/centre/bottom corners |
| Nested flex | `.row` groups inside `.five-simble` |
| CSS transforms | `transform: rotate(180deg)` utility class |
| Box model & depth | `box-shadow`, `border-radius`, fixed sizing |

## Files

```
Project-Build-a-Page-of-Playing-Cards/
├── index.html   → five card structures (rank, suit, pip zones)
├── index.css    → flex table, card layout and pip arrangements
└── README.md
```

## How to run

Open `index.html` in any modern browser — no build step or dependencies required.

---

<p align="center"><sub>Part of my <a href="../../README.md">Dev Portfolio</a> · freeCodeCamp certification project</sub></p>
