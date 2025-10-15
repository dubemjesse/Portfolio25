# Portfolio25

A modern, single-page portfolio showcasing projects, skills, and contact details. Built on the HTML5 UP "Dimension" template and customized with a unique JO monogram logo, additional project links, and styling.

## Features

- Responsive one-page layout with modal sections for smooth navigation.
- Custom inline SVG header monogram (JO), centered and scalable.
- Project highlights with buttons for Live Demo and GitHub Repository (e.g., CoinFlow).
- Lightweight stack: pure HTML/CSS/JS; no build step required.

## Tech Stack

- HTML5, CSS3, JavaScript
- Font Awesome icons
- jQuery and Responsive Tools (from HTML5 UP)

## Quick Start

Prerequisite: Python 3 (or any static web server).

Start a local server from the project root:

```bash
python -m http.server 8000
```

Open the site in your browser:

```text
http://localhost:8000/
```

## Project Structure

```text
.
├── index.html
├── assets/
│   ├── css/
│   │   ├── main.css
│   │   └── fontawesome-all.min.css
│   ├── js/
│   └── sass/
├── images/
│   ├── logo.svg
│   └── ...
└── LICENSE.txt
```

## Customization

- **Header Logo**
  - The monogram is an inline SVG in `index.html` within `#header .logo`.
  - Size is controlled via `#header .logo .mark` in `assets/css/main.css`.
- **Projects**
  - Update the "More Projects" section in `index.html`.
  - Add `Live Demo` and `GitHub Repo` buttons using standard anchor elements.
- **Content & Media**
  - Replace images in `images/` and update references in `index.html`.
  - Edit text sections (`Intro`, `About`, `Contact`) directly in `index.html`.

## Deployment

### GitHub Pages

1. Push this folder to a GitHub repository.
2. In Settings → Pages, choose "Deploy from a branch".
3. Select branch `main` and folder `/ (root)`.
4. Your site will be served at the GitHub Pages URL.

### Netlify (or similar)

- Drag-and-drop the project folder, or connect the repository and deploy.
- Publish directory: `/` (root).

## Notes

- Static site; no build tooling required.
- Consider compressing large images under `images/` to improve performance.

## License

- Template: HTML5 UP "Dimension" — CC BY 3.0. See `LICENSE.txt`.
- Custom content (text, images, logo) © respective owner.
