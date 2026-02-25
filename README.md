# Portfolio (alternate)

Copy of the portfolio for a **separate** GitHub repository. Customize name, contact, projects, and image here independently from the main `myp2` project.

## Push to a different GitHub repo

1. **Create a new repository** on GitHub (do not use the same repo as `myp2`).

2. **From this folder**, init git and push:

   ```bash
   cd c:\Users\acer\Desktop\portfolio-2
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_OTHER_REPO_NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages** in the repo: **Settings → Pages → Deploy from a branch** → branch **main**, folder **/ (root)**.

4. Site will be at: `https://YOUR_USERNAME.github.io/YOUR_OTHER_REPO_NAME/`

## Customize this copy

- **Name:** Replace "Your Name" in the nav (line ~16) and hero (line ~33) in `index.html`.
- **Photo:** Add your image in this folder and set `src="yourfile.jpg"` in the About section (or use a different image for this version).
- **Contact:** Update email, LinkedIn, and GitHub URLs in the Contact section of `index.html`.
- **Content:** Edit projects, experience, and bio as needed for this version.

## Local preview

```bash
npx serve .
```

Then open the URL shown (e.g. `http://localhost:3000`).
