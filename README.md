# Mayank Yadav — Creative Portfolio

Seven-page responsive React + Vite + Tailwind portfolio with GitHub Pages-compatible hash routing.

## Development
```bash
npm install
npm run dev
npm run build
```

## Original media
Put your portrait at `public/media/portrait.webp`, your resume at `public/media/mayank-resume.pdf`, and project images/videos in `public/media/`. Edit `src/data.js` to add real project entries and social links. No sample client projects or fake testimonials are included.

## Deploy
Merge the portfolio branch into main. In repository Settings → Pages choose **GitHub Actions**. The workflow builds and publishes on every push to main. With the configured Vite base, the standard URL is https://yadavgamingmayank-gif.github.io/my-portfolio/ . Hash routes work on refresh.

The existing root CNAME on main is intentionally not modified. If deploying with a custom domain, update Vite base and public asset URLs to match that domain and copy a CNAME into public/ before building.

Contact uses direct mailto and WhatsApp links, not a fake form submission.