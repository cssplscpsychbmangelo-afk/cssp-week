# 21infinityandBeyond — CSSP Week

An animated CSSP Week celebration page: 21 years, shaped by being a Rajah, from our first *pagpuputong*, and everything still ahead.

🔗 **Live site:** `https://<your-username>.github.io/21infinityandBeyond/`

## What's inside

A single, self-contained `index.html` — all CSS and JavaScript are inlined, so there are no build steps and no external dependencies.

## Publish it on GitHub Pages

### Option A — Upload in the browser (easiest)

1. Create a new repository on GitHub named **`21infinityandBeyond`** (public).
2. On the repo page, click **Add file → Upload files**.
3. Drag in `index.html` (and this `README.md`), then **Commit changes**.
4. Go to **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **Deploy from a branch**.
6. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
7. Wait ~1 minute, then open `https://<your-username>.github.io/21infinityandBeyond/`.

### Option B — Command line (git)

```bash
# inside this folder
git init
git add .
git commit -m "Publish 21infinityandBeyond CSSP Week page"
git branch -M main
git remote add origin https://github.com/<your-username>/21infinityandBeyond.git
git push -u origin main
```

Then enable Pages under **Settings → Pages** as described in Option A (steps 4–7).

## Notes

- The `.nojekyll` file tells GitHub Pages to serve the files as-is (no Jekyll processing).
- To use a custom domain, put it in the `CNAME` file and configure DNS with your registrar.
- Everything runs client-side; the page works offline once loaded.
