# Geter India

```
hugo build  # Build the site
hugo server --bind 0.0.0.0 # Preview the site on this computer and your local network
```

GitHub Actions builds and deploys the site to https://geterindia.com/ on every
push to `master`. The generated `docs/` directory is ignored by Git; commit only
the source files. The workflow can also be run manually from the Actions tab.

GitHub Pages must use **GitHub Actions** as its publishing source under
**Settings → Pages → Build and deployment**. The custom domain is kept in
`static/CNAME` and the Pages settings.
