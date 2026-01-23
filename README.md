# Frank Bieder - Personal Academic Website

This is the personal academic website for Frank Bieder, PhD Candidate at Karlsruhe Institute of Technology (KIT) and FZI Research Center for Information Technology.

**Live Website:** [franklynjey.github.io](https://franklynjey.github.io) / [frank.bieders.de](https://frank.bieders.de)

### Technologies Used
- **HTML5** - Semantic markup
- **Tailwind CSS** (via CDN) - Utility-first CSS framework
- **Google Fonts (Inter)** - Typography
- **Vanilla JavaScript** - Interactive features


### What You Need To Do

Before publishing, please update the following placeholders:

1. **Google Scholar ID**: Replace `YOUR_ID` with your actual Google Scholar ID
   - Find in: Hero section, Publications section, Contact section
   - Format: `https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID`

2. **ORCID**: Replace `YOUR_ORCID` with your ORCID identifier (if you have one)
   - Find in: Profile card
   - Format: `https://orcid.org/0000-0000-0000-0000`

3. **LinkedIn**: Update the LinkedIn URL with your profile
   - Find in: Profile card, Contact section
   - Current: `https://www.linkedin.com/in/frank-bieder`

4. **Profile Photo**: Add your profile photo
   - Path: `assets/profile.jpg`
   - Recommended: Square image, at least 512x512px
   - If not provided, initials "FB" will be displayed

## 📁 File Structure

```
franklynjey.github.io/
├── index.html              # Main website file
├── assets/
│   ├── CV.pdf             # Your CV (already present)
│   └── profile.jpg        # Profile photo (to be added)
├── README.md              # This file
├── index_old.html         # Backup of previous version
└── index.html.backup      # Another backup
```

## 🚀 Deployment

This website is designed for **GitHub Pages**:

1. **Automatic Deployment**: Push to the `master` branch
2. **Custom Domain** (optional): Configure `frank.bieders.de` in repository settings
3. **HTTPS**: Automatically enabled by GitHub Pages

### Steps to Deploy

```bash
git add index.html README.md
git commit -m "Updated personal website with complete information"
git push origin master
```

The website will be live at `https://franklynjey.github.io` within a few minutes.

**Last Updated**: January 2026
**Version**: 2.0
**Status**: Ready for deployment ✅
