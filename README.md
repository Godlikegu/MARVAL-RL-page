# Paper Project Page

This repository contains a simple, modern landing page for your research paper, designed to be hosted on **GitHub Pages**.

You can edit `index.html` to update:

- The paper **title**, **authors**, and **venue**
- Links to the **PDF**, **code repository**, **arXiv**, datasets, models, and videos
- The **abstract**, **method overview**, **results highlights**, and **BibTeX**

The main style is defined in `style.css`, and a small script in `script.js` just updates the current year in the footer.

## How to use with GitHub Pages

1. **Create a new GitHub repository** (for example: `paper-project-page`).
2. Copy all files in this folder (`index.html`, `style.css`, `script.js`, `README.md`) into the repository and push:

   ```bash
   git init
   git add .
   git commit -m "Add paper project page"
   git branch -M main
   git remote add origin git@github.com:<your-username>/<your-repo>.git
   git push -u origin main
   ```

3. On GitHub, go to **Settings → Pages**:
   - Source: select **Deploy from a branch**
   - Branch: choose `main` and folder `/ (root)`
   - Save

4. After GitHub finishes building, your page will be available at:
   - For a project site: `https://<your-username>.github.io/<your-repo>/`
   - For a user site (if you use `<your-username>.github.io` as repo name): `https://<your-username>.github.io/`

## Customization Tips

- Replace the placeholder teaser in the right panel by adding an image under an `assets/` folder and using an `<img>` tag inside the `.preview-image` div in `index.html`.
- Adjust colors and layout in `style.css` (they are grouped at the top under `:root`).
- You can translate all text into your preferred language (e.g., Chinese, English, or bilingual).

