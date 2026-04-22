# A&R Construction Group — Website

A single-page, static marketing website for **A&R Construction Group**, a Toronto/GTA masonry and landscape construction firm.

Built as a single `index.html` file with no build step, no dependencies, and all assets in an `images/` folder. Drop it into GitHub Pages and you're live.

## Stack
- Pure HTML + CSS + vanilla JS
- Google Fonts: Cormorant Garamond (display) + Manrope (body)
- Black & gold brand palette

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `ar-construction-site`).
2. Upload `index.html` and the `images/` folder.
3. Go to **Settings → Pages**.
4. Under **Source**, select branch `main` and folder `/ (root)`, then save.
5. Your site will be live at `https://<your-username>.github.io/ar-construction-site/` in ~1 minute.

## Customizing

| What | Where in `index.html` |
|---|---|
| Phone number | Search for `905-392-8859` and `9053928859` |
| Email | Search for `info@arconstructiongroup.ca` |
| Service area | Search for "Toronto & the Greater Toronto Area" |
| Swap images | Replace files in `/images/` (keep filenames the same) or update `<img src>` attributes |
| Stats (years, properties) | Search for `stat-num` in the hero section |
| Testimonial | Search for `<blockquote>` |

## Form handling

The contact form currently shows a confirmation message on submit but does not send anywhere. To wire it up, use a free service like:

- **Formspree** — add `action="https://formspree.io/f/YOUR_ID"` and `method="POST"` to the `<form>` tag, remove the `onsubmit` handler.
- **Netlify Forms** — if hosting on Netlify, add `data-netlify="true"` to the `<form>` tag.
- **Web3Forms** — similar to Formspree.

## License

All rights reserved © A&R Construction Group.
