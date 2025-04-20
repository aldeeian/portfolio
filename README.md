# MD Saif Aldeen — Personal Portfolio

A fully animated personal portfolio website built with **pure HTML, CSS, and JavaScript** — no frameworks, no dependencies, single file.

## Features

| Feature | Implementation |
|---|---|
| Loading screen | CSS keyframe fade-out on `window.load` |
| Custom cursor | Glowing dot + trailing ring via `mousemove` |
| Particle network | Canvas API with connecting lines to mouse |
| Shimmer hero name | CSS `background-size: 200%` + `@keyframes shimmer` |
| 3D floating card | CSS `rotateX/Y` animation on `perspective` wrapper |
| Pulsing avatar | 3 rings with staggered `animation-delay` |
| Scroll reveal | `IntersectionObserver` with fade-up/slide variants |
| Skill bars | Width animates only when scrolled into view |
| Marquee | Infinite CSS `translateX` loop, pauses on hover |
| Project cards | Top-border gradient sweep on `:hover` |
| Contact ripples | Expanding `scale` rings with staggered delay |

## Usage

```bash
# Clone the repo
git clone https://github.com/aldeeian/portfolio.git

# Open directly in browser — no build step needed
open index.html
```

## Tech

- HTML5 / CSS3 / Vanilla JS
- Zero external libraries
- Fully responsive (mobile-first breakpoints at 768px)
