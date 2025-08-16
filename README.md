# Project Name — Submission Package

**URL:** https://your-site.example/  
**Video demo:** https://youtu.be/your-demo

## Introduction
This is a ready-to-submit package demonstrating a front-end website that meets the rubric: W3C-compliant, responsive, and thoughtfully designed. Replace placeholder links and screenshots with your live site and real validator captures.

## Key Features
- Clean semantic HTML and CSS architecture
- Responsive layouts (mobile / tablet / desktop)
- Accessibility-first interactions (focus rings, landmarks, labels)
- Reusable UI components (cards, buttons, grid)

## Evidence & Compliance
- **W3C Validator:** screenshots in `evidence/w3c/` (replace with real validator screenshots)
- **Responsive:** screenshots in `evidence/responsive/` (replace with DevTools device captures)
- **Design:** see `design/styles.css` and `design/design-system.md`
- **Four additional parts:** listed below with code snippets and images

## Four “Additional Parts”
1. **Dark Mode / Theme Switcher** — CSS variables + `prefers-color-scheme` + localStorage.
2. **Form with Validation** — native HTML5 constraints with custom messages.
3. **Accessibility Enhancements** — skip link, ARIA labels, keyboard navigation.
4. **Basic SEO Setup** — meta tags, Open Graph, sitemap/robots.

See `code-snippets/` for working examples and `evidence/addons/` for placeholders.

## How to Run Locally
```bash
# If static site
npx serve .
# Or VS Code Live Server
```

## Technical Notes
- Meta viewport, CSS Grid/Flexbox, fluid typography (clamp), color system
- Performance tips: image lazy-loading, `srcset`, asset compression
- Lighthouse categories: Performance / Accessibility / Best Practices / SEO

## Folder Layout
```
submission/
├─ README.md
├─ link.txt
├─ design/
│  ├─ styles.css
│  └─ design-system.md
├─ evidence/
│  ├─ w3c/
│  │  ├─ home-html-ok.png
│  │  └─ styles-css-ok.png
│  ├─ responsive/
│  │  ├─ home-mobile.png
│  │  ├─ home-tablet.png
│  │  └─ home-desktop.png
│  └─ addons/
│     ├─ darkmode.png
│     └─ form-validation.png
└─ code-snippets/
   ├─ head-meta.html
   ├─ responsive.css
   └─ addon-darkmode.html
```
