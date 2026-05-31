# Precision Opticals

Official website for **Precision Opticals — Essilor Experts**, Jayanagar 4th T Block, Bengaluru.

Live at: [precisionopticals.in](https://precisionopticals.in)

## About

Precision Opticals has served Bengaluru families since 2000 from its store on 34th Cross, 11th Main Road, Jayanagar 4th T Block. The store is a certified Essilor Expert outlet offering Varilux progressive lenses, Crizal coatings, Transitions photochromic lenses, and frames from Ray-Ban, Calvin Klein, Tommy Hilfiger, Emporio Armani, Oakley, and more.

## Tech

Single-page site built with HTML, Tailwind CSS (CDN), and vanilla JavaScript. Hosted on GitHub Pages with a custom domain.

- Four sections: Home, Lenses, Frames, About
- Hash-based client-side navigation with History API
- Scroll-triggered fade-in animations via IntersectionObserver
- Responsive — mobile, tablet, desktop

## Project Structure

```
├── index.html          — Full site (all pages, styles, and scripts)
├── images/
│   ├── hero/           — Hero banner
│   ├── frames/         — Frame product photos
│   ├── store/          — Store interior photos
│   ├── testimonials/   — Customer photos
│   └── misc/           — Map and other assets
├── CNAME               — Custom domain
└── .nojekyll           — Disables Jekyll processing on GitHub Pages
```

Images are currently served from Google CDN. To switch to local images, add files to the relevant `images/` subfolder and update the `src` attributes in `index.html`.

## Contact

**Address:** No. 16, 34th Cross, 11th Main Rd, Jayanagar 4th T Block, Bengaluru 560041  
**Phone:** +91 99863 41896 · +91 97317 54666  
**Maps:** [Precision Opticals on Google Maps](https://maps.app.goo.gl/Qev3HRwdvbSW1ucN6)
