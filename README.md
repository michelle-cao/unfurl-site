# unfurl-site

Public pages for the **unfurl** app: support, privacy policy, and terms of service. These are the URLs submitted to the App Store and Google Play. The app's source code lives in a separate private repo.

## Pages

- `index.html` — landing page linking to the three legal/support pages
- `support.html` — support + FAQ
- `privacy-policy.html` — privacy policy
- `terms-of-service.html` — terms of service

## Hosting (GitHub Pages)

1. Create a **public** repo on GitHub named `unfurl-site`.
2. Push this folder (commands below).
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `/ (root)` → Save.**
4. Wait ~1 minute. Your pages go live at:
   - `https://<username>.github.io/unfurl-site/`
   - `https://<username>.github.io/unfurl-site/support.html`
   - `https://<username>.github.io/unfurl-site/privacy-policy.html`
   - `https://<username>.github.io/unfurl-site/terms-of-service.html`

## App Store Connect / Play Console

- **Support URL** → `.../support.html`
- **Privacy Policy URL** → `.../privacy-policy.html`

Editing a page later: change the file, commit, push. GitHub Pages redeploys automatically.
