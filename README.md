# Profile Frontend

A static profile screen built with Tailwind CSS CDN assets. Scripts rely only on Python's built-in HTTP server—no extra dependencies required.

## Scripts
- `npm run dev` – serve the app from the generated `public/` directory at http://localhost:4173.
- `npm run build` – copy the HTML into `public/` (the folder Vercel publishes).
- `npm run preview` – serve the `public/` folder locally.

## Deploying to Vercel (no local CLI needed)
Everything Vercel needs is committed to the repo—just import the project in the Vercel dashboard or drag-and-drop the folder. Settings:

- **Framework Preset:** `Other`
- **Build Command:** `npm run build`
- **Output Directory:** `public`

If you prefer, you can also rely on the included `vercel.json`, which already declares the same build command and output directory, so you don't have to set anything manually.

## Notes
The page uses remote Google Fonts and Tailwind CDN assets, so an internet connection is required for styles to load fully.
