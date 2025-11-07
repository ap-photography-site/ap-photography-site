# AP Photography — Static Site
This is a simple static site for **AP Photography** (Hobart, TAS).

## Files
- `index.html` — main page (Tailwind via CDN)
- `main.js` — small helper script
- `assets/logo.svg` — inline logo
- `CNAME` — custom domain for GitHub Pages (paine.au)

## Deploy (GitHub Pages)
1. Create a **public** repo (e.g., `ap-photography-site`) and push these files.
2. In the repo: **Settings → Pages** → Source = `Deploy from a branch` → Branch = `main`, Folder = `/ (root)`.
3. Under **Custom domain**, enter `paine.au`, Save, then enable **Enforce HTTPS** once available.
4. In GoDaddy DNS for `paine.au`, add A records pointing to GitHub Pages IPs and optional AAAA (IPv6). See instructions in Chat.

Enjoy!
