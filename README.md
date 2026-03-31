# Personal Homepage

A simple, responsive personal homepage deployed via GitHub Pages.

## Project Structure
```
├── index.html            # Main entry page
├── css/
│   └── style.css         # Responsive styles
├── js/
│   └── main.js           # Navigation, scroll effects
├── assets/
│   └── images/           # Your images (avatar, project screenshots)
├── .github/
│   └── workflows/
│       └── deploy.yml    # Auto-deploy via GitHub Actions
└── README.md
```

## Getting Started

### Local Preview
Just open `index.html` in your browser.

### Deploy to GitHub Pages

1. Create a repository on GitHub
2. Push all files:
   ```bash
   git init
   git add .
   git commit -m "Initial personal homepage"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. Go to Repository → **Settings → Pages**
4. Under **Source**, select **GitHub Actions**
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

## Customization

- Replace `Your Name` and placeholder content in [index.html](index.html)
- Swap the SVG avatar with your own image in `assets/images/`
- Update project info, skills, and contact links
- Update colors in [css/style.css](css/style.css) `:root` variables
