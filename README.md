# Visvaa Personal Portfolio

A five-page portfolio built with HTML5, CSS3 and vanilla JavaScript. No frameworks.

## Structure
```
personal-portfolio/
  index.html  about.html  projects.html  skills.html  contact.html
  css/style.css
  js/script.js
  README.md
```

## Run in VS Code
1. Open the folder in VS Code (File > Open Folder).
2. Install the Live Server extension.
3. Right-click `index.html` and choose "Open with Live Server". Or just double-click `index.html`.

## Edit your content
- Name, text, education: edit the HTML files. Header and footer are repeated in every page, so change them in all five.
- Project links: replace the "add your URL here" lines in `projects.html` and `index.html` with real `<a>` links.
- Email: change the sample address in `contact.html`.
- Colors and spacing: edit the variables at the top of `css/style.css`.

## Contact form limitation
The form is validated in the browser only. It does NOT send or store messages. To deliver real messages you need a backend or a form service (for example Formspree or Netlify Forms).

## Test keyboard accessibility
- Press Tab from the top: the first stop is "Skip to main content". Press Enter to jump to the content.
- Tab through links, buttons and form fields. A yellow focus ring must always be visible.
- Narrow the window below 768px: Tab to "Menu", press Enter or Space to open it, press Escape to close it.
- On the contact page, submit an empty form: errors appear and focus moves to the first invalid field.

## Validate and run Lighthouse
- HTML: paste each page at https://validator.w3.org/#validate_by_input, or use the "W3C Web Validator" extension.
- Lighthouse: open the page in Chrome, press F12, open the Lighthouse tab, tick Accessibility and SEO, then Analyze.
- Fix anything reported. A score is only valid after you run it; none is claimed here.

## Requirement checklist
| Requirement | Where |
|---|---|
| Semantic header, nav, main, section, article, aside, footer | all pages |
| figure and figcaption | `index.html` |
| address, time, form, label | `contact.html`, `about.html`, footer |
| lang, one h1 per page, skip link | every page |
| Visible focus, reduced motion, contrast | `css/style.css` |
| aria-expanded menu, validation, aria-live status | `js/script.js`, `contact.html` |
| Unique title and meta description | every page `<head>` |
| Responsive, mobile-first, Grid and Flexbox | `css/style.css` |
