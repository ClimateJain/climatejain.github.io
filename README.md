# shiprajain.com — personal website

Static personal website for **Shipra Jain**, Assistant Professor at the Department of Risk and
Disaster Reduction, University College London. Rebuilt from the previous Google Sites version.

Live at: **https://climatejain.github.io** (served by GitHub Pages from the `main` branch).

## Structure

```
index.html            Home
about.html            Career timeline
research.html         Publications & reports
stories.html          Writing & science outreach
activities.html       Service, talks, teaching, mentoring
clouds/coast/         Photo galleries
mountains/moments.html
contact.html          Contact details
thoughts.html         Poems  (linked under "More")
ipcc-challenge.html   IPCC AR6 reading notes  (linked under "More")
assets/style.css      All styling
assets/img/           Web-optimised photographs
```

## Editing

Pages are plain HTML — edit the relevant file and commit. Styling lives in `assets/style.css`.
Photographs are resized/compressed for the web (long edge ≤ 1500&nbsp;px, JPEG q80); originals are
kept in the Google Takeout archive.

## Custom domain (optional, later)

To serve this at `www.shiprajain.com`, add a `CNAME` file containing `www.shiprajain.com`, then
point the domain's DNS at GitHub Pages and enable the custom domain in repo Settings → Pages.
