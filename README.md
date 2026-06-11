# Open Graph Preview Tester

A single-file browser tool that previews how a link's Open Graph card will look when shared, from an og:title, og:description, og:image URL, and canonical URL, with length hints and a ready-to-paste set of og and twitter meta tags.

**Live demo:** https://0xelitesystem.github.io/open-graph-preview-tester/

It runs entirely in the browser. Nothing is uploaded, stored, or tracked.

## What it shows

- A preview card styled like a shared link, with image, title, description, and domain
- Character counts with a flag when the title or description is likely to be truncated
- A recommendation to use a 1200 x 630 image
- A copyable block of og and twitter meta tags

## How to use

Open `index.html` in any browser, or visit the GitHub Pages URL. Fill in the title, description, image URL, and canonical URL, and the preview and the meta-tag block update as you type. If the image URL is public and reachable, the browser shows it in the card; otherwise the card shows the recommended dimensions. Copy the meta tags into the head of your page.

## Notes

The image is loaded by your own browser directly from the URL you enter; the tool itself does not fetch or transmit anything. Aim for a title around 60 characters and a description around 150 to 200, since platforms truncate beyond that.

## License

MIT. Copyright (c) 2026 0xelitesystem.
