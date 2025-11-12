# Crypto Personality Test

This repository contains a static HTML quiz: `crypto_personality_test.html`.

How to publish on GitHub Pages (quick):

1. Go to the repository on GitHub → Settings → Pages.
   - Under "Build and deployment" / "Source", pick the branch `main` and folder `/ (root)`.
   - Click "Save".
2. Wait ~30–60s and then visit:
   `https://vanhovibes.github.io/Crypto-personality-test-/`

Notes:

- I added an `index.html` that redirects to `crypto_personality_test.html`, so you don't need to rename files.
- Optional: rename `crypto_personality_test.html` to `index.html` if you prefer no redirect.
- Optional: add a `CNAME` file (single line) to use a custom domain and configure DNS.

Troubleshooting:

- If you see a 404, verify Pages source is set to main / root.
- If features like clipboard or image download behave differently locally, they typically work once served over HTTPS (GitHub Pages provides HTTPS).

Local git workflow (if you'd rather push files yourself):

- Clone: `git clone https://github.com/vanhovibes/Crypto-personality-test-.git`
- Add files / edit
- Commit: `git add . && git commit -m "Add README for GitHub Pages"`
- Push: `git push origin main`