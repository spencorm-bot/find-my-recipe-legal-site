# Find My Recipe — Legal Pages (Vercel static)

A tiny static site with **Privacy**, **Data Deletion**, and **Terms** pages. Deploy on Vercel in ~1 minute.

## Deploy

1. Create a new GitHub repo and commit these files.
2. Go to https://vercel.com → **New Project** → **Import** the repo → **Deploy**.
3. After deploy, you’ll get a domain like `https://your-site.vercel.app`.

### URLs to paste into Meta → App settings → Basic
- Privacy Policy URL: `https://your-site.vercel.app/privacy`
- Data Deletion (URL): `https://your-site.vercel.app/data-deletion`
- Terms (optional): `https://your-site.vercel.app/terms`

> We set `cleanUrls: true` in `vercel.json` so `/privacy` maps to `privacy.html` (no `.html` in the path).

## Customize
- Update email addresses in the HTML files.
- Replace the effective date in `privacy.html` if needed.
