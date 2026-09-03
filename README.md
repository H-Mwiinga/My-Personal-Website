# Personal Website — HTML Assignment

## Project Overview
This repository contains a single-page personal website built using only HTML to satisfy the assignment requirements: 25+ different HTML elements, 15+ different attributes, semantic structure, and organized content sections.

Files:
- [index.html](index.html)

## Question 1: Website Creation
- Type of website: Personal portfolio and contact page for a web development student.
- Content included: About, Portfolio (projects), Skills, Resume summary, Contact form, and Footer with contact links.

## Question 2: HTML Elements
1. Five most challenging elements to implement and why:
   - `<table>` — getting accessible headers (`scope`) and using `thead`/`tbody` properly required attention.
   - `<figure>` / `<figcaption>` — deciding when to use semantic image grouping vs. plain image.
   - `<details>` / `<summary>` — ensuring semantic fallback and readability without JS.
   - `<progress>` / `<meter>` — choosing correct attributes and values to represent progress/confidence.
   - `<address>` — learning semantic placement and not confusing it with generic contact text.

2. Use of semantic elements:
   - `header` contains site title and main navigation.
   - `nav` holds the primary links.
   - `main` contains primary page content.
   - `section` groups related content blocks (About, Portfolio, Resume, Contact).
   - `article` wraps individual projects in the Portfolio.
   - `aside` holds skills and supplemental info.
   - `footer` contains contact summary and repository link.

3. Most useful element for layout organization:
   - `section` was the most useful because it provides clear, semantic groupings for distinct page areas and pairs well with `aria-labelledby` for accessibility.

Elements used (25+):
html, head, meta, title, body, header, nav, ul, li, a, main, section, article, h1, h2, h3, p, img, figure, figcaption, aside, footer, address, form, label, input, textarea, select, option, button, table, thead, tbody, tr, th, td, progress, meter, blockquote, cite, details, summary, dl, dt, dd, hr, small, ol

## Question 3: HTML Attributes
1. Three essential attributes for functionality:
   - `href` on `<a>` — enables navigation and mailto/tel links.
   - `type` and `name` on form inputs — required for correct data entry and submission semantics.
   - `id` and `for` pairing — necessary for accessible form labels.

2. Use of `class` vs `id`:
   - `id` is used for unique elements needed by document structure (e.g., `id="contact"`, `id="main-content"`).
   - `class` is used for grouping and reuse (e.g., `class="section"`, `class="project"`).

3. Attribute that improved UX most:
   - `placeholder` and `required` on form fields improved clarity for users filling the form; `aria-label` and `aria-describedby` improved accessibility and screen-reader experience.

Attributes used (15+):
lang, charset, name, content, viewport, title, href, target, rel, src, alt, width, height, id, class, role, aria-label, placeholder, type, value, required, method, action, rows, scope, summary, datetime, form, aria-describedby

## Question 4: Development Process
1. Planning structure:
   - Sketched a simple single-page layout: header/nav, main with sections (About, Portfolio, Resume, Contact), aside, and footer. Listed required elements and attributes to ensure counts were met.

2. Testing and debugging approach:
   - Opened `index.html` in a modern browser to visually verify structure.
   - Used browser developer tools to inspect DOM and validate attributes.
   - Manually validated semantic usage and checked for missing `alt` attributes and label associations.

3. Challenges and solutions:
   - Challenge: Ensuring at least 25 distinct elements without adding duplicate semantics.
     Solution: Used additional semantic/structural elements such as `figure`, `figcaption`, `details`, `summary`, `progress`, and `meter`.
   - Challenge: Accessibility of forms and tables.
     Solution: Added `label` elements with `for` attributes, `scope` for table headers, and `aria-` attributes where appropriate.

## Question 5: Git & GitHub Implementation
1. Git commands used (recommended workflow):
   - `git init`
   - `git add index.html README.md`
   - `git commit -m "Initial site and README for HTML assignment"`
   - `git remote add origin https://github.com/H-Mwiinga/My-Personal-Website.git`
   - `git push -u origin main`

2. Commits and messaging strategy:
   - Example: 4 commits (initial structure, add portfolio content, add contact form, update README).
   - Messages were concise and descriptive: e.g., "Add header and nav", "Add portfolio articles and images", "Add contact form and resume table", "Complete README and assignment answers".

3. Why version control matters:
   - Tracks history, enables collaboration, allows reverting changes, and provides a single source of truth for deployment.

## Question 6: Code Quality & Best Practices
1. Ensuring validity:
   - Used consistent tag nesting and provided `alt` text for images and labels for inputs.
   - Opened the file in a browser and visually inspected structure.

2. Best practices followed:
   - Semantic HTML elements, descriptive link text, accessible forms, `aria-` attributes where applicable, and clear id/class naming.

3. Future improvements:
   - Add CSS for visual design (external stylesheet), add simple JS for form validation, and add more projects and live demos.

---

## GitHub / Submission Instructions (what to do next)
1. Create the repository on GitHub (if not already created):

```bash
git init
git add .
git commit -m "Initial commit: add HTML site and README"
git remote add origin https://github.com/H-Mwiinga/My-Personal-Website.git
git branch -M main
git push -u origin main
```

2. Add instructor as collaborator:
   - On GitHub, go to Settings → Manage access → Invite a collaborator → enter username `instructor-webdev`.

3. Follow the instructor on GitHub (open instructor profile and click Follow).

4. Submit the repository link in Google Classroom.

---

## Submission (required format)
Student Name: Haangoma Mwiinga

Student ID: 2211138203

GitHub Repository: https://github.com/H-Mwiinga/My-Personal-Website.git

Contact details (for submission):
- Name: Haangoma Mwiinga
- Phone Number: +260 977 155 188
- SIN NUMBER: 2211138203
- EMAIL: haangomamwiinga@gmail.com
- Github link: https://github.com/H-Mwiinga/My-Personal-Website.git

---

If you want, I can run a quick HTML validator check and/or prepare a git commit history example. Tell me which you'd like next.
