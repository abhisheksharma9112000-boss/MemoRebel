[README.md](https://github.com/user-attachments/files/29560432/README.md)
# MemoRebel Website

A free, static site (no backend, no hosting cost) — deploy it with **GitHub Pages** in about 2 minutes.

## Deploy for free (GitHub Pages)

1. Create a new **public** GitHub repository. Name it `MemoRebel` (or anything you like).
2. Upload the contents of this `website/` folder to the **root** of that repository
   (`index.html`, `privacy.html`, `guidelines.html`, `style.css` should sit at the repo root, not inside a subfolder).
3. On GitHub, go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source: Deploy from a branch**, **Branch: main / (root)**, then **Save**.
5. Wait about a minute — GitHub will give you a live URL:
   `https://<your-github-username>.github.io/MemoRebel/`

That's it — no server, no cost, auto-renewed HTTPS.

## Wiring the URL back into the app

Once deployed, open `app/src/main/java/com/boss/memorebel/SupportScreen.kt` and update the
"Official Website" card's URL (search for `github.com/MemoRebel`) to your real Pages URL.

## Updating content later

Just edit the `.html` files and push to GitHub — Pages redeploys automatically within a minute or two.
