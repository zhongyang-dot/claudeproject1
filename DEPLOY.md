# Investment Pulse — Deployment Guide

## Quick Deploy Options (Free, all mobile-friendly)

### Option 1: GitHub Pages (Recommended — Easiest)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to your branch, folder: `/ (root)`
4. Your site is live at `https://<username>.github.io/<repo-name>/`
5. Share this URL with friends!

### Option 2: Netlify (Drag & Drop)
1. Go to [netlify.com](https://app.netlify.com/drop)
2. Drag the project folder onto the page
3. Done — you get a live URL instantly
4. Optional: connect to GitHub for auto-deploys

### Option 3: Vercel
1. Install: `npm i -g vercel`
2. Run: `vercel` in this folder
3. Follow the prompts — site is live in seconds

### Option 4: Cloudflare Pages
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect your GitHub repo
3. Set build output to `/` (no build step needed)
4. Deployed with global CDN

## Access on Your Phone
- **Easiest**: Open the deployed URL in your phone browser, then **"Add to Home Screen"** (Safari/Chrome menu). It will appear as an app icon.
- Share the URL directly via WhatsApp, Telegram, etc.

## Custom Domain (Optional)
All platforms above support custom domains. Buy a domain from Namecheap/Cloudflare (~$10/yr) and point it in the platform settings.

## How It Works
- Single `index.html` file — no build step, no backend, no API keys needed
- All data comes from **TradingView widgets** (free, real-time)
- Mobile-responsive dark theme
- Covers: Gold, Silver, Oil, Crypto (USDC/Circle focus), AI stocks, SaaS, S&P 500, Singapore STI, Smart Money indicators, News, Economic Calendar
