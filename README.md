# Redwan Kabir — GIS Portfolio

Two-file portfolio system. No build step needed — works directly on GitHub Pages.

## Files
- `index.html` — Public portfolio (recruiter-facing)
- `admin.html` — CMS admin panel (your private editor)

## Deploy to GitHub Pages

1. Upload both files to your repo: `https://github.com/redwan95/kabirportfolio`
2. Also upload `assets/RedwanKabir_CV.pdf` and `assets/profile.jpg` to an `assets/` folder
3. Enable GitHub Pages: Settings → Pages → Branch: main, Folder: / (root)
4. Your portfolio is live at: `https://redwan95.github.io/kabirportfolio/`

## Using the Admin Panel

1. Open `admin.html` in your browser (or `/kabirportfolio/admin.html` on your live site)
2. Edit any section using the left sidebar navigation
3. Upload your resume via "Resume Upload" to auto-extract profile data (needs free Groq key)
4. Click "Save Changes" after each section
5. Use "Export JSON Backup" to back up your data
6. Open `/index.html` in a new tab to preview changes live

## Data Storage

All portfolio data is stored in browser localStorage. 
To sync across devices: use "Export JSON Backup" → "Restore Data" on the new device.

## Profile Photo

Upload via Admin Panel → Personal Info → click on the photo circle.
