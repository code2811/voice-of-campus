# Voice of Campus

An accessible, student-centered microsite for authentic campus stories.

## Project Structure
- `index.html` – Home page
- `about.html` – About/Access page
- `story/` – Story detail pages
- `sass/` – Sass partials and main.scss
- `css/` – Compiled CSS
- `assets/` – Media and transcripts

## Running Locally
1. Compile Sass (`sass sass/main.scss css/styles.css`)
2. Open `index.html` in your browser

## Accessibility
- WCAG 2.1 AA compliant
- Semantic HTML5
- Keyboard navigation
- Visible focus states
- Captions/transcripts for all media

## License
MIT
## Accessibility Checklist - WCAG 2.1 AA Compliance

### Semantic HTML
- [x] Proper heading hierarchy (h1-h6)
- [x] Semantic elements (`<header>`, `<main>`, `<article>`, `<section>`, `<nav>`, `<footer>`)
- [x] Descriptive alt text for images
- [x] Proper use of `<figure>` and `<figcaption>` for media

### Multimedia Accessibility
- [x] Full transcripts for audio content
- [x] Time-stamped transcript for navigation
- [x] `<track>` elements for video captions
- [x] Audio player controls are keyboard accessible

### Color & Contrast
- [x] Text color contrast meets 4.5:1 ratio (WCAG AA)
- [x] Interactive elements meet 3:1 ratio
- [x] Color is not the only means of conveying information

### Keyboard Navigation
- [x] All interactive elements are keyboard accessible
- [x] Visible focus indicators on all focusable elements
- [x] Logical tab order throughout pages

### Responsive Design
- [x] Mobile-friendly layout
- [x] Text is readable without horizontal scrolling
- [x] Touch targets are at least 44x44 pixels
- [x] Content reflows properly at different viewport sizes

### ARIA
- [x] ARIA labels added only where semantic HTML is insufficient
- [x] ARIA roles used appropriately
- [x] Form inputs have associated labels

### Screen Reader Support
- [x] Logical reading order
- [x] Descriptive link text (no "click here")
- [x] Form labels properly associated with inputs