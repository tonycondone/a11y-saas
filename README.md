<!-- ┌─────────────────────────────────────────────────────────────┐
     │  A11Y-SAAS  –  Accessibility-First Task & Calendar Suite   │
     └─────────────────────────────────────────────────────────────┘ -->
<div align="center">

<!-- Animated SVG Logo -->
<svg width="320" height="80" viewBox="0 0 320 80" xmlns="http://www.w3.org/2000/svg" aria-labelledby="logoTitle">
  <title id="logoTitle">A11y SaaS Logo</title>
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" font-size="36" fill="#ff0d0d" font-family="Arial Black">
    <tspan class="a11y">A11y</tspan><tspan dx="8" class="saas">SaaS</tspan>
  </text>
  <style>
    .a11y { animation: popIn .8s ease-out forwards; }
    .saas { animation: popIn .8s .2s ease-out forwards; transform-origin: center; }
    @keyframes popIn {
      0%   { transform: scale(.3); opacity: 0; }
      100% { transform: scale(1); opacity: 1; }
    }
  </style>
</svg>

<!-- Badges -->
[![CI](https://github.com/tonycondone/a11y-saas/actions/workflows/ci.yml/badge.svg)](https://github.com/tonycondone/a11y-saas/actions)
[![Vercel](https://img.shields.io/github/deployments/tonycondone/a11y-saas/production?label=vercel&logo=vercel)](https://a11y-saas.vercel.app)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![WCAG 2.2 AA](https://img.shields.io/badge/WCAG-2.2%20AA-blueviolet)](https://www.w3.org/WAI/WCAG22/quickref)

**🚀 A fully-accessible task & calendar app built with React, TypeScript and screen-reader love.**

</div>

---

## 🌟 Live Demo
> https://a11y-saas.vercel.app

Keyboard-first, screen-reader friendly, motion-respectful.  
Try **Tab**, **Shift+Tab**, **Enter**, or activate voice input with **⌘+K** (macOS) / **Ctrl+K** (Windows).

---

## 📦 Quick Start

```bash
# 1. Clone
git clone https://github.com/tonycondone/a11y-saas.git
cd a11y-saas

# 2. Install
npm ci

# 3. Dev server (localhost:5173)
npm run dev

# 4. Run accessibility tests
npm run test:axe