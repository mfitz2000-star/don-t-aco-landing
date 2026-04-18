# Don T. Aco Landing Page

Minimal static landing page for Vercel deployment.

## Folder structure

```text
.
├── index.html
├── vercel.json
└── README.md
```

## Deploy to Vercel

### Option 1: Vercel dashboard
1. Upload this folder to a GitHub repository.
2. Import the repository into Vercel.
3. Framework preset: **Other**.
4. Build command: leave blank.
5. Output directory: leave blank.
6. Deploy.

### Option 2: Vercel CLI
```bash
npm i -g vercel
cd don-t-aco-vercel
vercel --prod
```

## Notes
- `index.html` is the entry point.
- `vercel.json` is optional, but keeps URLs clean and disables trailing slashes.
- The book cover currently uses the Amazon-hosted image URL directly.
- The page links to:
  - Amazon book: https://www.amazon.com/dp/B0GXMWJVHY
  - TikTok: https://www.tiktok.com/@don.t.aco

## Recommended next changes
- Replace the Amazon-hosted cover image with a local `/public` asset for more control.
- Add a custom domain in Vercel.
- Add analytics or email capture if you want conversion tracking.
