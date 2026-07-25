# Karan M. Mali — Portfolio Website

A modern, dark-themed, single-page portfolio website built with HTML, CSS, and vanilla JavaScript, showcasing skills, projects, work experience, and contact details.

## 🔗 Live Demo

_Add your deployed link here once hosted (e.g. Netlify, Vercel, GitHub Pages)._

## 📁 File

- `karan-mali-portfolio.html` — the complete single-file website (HTML + CSS + JS all included)

## ✨ Features

- Responsive, mobile-friendly layout (Bootstrap 5 grid)
- Animated typing effect in the hero section (rotates through role titles)
- Scroll-reveal animations for sections and cards
- Sticky navbar with active-section highlighting on scroll
- Animated skill progress bars
- Project cards with hover overlay for live/GitHub links
- Career timeline for work experience
- Contact form (front-end only, shows a "Message Sent" confirmation)
- Social links: GitHub, LinkedIn, X (Twitter), WhatsApp

## 🛠️ Built With

- HTML5 & CSS3 (custom properties / CSS variables for theming)
- Bootstrap 5.3.3 (layout & components)
- Bootstrap Icons 1.11.3
- Google Fonts — Inter & Space Grotesk
- Vanilla JavaScript (no framework/build step required)

## 🚀 Getting Started

No build tools or dependencies needed — it's a single static HTML file.

1. Download `karan-mali-portfolio.html`
2. Open it directly in any modern browser, **or**
3. Deploy it as-is to any static host:
   - **GitHub Pages** — push to a repo, enable Pages, point to this file (rename to `index.html`)
   - **Netlify / Vercel** — drag-and-drop deploy
   - Any web server — just upload the file

## ✏️ Customization

| Section     | What to update                                             |
|-------------|-------------------------------------------------------------|
| Hero        | Name, role list (`roles` array in the script), stats        |
| About       | Bio text, highlight cards                                   |
| Skills      | Skill cards & progress bar percentages (`data-w` attribute) |
| Projects    | Project cards — replace `#` in "Live" / "GitHub" links      |
| Experience  | Timeline entries (add more `.titem` blocks for older roles) |
| Contact     | Email, phone/WhatsApp, location, social links               |

### Adding project links

Each project card has two placeholder links in the `.overlay` div:

```html
<a href="#"><i class="bi bi-box-arrow-up-right"></i></a> <!-- live site -->
<a href="#"><i class="bi bi-github"></i></a>              <!-- repo -->
```

Replace the `#` with the actual live URL and GitHub repo URL for each project.

## 📇 Contact

- **Email:** karanmali490@gmail.com
- **Phone / WhatsApp:** +91 9766849858
- **LinkedIn:** [linkedin.com/in/karan-mali-2a8887318](https://www.linkedin.com/in/karan-mali-2a8887318/)
- **GitHub:** [github.com/karanmali490](https://github.com/karanmali490)
- **X (Twitter):** [x.com/Karanmali_490](https://x.com/Karanmali_490)

## 📄 License

© 2026 Karan M. Mali. All rights reserved.
