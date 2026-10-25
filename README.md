# moobiotics.com

Static one-page site for Moobiotics, served by GitHub Pages.

## Publish
1. Create a repo (e.g. `moobiotics-site`) and upload everything in this folder, keeping the `img/` folder.
2. Repo Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The `CNAME` file already points the site at moobiotics.com. Under Custom domain, enter moobiotics.com and tick "Enforce HTTPS" once it's available.

## DNS at Squarespace Domains
- Four A records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- CNAME record for `www` → `<your-github-username>.github.io`
- Leave the MX records alone so email keeps working.

## Still to fill in
- Team names, roles, one-line bios and photos (the "Meet the team" section in index.html).
