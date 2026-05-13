# tile-mana-pages

Marketing site and legal pages for [TileMana](https://github.com/nyuto-free/tile-mana), hosted on GitHub Pages.

## Structure

```
.
├── index.html      # Landing page (hero + features + pricing)
├── terms.html      # Terms of Service / EULA
├── privacy.html    # Privacy Policy
├── refund.html     # Refund Policy
└── style.css       # Shared styles
```

## Local preview

Open `index.html` directly in a browser, or run a static file server:

```sh
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Deploy

Hosted on GitHub Pages. Pushing to the `main` branch publishes the site.

After enabling Pages in the repository settings (Source: `main` / root), the site
is available at:

`https://nyuto-free.github.io/tile-mana-pages/`

A custom domain can be added later by creating a `CNAME` file and pointing the
DNS records to GitHub Pages.

## Updating the policies

Update the "Last updated" date at the top of any legal page when you change it.
