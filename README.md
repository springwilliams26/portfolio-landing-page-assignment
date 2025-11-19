# Spring Williams – Personal Portfolio Landing Page

This project is a pixel-aligned implementation of the **Personal Portfolio Template** Figma design, rebranded with my own content and built with semantic HTML and custom CSS.

Figma template:  
“🎨 Personal Portfolio Template – Community”

---

## ✨ Overview

The goal of this project was to:

- Rebuild the provided Figma design in code
- Replace all placeholder content with my own information
- Practice layout, typography, and spacing accuracy
- Prepare a clean starting point for a future multi-page portfolio

The current implementation focuses on the **landing / hero section** of the design.

---

## 🧩 Features

- **Top navigation bar**

  - Centered 920px inner container within a 1110px bar
  - Navigation links: Home, Case Studies, Testimonials, Recent Work, Get In Touch
  - Social icons for LinkedIn, Behance, Twitter (LinkedIn opens in a new tab)

- **Hero section**

  - Left column with my name and a short intro paragraph
  - CTA button (“View My Work”) styled to match the original, with a right-arrow SVG icon
  - Right column with a 350×350 circular headshot, positioned to match the Figma

- **“Worked with” strip**

  - Label “Worked with”
  - Four company buttons (Charles Schwab, ADP, Wilkes University, City of Phoenix)
  - Equal-width buttons with subtle borders and rounded corners

- **Accessibility touches**
  - Semantic `<header>`, `<main>`, and `<section>` elements
  - Descriptive `alt` text on the headshot
  - `aria-label` for the navigation and social icons
  - Visible focus styles for keyboard users (`a:focus` outline)

---

## 🛠 Tech Stack

- **HTML5**
- **CSS3**
- No frameworks or JavaScript required

---

## 📁 Project Structure

```text
.
├── index.html       # Main landing page
├── styles.css       # Global and layout styles
└── images/          # SVG icons and headshot image
    ├── LinkedIn.svg
    ├── Behance.svg
    ├── Twitter.svg
    ├── RightArrow.svg
    └── professional_image.png
```
