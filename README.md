# Legal Pages for Giant Guidance Inc. / GigiGuides.Ai

Static HTML landing + Privacy Policy + Terms of Service, ready to deploy to Vercel tonight so Google OAuth submissions can begin tomorrow.

## Quickest deploy (3 options, pick one)

### Option 1 — Vercel drag-and-drop (easiest, 3-5 min)

1. Go to https://vercel.com/new
2. Scroll down to "Deploy a folder" (or click "Upload")
3. Drag this entire `legal-pages-for-deploy` folder into the upload area
4. Name the project `gigiguides-legal`
5. Click Deploy — done in ~30 seconds
6. Vercel assigns a URL like `gigiguides-legal.vercel.app`
7. Privacy Policy lives at `gigiguides-legal.vercel.app/privacy`
8. Terms live at `gigiguides-legal.vercel.app/terms`

### Option 2 — Vercel CLI (2-3 min if you have Node installed)

```bash
cd "/path/to/legal-pages-for-deploy"
npx vercel --prod
```

Follow prompts. Signs in via browser the first time.

### Option 3 — Connect custom domain (adds 10 min for DNS)

After initial deploy succeeds:
1. Vercel Dashboard → your project → Settings → Domains
2. Add `giantguidance.com` (or a subdomain like `legal.giantguidance.com`)
3. Follow DNS instructions (add records at your domain registrar)
4. SSL certificate provisions automatically in ~5 min
5. Final URLs: `https://giantguidance.com/privacy` and `https://giantguidance.com/terms`

## After deployment

For Google OAuth verification (tomorrow morning, Coding Step 19):
- Privacy Policy URL: [paste the deployed /privacy URL]
- Terms of Service URL: [paste the deployed /terms URL]

## Files in this folder

- `index.html` — landing page (minimal)
- `privacy.html` — Privacy Policy STARTER v0.1 in HTML
- `terms.html` — Terms of Service STARTER v0.1 in HTML
- `vercel.json` — clean URLs + security headers
- `README.md` — this file (will be ignored by Vercel deploy)

## Update process when attorney reviews post-May-10

When the attorney sends back redlines:
1. Update `GigiGuides - Privacy Policy STARTER v0.1.md` or `GigiGuides - Terms of Service STARTER v0.1.md` → bump to v1.0
2. Re-run the md-to-html conversion
3. Replace files in this folder
4. Vercel auto-redeploys if connected to GitHub, OR re-drag-drop

## Placeholders to fill in before public announcement

- Contact emails should be working: hello@, privacy@, legal@, support@ (set up in Outlook/M365)
- If using custom domain: set up DNS first
- DPO / Privacy Lead contact name (can be Brad Holcomb at MVP-1)

