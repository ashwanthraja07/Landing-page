# Techfest 2026 — Landing Page

> **Hack the Future.** India's most electrifying college tech festival.

A fully self-contained, single-file landing page built with **HTML + CSS + JS** — no build tools, no frameworks, no external assets beyond Google Fonts.

---

## 🔗 Live Demo

**[View Live → https://ashwanthraja07.github.io/Landing-page](https://ashwanthraja07.github.io/Landing-page)**

---

## ✨ Features

| Feature | Detail |
|---|---|
| **Theme** | Cyberpunk 2077-style glassmorphism — `#0d0d12` base, `#ff2e63` magenta + `#00e5ff` cyan neon accents |
| **Background** | Animated canvas neural-network: drifting particle nodes, connecting edges, dashed circuit traces |
| **Cursor effect** | Lerp-eased magnetic pull — nodes attract toward cursor, dual-ring aura glow follows with delay |
| **Sticky Navbar** | Scroll-triggered frosted-glass effect, mobile hamburger drawer |
| **Hero** | Glitch-text headline, HUD readout strip, animated SVG hex graphic |
| **Event Cards** | Asymmetric glassmorphism grid with 3-D tilt on hover |
| **Timeline** | Hex-node milestone steps with animated SVG connectors |
| **Stats** | IntersectionObserver-driven animated counters (Participants, Prize Pool, Events, Colleges) |
| **Speakers** | ID-card grid with verified badge styling |
| **Footer** | Brand col, nav links, sponsors, social icons, copyright |
| **Responsive** | Breakpoints at 375px, 768px, 1440px |
| **Accessibility** | Keyboard focus states, aria-label, prefers-reduced-motion respected |

---

## 🚀 Stack

- **HTML5** — semantic structure
- **Vanilla CSS** — CSS custom properties, backdrop-filter, clip-path, @keyframes
- **Vanilla JS** — IntersectionObserver, requestAnimationFrame, Canvas 2D API
- **Google Fonts** — Chakra Petch, Inter, JetBrains Mono

---

## 📂 File Structure

`
Landing-page/
├── index.html      ← entire site (self-contained, ~84 KB)
└── README.md
`

---

## 🛠️ Local Development

No build step needed — just open in a browser:

`ash
start index.html
# or serve with any static server
npx serve .
`

---

## 🎨 Design Tokens

`css
--bg-deep:  #0d0d12   /* near-black base       */
--mg:       #ff2e63   /* magenta neon accent    */
--cy:       #00e5ff   /* electric cyan accent   */
--vi:       #7c3aed   /* violet ambient glow    */
`

---

## 📸 Sections

1. Sticky Navbar — logo, links, Register CTA, mobile drawer
2. Hero — glitch headline, HUD readout strip, animated hex SVG, CTAs
3. Event Tracks — 7-card asymmetric grid
4. Timeline — 4-phase schedule with hex milestone nodes
5. Stats Band — animated counter strip
6. Speakers / Judges — ID-card grid
7. Footer — brand, links, sponsors, socials

---

## 📄 License

MIT — free to use, remix, and build on.

---

*Built with for Techfest 2026 — IIT Mumbai*
