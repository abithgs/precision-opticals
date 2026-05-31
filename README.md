# Precision Opticals — Website

Official website for **Precision Opticals — Essilor Experts**, Jayanagar 4th T Block, Bengaluru.

## 🚀 Deploying on GitHub Pages

### 1. Create a GitHub Repository
- Go to [github.com/new](https://github.com/new)
- Name it anything (e.g., `precision-opticals` or `precisionopticals.github.io`)
- Set it to **Public**

### 2. Upload Files
Upload the contents of this zip to the repository:
```
├── index.html          ← Main website (single-page app with 4 tabs)
├── images/             ← Image folder structure (see below)
│   ├── hero/           ← Hero banner images
│   ├── frames/         ← Product frame images
│   ├── store/          ← Store interior photos
│   ├── testimonials/   ← Customer photos
│   └── misc/           ← Map, lens details, etc.
├── CNAME               ← Custom domain config (edit before deploying)
├── .nojekyll           ← Tells GitHub not to process with Jekyll
└── README.md           ← This file
```

### 3. Enable GitHub Pages
- Go to **Settings → Pages**
- Under **Source**, select **Deploy from a branch**
- Choose `main` branch, `/ (root)` folder
- Click **Save**

### 4. Connect Custom Domain (Hostinger)
1. Edit the `CNAME` file and replace `yourdomain.com` with your actual domain
2. In **Hostinger DNS settings**, add these records:
   | Type  | Name | Value                         |
   |-------|------|-------------------------------|
   | A     | @    | 185.199.108.153               |
   | A     | @    | 185.199.109.153               |
   | A     | @    | 185.199.110.153               |
   | A     | @    | 185.199.111.153               |
   | CNAME | www  | `<your-username>.github.io`   |
3. In GitHub repo **Settings → Pages → Custom Domain**, enter your domain
4. Check **Enforce HTTPS**

DNS propagation may take up to 24–48 hours.

## 🖼️ About Images

The site currently uses externally hosted images (Google CDN). These work fine and load fast globally.

**To use your own images:** Replace the photos with your actual store/product images:
1. Add your images to the appropriate `images/` subfolder
2. In `index.html`, find and replace the `src="https://lh3.googleusercontent.com/..."` URLs with local paths like `src="images/frames/your-photo.jpg"`

### Recommended image replacements:
| Current | Folder | Suggested replacement |
|---------|--------|----------------------|
| Hero banner | `images/hero/` | Your store exterior or a styled eyewear photo |
| Frame products (×4) | `images/frames/` | Photos of actual frames you sell |
| Store interior | `images/store/` | Your actual store interior |
| Customer avatars (×3) | `images/testimonials/` | Real customer photos (with permission) |
| Location map | `images/misc/` | Screenshot of your Google Maps location |

## 📞 Contact Info (in site)
- **Address:** No. 16, 34th Cross, 11th Main Rd, Jayanagar 4th T Block, Bengaluru 560041
- **Phone:** +91 99863 41896 / +91 97317 54666
- **Google Maps:** https://maps.app.goo.gl/Qev3HRwdvbSW1ucN6

---
© 2026 Precision Opticals. All rights reserved.
