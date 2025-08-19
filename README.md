## Website

### Overview
Static website built with only HTML, CSS, and JavaScript. It includes multiple pages for general content and sports/news coverage, styled via a shared stylesheet.

### Project Structure
```
Website/
  ├─ index.html      // Home page
  ├─ about.html      // About page
  ├─ live.html       // Live coverage page
  ├─ news.html       // News page
  ├─ sports.html     // Sports page
  └─ styles.css      // Global styles
```

### Tech Stack
- **HTML**: semantic markup for content
- **CSS**: global styling in `styles.css`
- **JavaScript**: vanilla JS only (no frameworks)

### Getting Started (Windows)
- **Quick open**: Double‑click `index.html` to open in your default browser.
- **VS Code Live Server (optional)**:
  1) Install the “Live Server” extension
  2) Open this folder in VS Code
  3) Right‑click `index.html` → “Open with Live Server”

### Development Guidelines
- **No frameworks/build tools**: keep to plain HTML, CSS, and JavaScript only.
- **Link styling**: Links across the site are intentionally styled in bold to stand out.
- **Consistency**: Reuse existing classes and follow the patterns in `styles.css`.
- **Accessibility**: Use semantic elements, proper headings, and alt text for images.

### Pages
- `index.html`: Landing/homepage
- `about.html`: Project/about information
- `live.html`: Live updates/coverage
- `news.html`: News listings and articles
- `sports.html`: Sports content and categories

### Styling
- All shared styles live in `styles.css` (typography, layout, colors, and link appearance).
- Prefer utility/structural classes already present; add new ones sparingly and descriptively.

### Deployment
This is a static site and can be hosted on any static host (e.g., GitHub Pages, Netlify, Vercel, or a basic web server). Upload the contents of the `Website` directory as‑is.

### Contributing
1) Create a new branch for your change
2) Keep HTML semantic and JS vanilla
3) Test locally in at least one modern browser
4) Open a pull request with a concise summary of changes

### License
No license specified.


