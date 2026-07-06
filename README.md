# GMAT Avenger

GMAT Avenger is a mobile-first, gamified GMAT prep web app for busy professionals.

## What is included

- Static single-page app in `index.html`
- Inline GMAT Avenger logo in the app header
- `CNAME` configured for `GMATAvenger.com`
- Adaptive-style score movement on every answer
- Timed questions, average time per question, and 10-on-the-trot concept mastery

## Deploy with GitHub Pages

1. Merge this PR into `main`.
2. Open the repository on GitHub.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/** root
5. Save.

GitHub Pages will publish the site and use the `CNAME` file for `GMATAvenger.com`.

## Connect the domain

At your domain registrar/DNS provider, point `GMATAvenger.com` to GitHub Pages:

- Add `A` records for the apex domain using GitHub Pages IPs.
- Add a `CNAME` record for `www` pointing to `MEHROTRAYASH2.github.io`.

After DNS propagates, return to **Settings > Pages** and enable **Enforce HTTPS**.
