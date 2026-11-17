# Personal Oura Analytics — informational website

Static pages for the three URL fields required by an Oura developer application. No health data, access tokens, secrets, client-side analytics or OAuth callbacks are hosted here.

## Publish
1. Sign in to GitHub and verify your username.
2. Create a **public** repository named `personal-oura-analytics`.
3. Upload `index.html`, `privacy.html`, `terms.html`, and `style.css` into the repository root; commit to `main`.
4. In **Settings → Pages**, choose **Deploy from a branch**, `main`, `/(root)`, then **Save**.
5. Verify that all three URLs are live before entering them into the Oura developer portal:
   - Website: `https://YOUR-USERNAME.github.io/personal-oura-analytics/`
   - Privacy: `https://YOUR-USERNAME.github.io/personal-oura-analytics/privacy.html`
   - Terms: `https://YOUR-USERNAME.github.io/personal-oura-analytics/terms.html`
6. Keep the OAuth redirect URI at the separately configured local callback (`http://localhost:8989/callback`), subject to Oura portal validation. GitHub Pages is **not** the OAuth callback.

**Security:** Never upload Oura client secrets, tokens, `.env` files, exported JSON/CSV health records, or credentials to this repository. Review the public policy/terms content and ensure it reflects how your eventual local application actually works.
