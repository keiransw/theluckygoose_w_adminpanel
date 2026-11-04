# The Lucky Goose — website

Static site. No build step: the repo root is the web root.

- `index.html` – the site
- `data/menu.json`, `data/hours.json`, `data/gallery.json` – editable content
- `.pages.yml` – Pages CMS config (edit at https://app.pagescms.org)
- `img/`, `fonts/` – site assets
- `images/uploads/` – photos uploaded through the CMS

Hosting: publish the repo root from the `main` branch. Serve it at the domain root
(e.g. www.theluckygoose.com.mt), not a subfolder, so CMS-uploaded images resolve.
