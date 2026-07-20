<div align="center">

# ⚡ PULSE — Sound Redefined 🎧

### An ultra-luxury, Apple-inspired scrollytelling experience for PULSE Wireless Headphones

*Cinematic frame-by-frame video scrubbing · Liquid-smooth GSAP choreography · Absolute dark-mode elegance*

<br/>

[![License](https://img.shields.io/badge/License-All_Rights_Reserved-0d0d0d?style=for-the-badge&labelColor=1a1a1a)](https://github.com/Egemen-Al/pulse-landing#-legal--copyright)
[![Repo Size](https://img.shields.io/github/repo-size/Egemen-Al/pulse-landing?style=for-the-badge&color=0d0d0d&labelColor=1a1a1a)](https://github.com/Egemen-Al/pulse-landing)
[![Stars](https://img.shields.io/github/stars/Egemen-Al/pulse-landing?style=for-the-badge&color=0d0d0d&labelColor=1a1a1a)](https://github.com/Egemen-Al/pulse-landing/stargazers)
[![Forks](https://img.shields.io/github/forks/Egemen-Al/pulse-landing?style=for-the-badge&color=0d0d0d&labelColor=1a1a1a)](https://github.com/Egemen-Al/pulse-landing/network/members)

<br/>

**[ ✦ View Live Experience ✦ ](https://egemen-al.github.io/pulse-landing/)**

</div>

---

## 🌌 Overview

**PULSE** is a single-page, scroll-driven product film rendered in the browser. As the visitor scrolls, a premium headphone disassembles frame-by-frame in perfect sync with the scrollbar — wrapped in translucent glassmorphism, neon-white typography ignition, magnetic section snapping, and a custom blend-mode cursor system. Every pixel engineered for the feel of a flagship keynote.

---

## 🧬 Key Features Matrix

| Capability | Engineering Detail |
|:---|:---|
| 🎞️ **Smooth GSAP Scrubbing** | Blob-preloaded video buffer + `ScrollTrigger` with `scrub: 1.2` luxury damping — scroll velocity dictates fluid, lag-free frame playback |
| 🛡️ **Watermark Hiding Engineering** | Center-origin `scale(1.18) translate(2%, 2%)` inside an `overflow: hidden` fixed stage mathematically pushes the corner outside the viewport on every aspect ratio |
| 🖱️ **Absolute Cursor Max Z-Index** | Custom magnetic dot + lagging ring at `z-index: 999999` — permanently visible above modals, loaders, and every stacking context |
| 🧊 **Translucent Glassmorphism UI** | `backdrop-filter: blur(22px) saturate(140%)` cards, translucent sticky nav, and a glass checkout configurator |
| 📱 **Responsive Video Architecture** | `object-fit: cover` + `100dvh` stage with portrait-ratio override — zero horizontal scroll from 4K desktop to mobile |
| 🧲 **Magnetic Section Snapping** | Directional `ScrollTrigger` snap locks the scroll to each perfect disassembly frame |
| 🔥 **Scroll-Linked Text Ignition** | Neon-white `text-shadow` glow bound strictly to scroll coordinates — pause the scroll, pause the light |
| 📟 **Futuristic Progress Dashboard** | Illuminating vertical milestone tracker (`01 // OVERVIEW → 04 // ACQUIRE`) with click-to-glide navigation |
| 🛒 **Functional Checkout Module** | Color configurator, live input masking, validation, and an animated pre-order confirmation modal |

---

## 🛠️ Tech Stack

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP_+_ScrollTrigger-88CE02?style=for-the-badge&logo=greensock&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

</div>

---

## 🚀 Quick Installation / Local Setup

```bash
# 1 · Clone the repository
git clone https://github.com/Egemen-Al/pulse-landing.git

# 2 · Enter the project
cd pulse-landing

# 3 · Serve locally (any static server works)
npx serve .

# 4 · Open in your browser
# → http://localhost:3000
```

> **Note** — serve over `http://`, not `file://`: the video is fetched as a Blob for instant-seek scrubbing, which requires a server context.

---

## 🌐 Deployment Guide — GitHub Pages

- **Push** the production files (`index.html`, `video.mp4`) to the `main` branch
- Open **Settings → Pages** in the repository
- Under **Build and deployment**, set **Source** to `Deploy from a branch`
- Select branch **`main`**, folder **`/ (root)`**, and click **Save**
- Wait ~1–2 minutes for the Pages build to go green
- The experience is live at **`https://egemen-al.github.io/pulse-landing/`** — zero build step, zero dependencies, pure static delivery

---

## ⚖️ Legal & Copyright

<div align="center">

**© 2026 · All Rights Reserved**

All production concepts, visual direction, interaction design, and design patents associated with the
**PULSE — Sound Redefined** experience are the sole and exclusive intellectual property of

### ✦ [Bülent Egemen AL](https://github.com/Egemen-Al) ✦

*Unauthorized reproduction, redistribution, or commercial use of any part of this work is strictly prohibited.*

<br/>

*Engineered with obsession. Designed for silence.*

</div>
