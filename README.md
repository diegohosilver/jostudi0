# JO Studio — Portfolio Website

## Stack

- Single-file HTML (`index.html`) — no build step, no dependencies to install
- [Tailwind CSS](https://tailwindcss.com/) via CDN (with Forms + Container Queries plugins)
- [GSAP 3.12](https://gsap.com/) — ScrollTrigger, ScrollToPlugin
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) + [Aileron](https://www.cdnfonts.com/aileron.font) fonts
- Google Material Symbols icons

## Structure

```
jostudi0/
├── index.html              # Entire site
├── logo-black.png          # Logo (dark version, used in nav)
├── logo-white.png          # Logo (light version, used in hero)
├── images/                 # Hero, about photo, portfolio cover, and gallery images
├── PROYECTO PERSONAL/      # Gallery images — Fisherman project
├── ENDAVANT/               # Gallery images — Endavant project
└── ICO BATISTA/            # Gallery images — Ico Batista project
```

## Sections

| Section | ID |
|---|---|
| Hero | `#inicio` |
| About Me | `#quien-soy` |
| Selected Works | `#trabajos` |
| Services | `#servicios` |
| Contact | `#contacto` |

## Features

- **Bilingual** — ES/EN toggle in the navbar swaps all copy including placeholders and select options
- **Expandable portfolio galleries** — each card reveals an inline masonry grid; lightbox on image click
- **Scrolling services ticker** — infinite CSS marquee in the contact section
- **Contact form** — opens the default mail client via `mailto:micaelajoho@gmail.com` with form data pre-filled
- **GSAP animations** — hero entrance, scroll reveals, parallax, navbar shrink, scroll-spy active nav

## Running locally

No server required — just open `index.html` in a browser.

> Note: some browsers block local file access for images. If images don't load, serve the folder with any static server:
> ```
> npx serve .
> ```
