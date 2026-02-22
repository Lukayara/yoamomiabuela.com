# yoamomiabuela.com

## Play the game files

- **Main game:** [`snake-arena.html`](./snake-arena.html)
- **Quick entry:** [`game.html`](./game.html)
- **Site root (auto-redirects to game):** [`index.html`](./index.html)

## Publish to a website (GitHub Pages)

I added a Pages deploy workflow at `.github/workflows/deploy-pages.yml`.

1. Push this branch to your GitHub repo.
2. In GitHub: **Settings → Pages**.
3. Under **Build and deployment**, set **Source = GitHub Actions**.
4. Push to `main` (or run the workflow manually in **Actions**).
5. Your live URL will be:
   - `https://<your-github-username>.github.io/yoamomiabuela.com/`

When you open that URL, it redirects straight to the playable snake game.
