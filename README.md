# Zylock Landing Page

Landing page for [zylock.dev](https://zylock.dev) — Identity-aware secure remote access.

## Deployment

This site is deployed via GitHub Pages from the `main` branch root directory.

### Setup

1. Repository Settings → Pages
2. Source: Deploy from branch
3. Branch: `main` / `/ (root)`
4. Custom domain: `zylock.dev` (configured via CNAME file)

### Files

- `index.html` — Complete landing page (single file, no dependencies)
- `CNAME` — GitHub Pages custom domain configuration
- `main_README.md` — Product documentation (not shown on site)
- `DIRECTIVE.md` — Business model and positioning reference
- `ROADMAP.md` — Feature availability by edition

### Design Principles

- **No external dependencies** — All CSS is inline, no CDN, no analytics
- **No JavaScript dependencies** — Minimal inline JS only if needed
- **Single HTML file** — Easy to maintain and deploy
- **Mobile responsive** — Works on all device sizes
- **Fast loading** — Critical CSS inlined, no render-blocking resources
- **Accessible** — Semantic HTML, good contrast ratios

### Local Development

Simply open `index.html` in a browser. No build step required.

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

### Updates

Edit `index.html` directly. Push to `main` to deploy.

---

For product documentation, see [main_README.md](main_README.md).  
For business context, see [DIRECTIVE.md](DIRECTIVE.md).
