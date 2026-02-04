# Neuro Niche Website Setup

## Quick Start

1. **Add your images** to the `images/` folder:
   - `headshot.jpg` - Professional headshot (pink top photo) for the hero section
   - `casual.jpg` - Casual photo (yellow top) for the about section

2. **Run locally** using one of these methods:

   **Option A: VS Code Live Server**
   - Install the "Live Server" extension in VS Code
   - Right-click `index.html` and select "Open with Live Server"

   **Option B: Python**
   ```bash
   cd neuro-niche
   python -m http.server 8000
   ```
   Then open http://localhost:8000

   **Option C: Node.js**
   ```bash
   npx serve .
   ```

## File Structure

```
neuro-niche/
├── index.html      # Main HTML file
├── styles.css      # All CSS styles (separated for caching)
├── script.js       # JavaScript interactions
├── images/
│   ├── headshot.jpg  # Hero section photo
│   └── casual.jpg    # About section photo
└── SETUP.md        # This file
```

## Optimizations Applied

1. **Separated CSS/JS** - Better caching and maintainability
2. **Clean structure** - Organized into logical files
3. **Image paths** - Using dedicated images folder
4. **Mobile-ready** - Responsive design included

## To Deploy

For production, consider:
- Optimizing images (WebP format, compression)
- Minifying CSS/JS
- Adding meta tags for SEO
- Using a CDN for fonts
