# Package Tracker

Scans your Gmail for package tracking numbers and shows live shipment status in a dashboard.

## Deploy to Railway

1. Push this repo to GitHub
2. Go to [railway.app](https://railway.app) → New Project → Deploy from GitHub repo
3. Select this repo
4. Add environment variable: `ANTHROPIC_API_KEY` = your key
5. Railway auto-builds and gives you a public URL

## Local dev

```bash
npm install
cd client && npm install && npm run build && cd ..
npm start
```

Then open http://localhost:3001
