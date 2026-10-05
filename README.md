# sirwan.uk

A small, static personal homepage. It uses plain HTML and CSS, so there is no build step.

## Publish with GitHub Pages

Publish the repository's `main` branch from its root (`/`) in **Settings → Pages**. The `CNAME` file sets the custom domain to `sirwan.uk`.

At your DNS provider, point the root (`@`) to GitHub Pages with these four A records:

```text
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Optionally set `www` as a CNAME to `sirwanafifi.github.io` so it redirects to `sirwan.uk`. Enable **Enforce HTTPS** in GitHub Pages after the certificate is issued.
