# Green Solar World Inc. — Website

Static single-page site (all assets inlined in `index.html`, hash-based routing). No build step.

## Deploy to Hostinger
**Option A – Git (hPanel → Websites → Advanced → Git):** add this repo, branch `main`, install path empty (deploys to `public_html`), then click Deploy. Enable auto-deploy via the webhook if you want pushes to go live.

**Option B – File Manager/FTP:** upload `index.html`, `.htaccess` and `robots.txt` into `public_html`.

Enable the free SSL certificate in hPanel; `.htaccess` redirects HTTP → HTTPS.
