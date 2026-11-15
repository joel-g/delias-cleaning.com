# Delia's Cleaning

A lightweight Hugo site for Delia's Cleaning in South Puget Sound. The homepage uses site-owned layouts and CSS, with no JavaScript or external font dependencies.

## Preview

Install Hugo, then run from this directory:

```sh
hugo server
```

Open http://localhost:1313. Hugo refreshes the page when you save changes.

## Content and design

- `data/site.yaml`: homepage copy, contact details, service area, and image paths.
- `data/services.yaml`: residential and commercial service lists.
- `layouts/`: homepage, shared header/footer, metadata, icons, and 404 page.
- `assets/css/site.css`: typography, colors, layout, and responsive styles.
- `static/images/`: existing business photos and other image assets.

The previous theme and its original data remain in the repo for reference; they are no longer loaded. Update `data/site.yaml` to change current homepage copy.

Call and text buttons open the visitor's phone or messaging app. There is no contact form or backend.

## Production build

```sh
hugo --minify
```

The generated site is written to `public/`. The production URL is configured in `config.toml`. No publication is performed by the local preview or build commands.
