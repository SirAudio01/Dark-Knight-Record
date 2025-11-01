# Dark Knight Record

A modern web application built with React 19 and Vite, deployed on GitHub Pages.

## Overview

This is a single-page application (SPA) featuring a clean, responsive design with built-in dark/light theme support.

## Technology Stack

- **Frontend Framework**: React 19.0.0
- **Build Tool**: Vite
- **Styling**: CSS3 with custom properties
- **Deployment**: GitHub Pages
- **CI/CD**: GitHub Actions

## Features

- Modern React 19 features
- Responsive design
- Dark/light theme support (respects system preferences)
- Optimized performance with Vite
- Automated deployment via GitHub Actions

## Live Demo

This application is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

## Project Structure

```
Dark-Knight-Record/
├── index.html              # Main HTML entry point
├── index-Dla6ZdmG.js       # Compiled React application bundle
├── index-n_ryQ3BS.css      # Compiled styles
├── react-CHdo91hT.svg      # React logo
├── vite.svg                # Vite logo
├── .github/
│   └── workflows/
│       └── static.yml      # GitHub Actions deployment workflow
├── .gitignore              # Git ignore patterns
└── README.md               # This file
```

## Deployment

The application uses GitHub Actions for continuous deployment. On every push to the `main` branch:

1. GitHub Actions checks out the code
2. Configures GitHub Pages
3. Uploads the site as an artifact
4. Deploys to GitHub Pages

## Browser Support

This application uses modern JavaScript (ES modules) and CSS features. It works best in:

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## Accessibility

- Respects `prefers-reduced-motion` for animations
- Includes fallback message for users without JavaScript
- Semantic HTML structure
- Responsive design for all screen sizes

## Performance

- Minified and optimized JavaScript bundle
- CSS custom properties for efficient theming
- Preloaded critical assets
- Cache-busting via content hashes in filenames

## Contributing

This repository currently contains production build artifacts. For development:

1. Add source code in a `src/` directory
2. Include `package.json` with dependencies
3. Add build scripts for development and production
4. Update the GitHub Actions workflow to build before deploying

## License

[Add your license here]

## Contact

[Add your contact information or links here]

---

Built with React and Vite
