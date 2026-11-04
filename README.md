# Ezaz Kabir — GitHub Pages portfolio

This is a **complete static website** ready to publish to GitHub Pages. It is separate from the existing `outage-shield` source-code repository.

## What's included
- `index.html` — homepage, profile, certifications, project preview, contact
- `projects/outage-shield/index.html` — evidence-led project case study
- `assets/screenshots/` — eight original ServiceNow screenshots (full-resolution)
- `assets/previews/` — cropped/lighter-weight display copies
- `assets/docs/outage-shield-v1-test-evidence.pdf` — source validation report as PDF
- `assets/site.css` — responsive, accessible site styling
- `CNAME` — custom domain setting for `ezazkabir.com`

## Publish with GitHub Pages
1. Sign in to GitHub as `ezazkabir`.
2. Create a **public** repository named exactly `ezazkabir.github.io`. Keep it **separate** from `outage-shield`.
3. Upload the **contents** of this folder to the repository root (including the normally hidden `.nojekyll` file). GitHub's browser uploader may skip hidden files; the site works without `.nojekyll` for this simple static setup.
4. Commit the files to the `main` branch.
5. In the repository's **Settings → Pages**, set the publishing source to **Deploy from a branch**, using `main` and `/ (root)` (if not already configured).
6. Confirm the default website loads at `https://ezazkabir.github.io/`.
7. In **Pages → Custom domain**, enter `ezazkabir.com` and save. The supplied `CNAME` file specifies the same domain.
8. In GoDaddy's DNS management for `ezazkabir.com`, follow GitHub's current official custom-domain instructions. For an apex domain (without `www`), use the A/AAAA/ALIAS records GitHub currently requires. Add a `www` CNAME to `ezazkabir.github.io` if you also want `www.ezazkabir.com` to work. **Do not overwrite MX/TXT records used for email.**
9. Once the certificate becomes available in Pages, enable **Enforce HTTPS**. Check both desktop and mobile.

Official guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Before you share on your CV
- Check that `https://github.com/ezazkabir/outage-shield` is public and shows the expected app files. If it is private, either make it public after removing secrets or remove that link from the site.
- Confirm `mailto:ezaz.kabir.uk@gmail.com` is the address you want made public.
- Verify the screenshot content contains no sensitive data. Existing screenshot test accounts use example.com addresses and a PDI system administrator.
- Open the validation report PDF to confirm it displays correctly.
- If you want a video later, add a YouTube or Vimeo embed to the case study; do not upload a large video into the Git repository.
- You do **not** need to upload your old CV PDFs to the public site. They still describe Outage Shield as in design / in development. Update the CV first.

## Updating
This site is intentionally plain HTML and CSS; no paid hosting, third-party packages or build step are required. Add future projects under `projects/`, then add cards in `index.html`. The existing `outage-shield` repository remains untouched.
