# FAST Link Training Simulator

Vercel-ready React/Vite deployment folder.

## Local run

```bash
npm install
npm run dev
```

## Deploy to Vercel

1. Push this folder to GitHub.
2. Import the GitHub repo into Vercel.
3. Add this Environment Variable in Vercel:

```bash
ANTHROPIC_API_KEY=your_anthropic_key_here
```

4. Deploy.

The React app calls `/api/claude`. The Vercel serverless function in `api/claude.js` keeps your Anthropic key server-side.

## Vercel settings

- Framework Preset: Vite
- Build Command: `npm run build`
- Output Directory: `dist`
