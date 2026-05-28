[README.md](https://github.com/user-attachments/files/28332385/README.md)
# Nexus AI Agency Landing Page

A stunning, futuristic single-page landing website for an AI solutions agency. Built with pure HTML, CSS, and JavaScript — no frameworks required.

![Preview](https://img.shields.io/badge/status-live-success)
![Tech](https://img.shields.io/badge/tech-vanilla%20web-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

### Visual Design
- **Futuristic Dark Theme** — Deep space aesthetic with cyan/purple accents
- **Glassmorphism** — Frosted glass effects with backdrop blur
- **Animated Gradients** — Living, breathing background effects
- **Floating Particles** — Subtle ambient particle system
- **Glow Effects** — Neon-style hover states and borders
- **Responsive Layout** — Works beautifully on all devices

### Interactions & Animations
- 🎭 **Scroll Reveals** — Elements fade in smoothly as you scroll
- 🔢 **Counter Animations** — Stats animate when entering viewport
- ✨ **Hover Effects** — Cards lift, glow, and transform
- 📜 **Smooth Scrolling** — Fluid navigation between sections
- 🌊 **Gradient Morphing** — Animated background shifts

### Sections
1. **Navigation** — Fixed glassmorphic header with scroll effects
2. **Hero** — Bold headline with gradient text and dual CTAs
3. **Services** — 6 glassmorphic service cards with icon accents
4. **Process** — 4-step workflow timeline
5. **Stats** — Animated counters for social proof
6. **Testimonials** — Client quotes with avatars
7. **CTA** — Final call-to-action banner
8. **Footer** — Links and social media

## 🚀 Quick Start

### Option 1: Direct Open
Simply open `index.html` in any modern browser.

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

### Option 2: Local Server (Recommended)

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## 🛠️ Customization

### Changing Colors
Edit the CSS variables in the `:root` selector:

```css
:root {
  --accent-cyan: #00f0ff;    /* Primary glow color */
  --accent-purple: #a855f7;  /* Secondary accent */
  --accent-pink: #ec4899;    /* Tertiary accent */
  --bg-primary: #0a0a0f;     /* Main background */
}
```

### Changing Content

| Section | Location |
|---------|----------|
| Hero text | `<section class="hero">` |
| Services | `<section id="services">` |
| Process steps | `<div class="process-section">` |
| Stats | `<div class="stats-section">` |
| Testimonials | `<section id="testimonials">` |
| Footer links | `<footer>` |

### Changing Fonts

The page uses Google Fonts (Orbitron + Exo 2). To change:

1. Update the Google Fonts link in `<head>`
2. Update font-family references in CSS:
   - Headings: `font-family: 'Orbitron', sans-serif;`
   - Body: `font-family: 'Exo 2', sans-serif;`

## 📁 File Structure

```
ai-agency-landing/
├── index.html          # Main landing page (all-in-one)
├── SPEC.md            # Design specification
└── README.md          # This file
```

## 🎨 Design System

### Typography
- **Primary Font:** Orbitron (futuristic display)
- **Body Font:** Exo 2 (clean, modern sans-serif)
- **Scale:** 
  - Hero H1: `clamp(2.5rem, 8vw, 5rem)`
  - Section titles: `clamp(2rem, 5vw, 3rem)`
  - Body: `1rem`

### Color Palette
| Token | Value | Usage |
|-------|-------|-------|
| `--bg-primary` | `#0a0a0f` | Page background |
| `--accent-cyan` | `#00f0ff` | Primary glow, buttons |
| `--accent-purple` | `#a855f7` | Secondary accents |
| `--text-primary` | `#ffffff` | Headings |
| `--text-secondary` | `#94a3b8` | Body text |

### Effects
- **Glassmorphism:** `backdrop-filter: blur(20px)` + semi-transparent bg
- **Glow:** `box-shadow: 0 0 30px rgba(0, 240, 255, 0.4)`
- **Gradients:** Linear gradients from cyan → purple → pink

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ 90+ |
| Firefox | ✅ 88+ |
| Safari | ✅ 14+ |
| Edge | ✅ 90+ |

> Note: Glassmorphism effects require modern browsers with `backdrop-filter` support.

## 📱 Responsive Breakpoints

- **Desktop:** 1200px+ (full layout)
- **Tablet:** 768px - 1199px (adjusted spacing)
- **Mobile:** < 768px (stacked layout, mobile nav)

## 📝 License

MIT License — feel free to use for personal or commercial projects.

## 🤝 Credits

- Fonts: [Google Fonts](https://fonts.google.com/)
- Icons: Unicode symbols (no external icon library needed)
- Design: Inspired by modern cyberpunk/neon aesthetics

---

**Ready to deploy?** Upload `index.html` to any static hosting:
- GitHub Pages
- Vercel
- Netlify
- Cloudflare Pages
- AWS S3

Built with ❤️ for the future of AI.
