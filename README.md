# Overseer — Coming Soon

Static landing page for the Overseer project.

## Local preview

Open `index.html` directly in a browser, or serve the folder with any simple static web server.

Example with Python:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages

1. Create a GitHub repository for the website.
2. Add the files from this folder to the repository root.
3. Push to the `main` branch.
4. In GitHub open **Settings → Pages**.
5. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
6. Click **Save**.
7. GitHub will show the public Pages URL after deployment.

No build process is required.
