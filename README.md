# Love Letter Website

A simple static love-letter website built with HTML and CSS.

## Publish on GitHub Pages

1. Install Git for Windows from https://git-scm.com/download/win
2. Create a new repository on GitHub, for example `love-letter-website`
3. In PowerShell, run:

```powershell
cd "C:\Users\Acer\OneDrive\Desktop\Love-Letter-Website"
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

4. Open the repository on GitHub.
5. Go to `Settings` → `Pages`.
6. Select `Branch: main` and `Folder: / (root)`.
7. Save and wait for GitHub Pages to publish your site.

The published site URL will be shown on the Pages settings page.

## View locally

Open `index.html` directly in your browser, or run:

```powershell
cd "C:\Users\Acer\OneDrive\Desktop\Love-Letter-Website"
python -m http.server 8000
```

Then go to `http://localhost:8000`.

## Need help?

If you want, I can help you create the GitHub repo and push the project once Git is installed.
