# x-m-wedding

Digital wedding invitation — static site for GitHub Pages.

To publish via GitHub Pages:

1. Commit and push the repository to the `main` branch.
2. In the repository Settings → Pages, select the `main` branch and folder `/ (root)`.
3. Save — your site will be available at `https://<your-username>.github.io/<repo>/`.

Quick local preview:

```bash
# from repo root
python3 -m http.server 8000
# then open http://localhost:8000/index.html
```

Files:

- `index.html` — the invitation (accessible & responsive).

- `index.html` — RSVP page (site root)
- `invitation.html` — the original invitation (openable from the site)

If you'd like, I can create a `gh-pages` branch and open a PR for automatic publishing.
