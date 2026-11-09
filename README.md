# dhb.dev

Personal site, built with [Astro](https://astro.build) and deployed to GitHub Pages.

## Develop

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs to dist/
npm run check    # type and template checks
```

## Deploy

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site and
publishes it to GitHub Pages. In the repo's Settings → Pages, the source must be
set to **GitHub Actions**.

`public/CNAME` keeps the custom domain (dhb.dev). Old demo pages live under
`public/sample/` and are served at the same URLs as before.
