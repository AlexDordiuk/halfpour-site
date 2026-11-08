# Halfpour site

Static site for Halfpour: home, Privacy Policy and Support in English and Ukrainian. Served by GitHub Pages from this
repository (branch `main`, folder `/`, no build step) at https://alexdordiuk.github.io/halfpour-site/.

The pages are written in the app repository (`halfpour-ios/site/public`, see `site/README.md` there) and copied here:

```bash
cp -R ../halfpour-ios/site/public/. .
```

Links between pages are relative, so the site also works on a custom domain later.
