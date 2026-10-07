# YPO MENA REX Playbook (FY26–27)

A single-page site for the YPO MENA Regional Executive Committee: officers, SMART goals, role guides, management contacts, policies and regional links.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site (HTML, CSS and JavaScript in one file) |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |
| `robots.txt` | Asks search engines not to index the site |
| `README.md` | This file |

## Publish on GitHub Pages

1. Sign in at github.com and click **New repository**. Name it, e.g. `ypo-mena-rex-playbook`.
2. Click **uploading an existing file**, drag in all four files (show hidden files so `.nojekyll` is included), then **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/ypo-mena-rex-playbook/`.

## Updating

Edit `index.html` on GitHub (pencil icon) or upload a new version, then commit. The site refreshes within a few minutes.

Most content lives in the JavaScript data near the bottom of `index.html`:
`U` (links), `REX` (officers), `GOALS`, `SHARED`, `ROLES`, `MGMT`, `CAN` / `CANT`, `DOCS`, `RLINKS`.

## Notes

- **Privacy:** GitHub Pages sites are public to anyone with the link, even from a private repository on most plans. `robots.txt` and the `noindex` tag only discourage search engines. Only GitHub Enterprise Cloud can restrict Pages to signed-in organisation members.
- **"Ask the playbook" chat:** this only works when the page is hosted as a Claude artifact. On GitHub Pages the button stays hidden; everything else works normally.
