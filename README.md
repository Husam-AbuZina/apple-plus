# Apple Plus Frontend

Vite/React storefront and administrator dashboard.

## Run locally

1. Copy `.env.example` to `.env`.
2. Keep `VITE_API_URL=http://localhost:5000/api` while developing locally.
3. Start the backend and then run:

```bash
npm install
npm run dev
```

The public storefront is available at `/`. The administrator interface is available at `/admin/login`.

For production, set `VITE_API_URL=https://api.your-domain.com/api` before building for Netlify.

The `public/_redirects` rule is included so direct visits to `/admin/login` and other client-side routes work on Netlify.
