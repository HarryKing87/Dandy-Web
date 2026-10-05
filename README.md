# Dandy — Website

This is the landing page for Dandy, a private photo organization app for Android.

## Features

- Clean, minimal design
- Responsive layout
- Subtle animations
- Privacy-first messaging
- GitHub Pages ready

## Structure

```
├── index.html              # Main landing page
├── assets/
│   ├── css/style.css      # Styling with animations
│   └── js/script.js       # Scroll animations
├── pages/
│   ├── privacy.html       # Privacy policy
│   └── terms.html         # Terms & conditions
└── README.md
```

## Getting Started

1. Clone this repository
2. Serve locally: `python -m http.server 8000` (then visit `http://localhost:8000`)
3. Deploy to GitHub Pages:
   - Push to `main` branch
   - Enable GitHub Pages in repository settings
   - Set source to `main` branch

## Customization

- Update links in footer and nav
- Modify contact email in pages/privacy.html and pages/terms.html
- Change Play Store link in download section
- Update colors in `assets/css/style.css` (CSS variables at top)

## License

See LICENSE file
