# Coding Guidelines

## General

This project should remain simple, portable and easy to maintain.

Prefer static HTML/CSS/JavaScript unless a framework is explicitly approved.

## Website

Recommended structure:

```text
website/
├── index.html
├── about.html
├── courses.html
├── projects.html
├── portfolio.html
├── contact.html
├── css/style.css
├── js/main.js
└── assets/
```

## HTML

- Use semantic HTML5.
- Use accessible headings.
- Keep content readable without JavaScript.
- Add meta description and title to every page.

## CSS

- Use one main CSS file initially.
- Use CSS variables for colors.
- Make layout responsive.
- Keep the design professional and clean.

## JavaScript

- Use vanilla JavaScript only unless needed.
- Keep scripts minimal.
- Do not add unnecessary dependencies.

## Content

- Source content should be kept in Markdown under `/docs` where possible.
- Website pages can reuse and adapt that content.

## Quality Criteria

- Mobile-friendly
- Fast loading
- Clear navigation
- Professional tone
- No placeholder claims that sound fake
- No unsupported certifications or titles
