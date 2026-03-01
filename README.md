# 🧑‍💻 Shikhar Sharma — Developer Portfolio

A sleek, single-file personal portfolio website with a dark aesthetic, built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step — just open and go.

---

## ✨ Features

- **Hero Section** — Introduction with role badges and links to GitHub & LinkedIn
- **Projects Tracker** — Add, edit, delete, and filter projects by status (Ongoing / Completed / Future) with progress bars and GitHub links
- **GitHub Integration** — Enter any GitHub username to fetch live stats: public repos, followers, following, top languages, and an activity grid
- **LeetCode Stats** — Input your Easy / Medium / Hard solve counts and rank to render an animated ring chart and breakdown bars
- **Contact Section** — Save and display your email and LinkedIn URL
- **Persistent Storage** — All data (projects, LeetCode stats, GitHub username, contact info) is saved to `localStorage` and restored on page reload


---

## 🚀 Getting Started

No installation required.

1. Clone or download the repository
2. Open `portfolio.html` in any modern browser

```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
open portfolio.html
```

---

## 🛠️ Customisation

Since everything lives in one file, customisation is straightforward:

| What to change | Where to find it |
|---|---|
| Name, title, bio | `<div class="hero">` section in the HTML |
| Default projects | `let projects = [...]` array in the `<script>` block |
| Colour scheme | CSS variables in `:root { }` |
| Social links (GitHub / LinkedIn buttons) | `<div class="social-row">` in the hero section |

---

## 📦 Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, keyframe animations
- **Vanilla JavaScript** — DOM manipulation, `fetch` API, `localStorage`
- **GitHub REST API** — `https://api.github.com` for live profile stats
- **Google Fonts** — Syne & Space Mono (loaded via CDN)

---

## 📁 Project Structure

```
portfolio/
└── portfolio.html   # Entire site — HTML + CSS + JS in one file
```

---

---

> Built by [Shikhar Sharma](https://github.com/your-username)
