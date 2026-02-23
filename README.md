# Vintage UI

A lightweight vintage-themed UI starter built with plain HTML and CSS.

## Files

- `index.html` — Demo page using the vintage components
- `vintage.ui.css` — Theme tokens and reusable UI styles
- `.dist/` — Optional distribution folder

## Features

- Warm vintage color palette
- Serif headings + clean body typography
- Reusable card, button, form, and layout styles
- Responsive two-column layout that collapses on smaller screens

## Run Locally

### Option 1: Open directly

```powershell
start .\index.html
```

### Option 2: Local server (recommended)

```powershell
python -m http.server 5500
```

Then open:

- http://localhost:5500

## Notes

- If inputs ever appear outside borders, make sure global border-box sizing is present in `vintage.ui.css`.
- You can customize colors in the `:root` variables at the top of the CSS file.
