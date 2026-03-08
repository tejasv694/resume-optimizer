# Resume Optimizer — Netlify Deployment

## Option A: Deploy via Netlify UI (with GitHub)
1. Push this folder to a GitHub repo
2. Go to netlify.com → Add new site → Import from GitHub
3. Build command: `npm run build`
4. Publish directory: `dist`
5. Click Deploy!

## Option B: Deploy via Netlify CLI (no GitHub needed)
1. Open terminal in this folder
2. Run:
   ```
   npm install
   npm run build
   npx netlify-cli deploy --prod --dir=dist
   ```
3. Follow the prompts to log in and pick a site name
4. Done! You'll get a live URL.
