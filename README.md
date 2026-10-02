# Green Room Global — website

Static site for **greenroomglobal.co**: U.S. company formation, registered agent, business address and tax preparation for international talent. English/Spanish toggle built in.

- `index.html` — the whole site (HTML, CSS and JS in one file)
- `CNAME` — custom domain for GitHub Pages

## Publish with GitHub Pages
1. Repo **Settings → Pages** → Source: *Deploy from a branch* → `main` / root.
2. At your domain registrar, add DNS records:
   - `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` for `www` → `<your-github-username>.github.io`
3. Back in Settings → Pages, tick **Enforce HTTPS** once the certificate is issued.
