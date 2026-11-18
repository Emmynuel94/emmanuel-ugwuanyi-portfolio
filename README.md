# Emmanuel Ugwuanyi: Portfolio

A static portfolio website (HTML, CSS and vanilla JavaScript only). No build step.

## Files
- `index.html` : all page content
- `assets/css/style.css` : styles (colours are variables at the top)
- `assets/js/script.js` : theme toggle, mobile menu, contact form
- `assets/images/emmanuel-ugwuanyi.jpg` : profile photo
- `assets/documents/CV.pdf` : public CV (phone number and postcode removed)

## Publish on GitHub Pages
1. Create a new repository on GitHub (for example `portfolio`), set to Public.
2. Click **Add file > Upload files** and drag in the *contents* of this folder (so `index.html` is at the top level), then **Commit changes**.
3. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute or two your site appears at `https://YOUR-USERNAME.github.io/portfolio/`.

## Edit later
- Change text in `index.html`.
- Change colours in the `:root` blocks at the top of `assets/css/style.css`.
- Replace the CV by uploading a new file named `CV.pdf` into `assets/documents/`.
- To add project screenshots, save them in `assets/images/` and swap them in for the SVG illustration inside the project's `case-visual` block.
