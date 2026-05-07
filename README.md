# Kuprava (kuprava.com)

Marketing website for **Kuprava** - a NetSuite integration practice founded by Nick Kenner. Static HTML + Bootstrap, no build step.

## Local preview

```bash
cd website-main
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deployment

Currently a single-page static site. The `CNAME` file points the project's GitHub Pages (or Cloudflare Pages) host to `kuprava.com`.

## Folder map

- `index.html` - the entire homepage
- `css/`, `js/` - Bootstrap assets
- `img/` - logos, hero image, partner/client logos, favicons
- `file/` - resume PDF

## TODO (next pass)

- Wire `Book a 20-min call` buttons to a real Calendly link
- Confirm production email (`hello@kuprava.com` or `nick@kuprava.com`)
- Add Open Graph / Twitter card meta tags for link previews
- Replace the example case-study numbers with approved metrics
- Add basic analytics (Plausible / GA4)
