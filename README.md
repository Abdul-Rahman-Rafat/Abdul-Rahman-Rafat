<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=header&text=Abdul-Rahman%20Rafat&fontSize=42&fontColor=ffffff&fontAlign=50&fontAlignY=40&color=gradient&customColorList=2,3,30" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Space+Mono&size=18&pause=1000&color=00C4AE&center=true&vCenter=true&width=600&lines=Frontend+Developer+%7C+React+%26+JavaScript;ITI+Graduate+%7C+160%2B+Training+Hours;Cairo%2C+Egypt+%F0%9F%87%AA%F0%9F%87%AC" alt="Typing SVG" />

<br/><br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-00C4AE?style=for-the-badge&logo=vercel&logoColor=white)](https://your-portfolio-link.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdul-rahman-rafat-b571a4361)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Abdul-Rahman-Rafat)

</div>

---

## About This Portfolio

A personal portfolio built with React, no UI library. Animated particle canvas background, custom cursor, orbiting skill icons, bilingual support (EN/AR with RTL layout), dark/light mode, and a working contact form via EmailJS.

---

## Screenshots

> Add your screenshots here after deployment

```
screenshots/
├── desktop-dark.png
├── desktop-light.png
└── mobile.png
```

---

## Features

**Design**
- Animated particle network background on canvas
- Custom cursor with ring follower
- Smooth scroll with IntersectionObserver-based active section tracking
- Rocket navigator for jumping between sections

**Bilingual**
- English and Arabic with one button toggle
- Full RTL layout when Arabic is selected
- Custom Alexandria font loaded locally for Arabic

**Theme**
- Dark and light mode toggle
- CSS variables for all colors, no hardcoded values

**Sections**
- Hero with orbiting skill icons (CSS + rAF animation, no library)
- About with stats
- Skills grid with scroll-triggered entrance animation
- Projects grid with live demo and GitHub links
- Contact with EmailJS form that slides in from the side

---

## Tech Stack

| | |
|---|---|
| Framework | React 19 |
| Routing | React Router DOM v7 |
| Styling | Pure CSS with custom properties |
| Build | Vite 8 |
| Icons | RemixIcon, Devicon |
| Email | EmailJS |
| Animation | Canvas API, requestAnimationFrame |
| Fonts | Cormorant Garamond, Outfit, Space Mono, Alexandria |

---

## Project Structure

```
src/
├── assets/             # Images, fonts
├── components/
│   ├── BackgroundCanvas.jsx   # Particle network
│   ├── CustomCursor.jsx       # Cursor + ring
│   ├── Icons.jsx              # RemixIcon wrappers
│   ├── Navbar.jsx
│   └── RocketNavigator.jsx    # Section jumper
│
├── data/
│   ├── personal.js     # Social links, contact info, CV link
│   ├── projects.js     # All project data
│   ├── skills.js       # Skills grid + orbit skills
│   └── translations.js # EN/AR strings
│
├── sections/
│   ├── Hero.jsx        # Orbit animation lives here
│   ├── About.jsx
│   ├── Skills.jsx
│   ├── Projects/
│   │   ├── Projects.jsx
│   │   └── ProjectCard.jsx
│   ├── Contact.jsx     # EmailJS form
│   └── Footer.jsx
│
└── App.jsx             # Theme, language, scroll, IntersectionObserver
```

---

## Getting Started

```bash
git clone https://github.com/Abdul-Rahman-Rafat/MyNewPortfolio.git
cd MyNewPortfolio
npm install
npm run dev
```

---

## Customization

All content lives in `src/data/`. To update the portfolio:

- **Projects** → `src/data/projects.js`
- **Skills** → `src/data/skills.js`
- **Contact info and social links** → `src/data/personal.js`
- **All text (EN + AR)** → `src/data/translations.js`
- **CV link** → `src/data/personal.js` → `cvLink`

To update the EmailJS form, replace the service ID, template ID, and public key in `src/sections/Contact.jsx`.

---

## Projects Showcased

| # | Project | Stack | Link |
|---|---------|-------|------|
| 01 | Tavola Restaurant | React, Redux, Tailwind | [Live](https://tavola-restaurant.vercel.app/) |
| 02 | WindsMeet Travel | HTML, CSS, JS, Bootstrap | [Live](https://windsmeet.vercel.app/) |
| 03 | Grino eCommerce | HTML, Pure CSS, JS | [Live](https://grino-e-commerce.vercel.app/) |
| 04 | E-Commerce Platform | HTML, CSS, JS | [Live](https://firstecommerce-tau.vercel.app/) |
| 05 | LearnHub | Django, Python | [GitHub](https://github.com/Abdul-Rahman-Rafat/Learn-Hub-Django-.git) |

---

## Contact

**Abdul Rahman Rafat**
Frontend Developer | Cairo, Egypt

- Email: abdorafat489@gmail.com
- Phone: +20 111 354 5007
- LinkedIn: [abdul-rahman-rafat-b571a4361](https://linkedin.com/in/abdul-rahman-rafat-b571a4361)

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=80&section=footer&color=gradient&customColorList=2,3,30" />

</div>
