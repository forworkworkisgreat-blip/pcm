# Physics Practical Copybook Studio — Vercel

This is a static HTML/CSS/JavaScript website. It does not require Python on Vercel.

## Deploy from Vercel dashboard
1. Unzip this archive.
2. Open https://vercel.com/new and sign in.
3. Import the folder through a GitHub repository (recommended) or use the Vercel CLI below.
4. Framework Preset: **Other**. Root Directory: repository root.
5. Build Command: leave empty. Output Directory: leave empty (serve root).
6. Deploy.

## Deploy with CLI
Install Node.js, then run inside this folder:

```bash
npx vercel
```

Answer setup prompts, then run `npx vercel --prod` to publish production.

## Local preview
Open index.html directly, or run `python -m http.server 8000` and visit http://localhost:8000.

## Notes
- The site uses localStorage to save copying progress **per browser/device**; it does not sync across devices.
- PDF reference page images are stored under assets/.
- The old Python server.py was only for local preview and is not required for deployment.
