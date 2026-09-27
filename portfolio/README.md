# Lekhana G - Personal Portfolio

A responsive, multi-page portfolio built with semantic HTML5 and CSS3. It uses no JavaScript, frameworks, or build tools, and can be opened locally in a browser.

## Pages

- `index.html` - Home
- `about.html` - Professional summary and education
- `skills.html` - Skills by category
- `projects.html` - Academic project showcase
- `certifications.html` - Certifications and team leadership
- `contact.html` - Contact details and front-end-only form

## Open locally

Open `index.html` in a web browser. All pages share `css/style.css` and use relative links, so no local server is required.

## Replace image placeholders

The profile and project visuals are CSS/HTML placeholders, not photographs or project screenshots. Add your own files to `images/` using these names when available:

- `profile.jpg`
- `project1.jpg`
- `project2.jpg`

In each corresponding HTML page, replace the placeholder `<div>` with an `<img>` element using the matching relative path and descriptive alt text. Keep image proportions appropriate to the circular profile frame or project preview area.

## Update portfolio details

Edit the relevant HTML page to update personal information, education, skills, project descriptions, certifications, and contact links. Replace the `#` project link targets in `projects.html` with verified project URLs when available. The contact form is a visual front-end only; connect a backend or form service before using it to receive messages.

## Accessibility and responsive behavior

Pages include a skip link, semantic landmarks, labeled form fields, visible keyboard focus, and reduced-motion support. The mobile navigation is controlled with a CSS checkbox and works without JavaScript.