# Sidor Consulting — Setup Guide

## 1. Install Node.js (one time)

Go to https://nodejs.org and download the **LTS** version. Install it like any Mac app.

Verify it worked:
```bash
node -v
npm -v
```

## 2. Run the site locally

```bash
cd sidor-consulting
npm install
npm run dev
```

Open http://localhost:4321 in your browser.

## 3. Deploy to Vercel (free)

1. Push this folder to a GitHub repo (create one at github.com)
2. Go to vercel.com → "Add New Project" → import your GitHub repo
3. Click Deploy — done. Vercel auto-deploys on every git push.

Your site will be live at `your-project-name.vercel.app` for free.

## 4. Connect a custom domain (optional, ~$10/yr)

1. Buy a domain at https://www.cloudflare.com/products/registrar/
2. In Vercel: Project Settings → Domains → Add your domain
3. Follow Vercel's DNS instructions (copy 2 records into Cloudflare)
4. Done — usually live within minutes

## 5. Update your email

Search for `hello@sidorconsulting.com` in the `src/` folder and replace it with your real email.
