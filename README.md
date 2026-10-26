# f1yh1gh — Roblox Building Portfolio

Static website (HTML, CSS, JavaScript). No build step required.

## Publish on GitHub + Vercel
1. Unzip the downloaded ZIP file.
2. Create a new public or private repository at https://github.com/new (e.g. `f1yh1gh-portfolio`).
3. Click **uploading an existing file**, drag in `index.html`, `styles.css`, `script.js`, `projects.js`, `README.md`, and the entire `images` folder, then **Commit changes**. Ensure images retain the `images/` folder path. GitHub web upload may not preserve folders if you select only individual images; drag the entire folder or use GitHub Desktop if needed.
4. Sign in to https://vercel.com, choose **Add New → Project**, import the GitHub repository.
5. Select **Other** as framework preset if asked; leave build command empty and output directory at root/default. Click **Deploy**.
6. Vercel gives you a `.vercel.app` address.

## Edit
- Project images and names: `projects.js` and `images/`.
- Text, prices, terms and Discord: `index.html`.
- Colors and animation: `styles.css`.
- Slideshow behavior: `script.js`.

The intro is an original CSS interpretation of the requested cinematic purple style, not a frame-by-frame reproduction of the reference video.
