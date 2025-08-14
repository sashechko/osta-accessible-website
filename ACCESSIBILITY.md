# Accessibility Report – Osta Accessible Website

This document summarizes the accessibility goals, testing methods, and WCAG compliance status of the static website for the **NGO "Innovation Practice Center Osta" (IPC Osta, Latvia)**. The project is developed as a public portfolio example and follows both international and national accessibility standards.

---

## Accessibility Goals

- Comply with **WCAG 2.1 Level AA** requirements  
- Make the website usable with keyboard and screen readers  
- Structure content using semantic HTML  
- Ensure accessibility across various devices and screen sizes  
- Identify and eliminate common accessibility barriers such as:
  - Low contrast
  - Missing or incorrect alt text
  - Improper heading hierarchy
  - Inaccessible form elements
  - Unclear focus order or lack of focus indicators

---

## Testing Methods

### Manual Testing

Manual accessibility testing has been conducted using the following tools and methods:

- Keyboard-only navigation (Tab, Shift+Tab, Enter, Escape)
- Screen reader testing (e.g. NVDA on Windows or VoiceOver on macOS)
- [WAVE Evaluation Tool](https://wave.webaim.org/)
- [axe DevTools](https://www.deque.com/axe/devtools/)
- [VARAM Pieklustamības izvērtēšanas rīks (Latvian Government Tool)](https://pieklustamiba.varam.gov.lv/)
- Visual checks for:
  - Focus visibility and logical focus order
  - Color contrast of text, icons, buttons, and links
  - Correct use of headings, lists, tables, and landmarks

Manual test notes and observations will be documented in: `/accessibility tests/manual/`

---

### Automated Testing

Automated accessibility tests are planned or in progress using the following tools:

- axe-core
- Lighthouse (Chrome DevTools)
-  Playwright accessibility test scripts (JavaScript)
- (Planned) Java-based automation using Selenium WebDriver for accessibility regression checks
- (Planned) Python-based automation using pytest and pa11y or axe-core Python bindings for batch testing and report generation

Test code and report outputs will be stored in: `/accessibility tests/automated/`


## Status

Accessibility testing is currently in progress. Reports and fixes are applied iteratively throughout development. This document will be updated as the website moves toward public release.


---

## Author

Aleksandra Pavlovska  
Junior Accessibility & QA Tester  
Social Worker (MSW), Latvia

