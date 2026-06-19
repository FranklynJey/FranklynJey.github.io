# Frank Bieder - Personal Academic Website

This is the personal academic website for Frank Bieder, Group Leader for Visual & Spatial Learning at the FZI Research Center for Information Technology, and PhD (Dr.-Ing.) graduate of the Karlsruhe Institute of Technology (KIT).

**Live Website:** [franklynjey.github.io](https://franklynjey.github.io) / [frank.bieders.de](https://frank.bieders.de)

### Technologies Used
- **HTML5** - Semantic markup
- **Tailwind CSS** (via CDN) - Utility-first CSS framework
- **Google Fonts (Inter)** - Typography
- **Vanilla JavaScript** - Interactive features

### What You Need To Do

The Google Scholar and ORCID buttons were removed (they pointed at placeholder
IDs). Once you have real links, add them back to the hero CTA row, the profile
card, the Publications header, and the Contact section's Links row in
`index.html`.

## 📁 File Structure

```
franklynjey.github.io/
├── index.html              # Main website file (single page)
├── robots.txt              # Crawler directives
├── sitemap.xml             # XML sitemap
├── assets/
│   ├── CV.pdf               # Current CV (linked from the site)
│   └── profile.jpg          # Profile photo
├── CNAME                    # Custom domain (frank.bieders.de) for GitHub Pages
├── LICENSE                  # MIT license + third-party license notices
└── README.md                # This file
```

## 🖥️ Local Development

The site is a single static HTML file with no build step, so any of these work:

**Option A — just open it:**
```bash
open index.html        # macOS
xdg-open index.html    # Linux
```
This works because all assets are relative paths and styling/fonts load from CDNs.

**Option B — local web server (recommended, matches production more closely):**
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

**Option C — Node-based static server:**
```bash
npx serve .
```

**Option D — VS Code:** install the "Live Server" extension, right-click `index.html` → "Open with Live Server".

Any of these is enough to preview edits before pushing — there is no compile/build/deploy step for this repo.

## 🚀 Deployment

This website is hosted on **GitHub Pages**:

1. **Automatic Deployment**: Push to the `main` branch
2. **Custom Domain**: `frank.bieders.de`, configured via the `CNAME` file and DNS
3. **HTTPS**: Automatically enabled by GitHub Pages

### Steps to Deploy

```bash
git add index.html
git commit -m "Update site content"
git push origin main
```

The website will be live at `https://frank.bieders.de` within a few minutes.
