# Miguel Pinto — Personal Portfolio

A responsive, single-page personal portfolio for presenting Miguel Pinto's background, data analysis experience, and contact links to recruiters and potential collaborators.

The site is built with plain HTML, CSS, and JavaScript, so it does not require a framework, package manager, or build process.

## Features

- Responsive dark-themed portfolio layout
- Navigation links for the About, Experience, and Contact sections
- Professional experience and academic project highlights
- Links to GitHub, LinkedIn, Gmail, and Outlook
- Smooth scrolling between sections
- Footer year updated automatically with JavaScript
- Inter font loaded from Google Fonts

## Project structure

```text
.
├── index.html   # Portfolio content and page structure
├── style.css    # Theme, layout, responsive styles, and components
├── script.js    # Dynamic footer year
└── README.md    # Project documentation
```

## Run locally

Because this is a static website, the page can be opened directly by double-clicking `index.html`. For a more representative local web-server preview, use any static server, for example:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

## Customization

To adapt the portfolio for another person or role:

1. Update the name, tagline, biography, experience, and contact links in `index.html`.
2. Replace the social profile URLs and email address in the hero and contact sections.
3. Adjust colors, spacing, typography, and responsive behavior in `style.css`.
4. Keep the `<span id="year"></span>` element in the footer if the automatic year should remain enabled.

The CSS theme variables are defined at the top of `style.css`, making the main colors and font easy to change:

```css
:root {
  --bg-color: #0f172a;
  --card-bg: #1e293b;
  --accent-color: #38bdf8;
}
```

## Deployment

The project can be deployed to any static hosting provider. Common options include:

- GitHub Pages
- Netlify
- Vercel
- Azure Static Web Apps

For GitHub Pages, publish the repository from the branch and folder containing `index.html`. No build command or output directory is required.

## Browser support

The portfolio uses standard HTML, CSS, and JavaScript features supported by current versions of modern browsers.
