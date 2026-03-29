# Osta Accessible Website

**Live:** [https://sashechko.github.io/osta-accessible-website/](https://sashechko.github.io/osta-accessible-website/)

This is a static website for the **NGO "Inovaciju prakses centrs Osta" (IPC Osta, Latvia)**, designed and built with a focus on accessibility and inclusiveness. The goal is to meet **WCAG 2.1 AA** standards and demonstrate best practices in accessible web design.

---

## Project Goals
- Inform visitors and clients about IPC Osta's mission, services, and contact details
- Ensure content is perceivable, operable, understandable, and robust
- Provide a clear example of how to create and test an accessible website

---

## Tech Stack
- HTML5 (semantic markup, ARIA attributes)
- CSS3 (reset + custom styles, responsive design, print stylesheet)
- Minimal JavaScript (responsive hamburger menu only)
- Formspree for contact form handling
- Manual testing tools: WAVE, axe DevTools, keyboard-only nav, screen reader (in progress)
- Automated testing tools: axe-core, Lighthouse (in progress)

---

## Structure

```
/osta-accessible-website
├── index.html
├── aktivitates.html
├── kontakti.html
├── par-mums.html
├── piekļūstamības-paziņojums.html
├── 404.html
├── sitemap.xml
├── README.md
├── ACCESSIBILITY.md
├── accessibility tests/
│   ├── manual/
│   └── automated/
├── blog/
│   └── index.html
├── css/
│   ├── index.css
│   └── reset.css
├── prakses/
│   ├── dzīvibas-koks.html
│   ├── family-conf.html
│   ├── kids-skills.html
│   ├── pieejas-un-prakses.html
│   └── woww.html
└── resources/
    └── images/
```

---

## Accessibility Features
- Skip link on every page
- Semantic HTML5 landmarks and heading hierarchy
- ARIA labels and attributes throughout
- Keyboard-navigable hamburger menu (details/summary, no-JS fallback)
- Focus indicators on all interactive elements
- Responsive design with mobile-first approach
- Reduced motion support
- Forced colors / high contrast mode support
- Print stylesheet
- Lazy loading for below-fold images
- Inline SVG icons (no external icon CDN dependencies)

---

## Deployment
The site is published via GitHub Pages.

---

## Author
**Aleksandra Pavlovska** -- Junior Accessibility & QA Tester, Social Worker (MSW), Latvia
