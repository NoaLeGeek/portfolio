# Portfolio Website

This is the portfolio website for Noa Ottermann, designed for GitHub Pages deployment.

## GitHub Pages

This website is designed to work with GitHub Pages. To enable GitHub Pages for this repository:

1. Go to your repository settings on GitHub
2. Scroll down to the "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose the branch you want to deploy from (usually `main` or `gh-pages`)
5. Select the root directory (`/ (root)`) as the folder
6. Click "Save"

Your portfolio will be available at: `https://NoaLeGeek.github.io/portfolio/`

## Local Development

To test the website locally:

```bash
# Start a simple HTTP server
python3 -m http.server 8000

# Or use Node.js if you prefer
npx http-server

# Then open http://localhost:8000 in your browser
```

## Customization

The website is contained in a single `index.html` file for simplicity. You can customize:

- Personal information in the HTML content
- Colors and styling in the CSS section
- Contact links and information
- Skills and project sections

## Features

- Responsive design that works on desktop and mobile
- Modern gradient background
- Clean, professional layout
- Contact links section
- Skills showcase
- SEO-friendly HTML structure
