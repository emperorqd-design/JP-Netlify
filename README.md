# Jobs Pitches – Netlify recruitment site

Public site, serverless API (Netlify Functions) and storage (Netlify Blobs). No separate database needed.

## Deploy
1. Push this folder to a GitHub repo (or use `npm i -g netlify-cli && netlify deploy --prod`).
2. On Netlify: Add new site > Import from Git. Build settings are read from `netlify.toml`.
3. Site configuration > Environment variables, add:
   - `ADMIN_PASSWORD` – your admin login password
   - `ADMIN_SECRET` – any long random string
4. Redeploy. Open `/admin.html` and log in.

## Your logo
The Jobs Pitches logo is `public/logo.jpg` (replace the file to change it).

## Local test
`netlify dev` (needs the Netlify CLI and a `.env` copied from `.env.example`).
