# Deployment

The fastest way to share this document privately or publicly is GitHub Pages.

## Quick Setup — GitHub Pages

1. **Create a new GitHub repository.** Either name it `the-plan` or anything else; if you'd like the URL to be `username.github.io`, name it exactly that.
2. **Upload these files** (`index.html`, `README.md`, `.gitignore`, `DEPLOY.md`) to the repo's main branch.
3. In the repo, go to **Settings → Pages**. Under "Source," select **Deploy from a branch**. Pick `main` and `/ (root)`. Save.
4. Wait 30–60 seconds. The site will be live at:
   - `https://username.github.io/the-plan/` *(if named `the-plan`)*
   - `https://username.github.io/` *(if named `username.github.io`)*

## Privacy

This document contains personal strategic content. Two options:

- **Private repo + share specific people only.** GitHub Pages on private repos is available with a paid plan (GitHub Pro or above). Recommended for personal documents.
- **Public repo with no name attached.** Strip identifying details from `README.md` and `index.html` first if going this route.

## Custom Domain *(optional)*

If you'd like a custom domain (e.g. `plan.yourdomain.com`):

1. Add a `CNAME` file containing only the domain name, e.g. `plan.yourdomain.com`
2. In your DNS provider, add a `CNAME` record pointing to `username.github.io`
3. In **Settings → Pages**, enter the custom domain and enable HTTPS

## Local Editing

To edit the document locally and preview before pushing:

```bash
git clone https://github.com/username/the-plan.git
cd the-plan
# Open index.html in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Make changes, commit, push. GitHub Pages redeploys automatically within a minute.

---

*That's it. Four steps and the document is live.*
