# Bahria Faculty of Engineering Sciences Meeting Portal

This is a Jekyll-based meeting minutes portal designed to be hosted on GitHub Pages.

## Deployment Instructions for Username: `bufoes`

1. Create a GitHub repository with the exact name:  
   `bufoes.github.io`

2. Clone this repository locally or upload the contents of this ZIP file.

3. The folder structure includes:
   - `index.html` — main page listing meeting PDFs dynamically.
   - `_config.yml` — Jekyll configuration including folders.
   - Meeting folders: `acm`, `fbos`, `rac`, `frc`, `herc` with sample PDFs.

4. Push all files to the `main` branch of the `bufoes.github.io` repository.

5. In GitHub repository settings, enable **GitHub Pages**:
   - Source branch: `main`
   - Folder: `/ (root)`

6. After a few minutes, visit:  
   `https://bufoes.github.io/`

7. To update meeting minutes, simply add PDFs to the respective folders and push to GitHub. The site will automatically list them.

---

## Notes

- This uses Jekyll’s `site.static_files` to dynamically list PDFs.
- Make sure your PDFs have `.pdf` extension and are inside the relevant folders.

Enjoy your portal!
