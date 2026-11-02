# dezvoltareaiasului.ro — static copy

Static snapshot of https://dezvoltareaiasului.ro/ (WordPress + Divi), captured 2 Nov 2026, prepared for GitHub Pages.

## Publish on GitHub Pages

1. Create a GitHub repository and push the contents of this folder to its `main` branch.
2. In the repository: Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The `CNAME` file already names `dezvoltareaiasului.ro`. At the domain registrar, point the domain to GitHub Pages:
   - `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` record for `www` → `<github-username>.github.io`
4. In Settings → Pages, tick "Enforce HTTPS" once the DNS check passes.

## Notes

- `.nojekyll` makes GitHub Pages serve the files as they are.
- All links and assets are relative, so the site also works from a sub-path or opened locally.
- Server-side WordPress features no longer work: the search box, the comment form on `hello-world/`, and the admin-ajax endpoints.
- `hello-world/` is the default WordPress sample post; delete the folder if it is not wanted.
