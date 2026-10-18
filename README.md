# VERITY - Minecraft Meme Coin Website

> The only truth in Minecraft is Verity.

## Quick Deploy to GitHub Pages (Free)

### Option 1: One-command deploy (recommended)
```bash
npm install && npm run deploy
```
This pushes to `gh-pages` branch. Enable GitHub Pages in repo Settings → Pages → Source: `gh-pages` branch.

### Option 2: Manual GitHub Pages
1. Push this repo to GitHub
2. Settings → Pages → Source: `main` branch / `/ (root)` folder
3. Your site lives at `https://<username>.github.io/<repo-name>/`

### Option 3: Netlify / Vercel / Cloudflare Pages
- Connect repo → auto-detects static site → deploys instantly
- Custom domain free on all three

## Local Dev
```bash
npm install && npm run dev
# Opens http://localhost:3000
```

## Customize
- Edit `index.html` for content, contract address, links
- Replace `og.png` (1200x630) for social previews
- Update `favicon.ico` (16x16, 32x32)
- Colors in CSS `:root` — change `--mc-green` for brand color

## Features
- Zero dependencies, single HTML file
- CRT scanlines, glitch text, floating particles
- Minecraft "pop" sound on button clicks
- Mobile-first responsive
- Accessible (reduced-motion support)

## Contract
Update the contract address in `index.html`:
```html
<div class="contract-address" id="contract">0xYourActualContractAddress</div>
```

## Social Links
Update hrefs in the `.links` section:
- Uniswap/DEX pair
- Twitter/X
- Telegram
- DexScreener chart

---

**VERITY** — Not financial advice. Meme coin. DYOR.
