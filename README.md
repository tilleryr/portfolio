# reneetillery.github.io

Personal portfolio site for Renee Tillery — operations executive, AI builder, and no-code developer.

**Live site:** [tilleryr.github.io](https://tilleryr.github.io)

---

## About

This site serves as a portfolio and professional introduction for recruiters, hiring managers, and potential consulting clients. It covers:

- **Builds** — AI tools and automation workflows built during the Leland AI Mastery Bootcamp and independently
- **Strategy & Governance** — policy documents, strategy frameworks, and course outputs from executive AI training programs
- **About** — professional background and what I'm looking for
- **Connect** — LinkedIn and contact information

---

## Structure

Single-page site built in vanilla HTML and CSS. No frameworks, no dependencies, no build step.

```
tilleryr.github.io/
├── index.html        # The entire site
├── README.md         # This file
└── assets/           # Add this folder when you have images
    └── renee.jpg     # Your headshot (swap in when ready)
```

---

## How to Update

### Add your headshot

1. Add your photo to an `assets/` folder in this repo
2. In `index.html`, find the comment that says `Replace the div below with:`
3. Replace the entire placeholder `<div class="photo-placeholder">...</div>` with:

```html
<img src="assets/renee.jpg" alt="Renee Tillery">
```

### Add your email address

Find `hello@reneetillery.com` in `index.html` and replace with your real address. It appears twice — once in the `href` and once as visible text.

### Link a completed project

Find the hex card for the project in the Builds section. Replace the placeholder `href`:

```html
<!-- Before -->
<a href="https://github.com/tilleryr" target="_blank" class="hex-card reveal">

<!-- After -->
<a href="https://github.com/tilleryr/your-repo-name" target="_blank" class="hex-card reveal">
```

### Add a new project card

Copy an existing hex card block and paste it into the grid. Update the title, description, and tag. Remove the `muted` class if the project is complete.

### Add a Strategy & Governance document

Upload the PDF to this repo or a separate repo. Then find the relevant doc tile in `index.html` and:
1. Wrap the `.doc-tile` in an `<a>` tag pointing to the file
2. Update the title, description, and badge text
3. Change `<span class="doc-badge">Coming Soon</span>` to `<span class="doc-badge">View Document</span>`

---

## Color Palette

| Role       | Hex       |
|------------|-----------|
| Navy       | `#112744` |
| Mid Navy   | `#3D6688` |
| Cream      | `#EDE0CC` |
| Light Cream| `#F5EEE2` |
| Text       | `#1C1C1C` |

---

## Fonts

- **Display / Headlines:** [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) — loaded via Google Fonts
- **Body / UI:** [Outfit](https://fonts.google.com/specimen/Outfit) — loaded via Google Fonts

---

## Deploying Changes

This site is hosted on GitHub Pages from the `main` branch. Any commit to `main` automatically updates the live site within a minute or two.

To update:
1. Edit `index.html` directly on GitHub (click the pencil icon), or
2. Clone the repo, make changes locally, and push to main

---

## Contact

- LinkedIn: [linkedin.com/in/tilleryr](https://www.linkedin.com/in/tilleryr/)
- GitHub: [github.com/tilleryr](https://github.com/tilleryr)

---

© 2026 Renee Tillery. All rights reserved.
