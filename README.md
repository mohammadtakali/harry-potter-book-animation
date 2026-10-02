# 📖 Hogwarts Book & Letter | CSS 3D Animation

A pure **CSS3** experiment recreating a magical, book-opening interaction — inspired by the Harry Potter universe. Hover over a closed book to watch it flip open in 3D, and hover over a wax-sealed envelope to watch the letter slide out. ✨

No JavaScript, no frameworks — every animation is built with `transform`, `transform-style: preserve-3d`, and `transition` in plain CSS. 🪄

## 📑 Table of Contents

- [Demo](#-demo)
- [Features](#-features)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [Author](#-author)

## 🔗 Demo

[Live Demo](https://mohammadtakali.github.io/harry-potter-book-animation/) 
## ✨ Features

- 📘 **3D Book Flip (Hero Section):** A closed book with a front cover and spine that rotates open in 3D perspective on hover.
- 📜 **Interactive Reading Book (Section 2):** Hovering reveals the book's inside page with a passage of text, animated with `preserve-3d` transforms.
- 💌 **Wax-Sealed Envelope (Section 3):** A hand-built CSS envelope (front flap, body, and letter) using pure border tricks — the flap opens and the letter slides up on hover.
- 🌙 **Cinematic Footer:** Full-bleed background image with a hover-reveal social navigation (Instagram, LinkedIn, GitHub).
- ✒️ **Custom Typography:** Google Fonts `Lavishly Yours` for a handwritten, storybook feel.
- ⚡ **Zero Dependencies:** No JavaScript, no build tools — just HTML & CSS.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🧱 HTML5 | Semantic markup and page structure |
| 🎨 CSS3 | 3D transforms, transitions, and nested SCSS-style selectors |
| 🧩 Font Awesome 6 | Social icons in the footer |
| 🔤 Google Fonts | `Lavishly Yours` typography |

## 📂 Project Structure

```text
hp-book-project/
│
├── index.html                  # Main application file
│
└── assets/
    ├── css/
    │   ├── master.css          # Section layout & 3D animations
    │   └── public.css          # Global resets & base rules
    │
    └── images/
        ├── cover.jpg            # Book front cover
        ├── back.jpg             # Book back cover
        ├── background.png       # Hero section background
        ├── pages.png            # Book page-edge texture
        ├── section2.png         # Reading-book section background
        ├── footerbackground.jpg # Footer background
        └── footer.PNG           # Footer portrait image
```

## 🚀 Getting Started

No build tools required — it's plain HTML/CSS.

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Open `index.html` directly in your browser, **or** serve it locally (recommended):
   ```bash
   npx serve .
   # or
   python3 -m http.server
   ```

## 🌐 Deployment

Deploying with **GitHub Pages**:

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Branch**, select `main` and `/ (root)`, then **Save**.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` 🎉

## 👤 Author

**Mohammad Takali** – Frontend Developer

- 🐙 [GitHub](https://github.com/mohammadtakali)
- 💼 [LinkedIn](https://www.linkedin.com/in/mohammad-takali-b9b820434)
- 📸 [Instagram](https://www.instagram.com/mohammadtakali.dev)
