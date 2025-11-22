# Render Studio Website

A modern, neon-themed website for Render Studio showcasing ERLC liveries, uniforms, ELS patterns, Discord branding, and bot development services.

## Features

- **Main Website** (`index.html`)
  - Hero section with animated orbit effect
  - Services showcase (Liveries, Clothing, ELS, Discord design, Bots, Premades)
  - Gallery section that loads from localStorage
  - Rundown video section
  - Responsive design with mobile support

- **Developer Panel** (`dev-login.html`)
  - Secure login system with dev and admin passwords
  - Publish management system
  - Image upload and preview
  - localStorage-based data persistence

## Local Development

To run the website locally:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Repository

This repository is maintained under [Duneworks Studios](https://github.com/Duneworks-Studios/Tylers-Website).

## Technologies

- Pure HTML, CSS, and JavaScript
- No external dependencies
- localStorage for data persistence
- Responsive CSS Grid and Flexbox layouts

## File Structure

- `index.html` - Main website page
- `index_with_rundown.html` - Alternative version with video section
- `dev-login.html` - Developer panel for content management
- `Artboard_9.png` - Logo image
- `b7ea6b49-b666-4f23-90f7-87f0dc505abe.png` - Hero image
- `1121 (1)(1).mp4` - Rundown video
- Various PNG images for gallery/assets

## Notes

- The dev panel uses localStorage, so published content is browser-specific
- All passwords are stored in the dev-login.html file
- The website is designed to work offline once loaded

