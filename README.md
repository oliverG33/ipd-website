# Innovation Painting & Decorating — website

One-page static site. No build step: `index.html` + `images/`.

## Publish on GitHub Pages
1. Create a new repository (e.g. `ipd-website`) and upload everything in this folder.
2. Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
3. After a minute it's live at `https://<your-username>.github.io/ipd-website/`.

## Use ipd.nz
1. Settings → Pages → Custom domain → `ipd.nz` → Save (this adds a CNAME file).
2. At your domain registrar add DNS records:
   - A records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME for `www` → `<your-username>.github.io`
3. Once the certificate is issued, tick "Enforce HTTPS".

## Quote form
Submissions go to santiago@ipd.nz via FormSubmit.co. The FIRST submission triggers a
confirmation email to that address — click the link once and the form is active.

## Before launch
- Replace the phone number (021 xxx xxxx) — search index.html for "021".
- Replace the three sample reviews (marked "Sample review — replace").
- Fill in paint brands in the FAQ ("[Your preferred brands and systems]").
- Swap stock / other-company photos in images/ for Santiago's own jobs (keep the same filenames).
