# codeproof.tech

Landing page for [Codeproof](https://codeproof.tech) — runtime-verified PR review for Python teams.

## Setup

This site is hosted on GitHub Pages. To deploy, push to `main` branch.

### Formspree

The contact form uses [Formspree](https://formspree.io). To activate:

1. Create a free account at formspree.io (use `codeproof@proton.me`)
2. Create a new form
3. Copy the form ID (e.g., `xyzabcde`)
4. Replace `YOUR_FORM_ID` in `index.html` with your actual form ID

### Custom domain

1. In repo Settings → Pages → Custom domain, enter `codeproof.tech`
2. Add DNS records at your registrar:
   - `A` record: `185.199.108.153`
   - `A` record: `185.199.109.153`
   - `A` record: `185.199.110.153`
   - `A` record: `185.199.111.153`
   - `CNAME` for `www`: `codeproof-tech.github.io`
3. Enable "Enforce HTTPS" in Pages settings
