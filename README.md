# Neon Red Personal Portfolio

A responsive personal portfolio inspired by the uploaded video. Built with plain HTML, CSS and JavaScript; no framework or build tools required.

## 1. Open in VS Code
1. Extract `neon-portfolio.zip`.
2. Open the `neon-portfolio` folder in VS Code.
3. Open `index.html` in your browser, or use the VS Code Live Server extension and choose **Open with Live Server**.

## 2. Personalize before publishing
Your supplied email address is already added. If it changes, update the email links in `index.html` and the `to` address in `script.js`.

Replace `assets/profile.svg` with your own photo:
1. Add your photo to the `assets` folder, for example `profile.jpg`.
2. In `index.html`, change `src="assets/profile.svg"` to `src="assets/profile.jpg"`.
3. Use a photo you have permission to publish.

The portfolio content has been filled using the resume details you supplied. Review all content and links before publishing. Update project and social URLs to the correct public pages.

## 3. Run locally
There is no installation or terminal command needed. Open `index.html` in a browser. Live Server is recommended for automatic refresh.

## 4. Publish
### GitHub Pages
1. Create a GitHub repository.
2. Upload the contents of this folder (not the ZIP itself).
3. In repository **Settings → Pages**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Open the Pages URL GitHub provides.

### Netlify
1. Sign in to Netlify.
2. Choose **Add new site → Deploy manually**.
3. Drag the extracted project folder into the deploy area.

## Contact form note
The included form uses a `mailto:` link. It opens the visitor's configured email application; it does not send messages silently or store submissions. For a hosted form that collects messages without opening email, connect a trusted form backend/service and configure it before publishing.

## Project structure
```
neon-portfolio/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── profile.svg
```
