# Mess Manager — Bachelor Point

Track meals, split costs & settle payments for a 5-member bachelor mess.
Built with Next.js 14 + TypeScript. Zero config Vercel deploy.

## Deploy to Vercel

### Option A — Vercel CLI (fastest)
```bash
npm i -g vercel
cd mess-manager
vercel
```

### Option B — Drag & drop
1. Go to https://vercel.com/new
2. Drag this folder onto the import page → Deploy

### Option C — GitHub
Push to GitHub, then import at vercel.com/new

## Run locally
```bash
npm install
npm run dev
# open http://localhost:3000
```

## Customise defaults
Edit `lib/types.ts`:
- `DEFAULT_MEMBERS` — change names, meals, days, paid amounts
- `DEFAULT_COSTS` — change rice/fish/gas prices
