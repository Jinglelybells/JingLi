# 黎静 · Jing Li — Portfolio Site

## Files
- `index.html` — Main portfolio page (Home, Experience, Projects, Education, Contact)
- `portfolio.html` — Illustration & visual work gallery

## How to publish

### Netlify (easiest — 30 seconds)
1. Go to netlify.com/drop
2. Drag the entire `jing-li-site` folder onto the page
3. Done — you get a live URL instantly
4. Optional: connect a custom domain in Netlify settings

### GitHub Pages
1. Create a new repo at github.com (e.g. `jing-li-portfolio`)
2. Upload both HTML files to the repo root
3. Go to Settings → Pages → Source → Deploy from branch → main
4. Your site will be live at `yourusername.github.io/jing-li-portfolio`

### Vercel
1. Go to vercel.com → Add New → Project
2. Drag the folder or connect your GitHub repo
3. Deploy — live in under a minute

## Adding your own assets
Search these tags in the HTML to find every replaceable asset:
- `[ASSET: BACKGROUND]` — background image
- `[ASSET: PROJ-IMG-n]` — project screenshots
- `[ASSET: PORTFOLIO-n]` — illustration/portfolio images

Place image files in the same folder as the HTML files,
then set the `src` attribute on the relevant `<img>` tags.
