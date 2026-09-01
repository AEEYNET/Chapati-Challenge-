# 1000 Chapati for 1000 Smiles — Fundraising Site

A single-page fundraising site for the "1000 Chapati for 1000 Smiles" event on Sunday 20th September 2026 at Gatwick Mall, Ruai.

## Publishing free on GitHub Pages

1. Create a new repository on GitHub (e.g. `1000-chapati-challenge`).
2. Upload `index.html` and `poster.jpg` to the repository (drag-and-drop works, or use `git push`).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. GitHub will give you a live URL like `https://<your-username>.github.io/1000-chapati-challenge/` within a minute or two.
6. Optional: point your own domain at it via **Settings → Pages → Custom domain**.

## Updating the chapati counter

Open `index.html`, find this line near the bottom (inside the `<script>` tag):

```js
const startCount = 0;
```

Change `0` to however many chapatis have been funded so far, then re-upload the file. The circular counter updates automatically.

## Files

- `index.html` — the whole site (structure, styles, and behavior in one file)
- `poster.jpg` — the event poster, used in the "Why 1,000 chapatis?" section
