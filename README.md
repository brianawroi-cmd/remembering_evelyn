# Remembering Evelyn

A memorial website for **Evelyn M. Cornett**, formerly of the North Side, who entered into rest on Sunday, September 10, 2017, at age 82.

**Live site:** [rememberingevelyn.org](https://rememberingevelyn.org)

## About

This site honors Evelyn's life and the family she loved: four children, 12 grandchildren and 16 great-grandchildren. It includes:

- **Photo reel**: family photos of Evelyn
- **Her Story**: her obituary and life story
- **Her Family**: her husbands, children, grandchildren, great-grandchildren and siblings
- **Light a Candle**: a small gesture of remembrance for visitors
- **Guestbook**: a place for family and friends to share memories
- **Resting Place**: Saint Mary Cemetery, 4000 Mt Troy Rd, Pittsburgh, PA 15214

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole website (layout, styles and scripts) |
| `evelyn-1.jpg` – `evelyn-6.jpg` | Photos used in the photo reel and portrait |
| `CNAME` | Tells GitHub Pages to serve the site at rememberingevelyn.org |
| `.nojekyll` | Tells GitHub Pages to publish the files as-is |

## Hosting

The site is hosted with **GitHub Pages** from the `main` branch (root folder). The domain `rememberingevelyn.org` is registered and managed in Cloudflare, and `www.rememberingevelyn.org` redirects to the main address.

### Updating the site

1. Edit `index.html`, or upload new photos.
2. Commit the change to `main`.
3. GitHub Pages republishes the site within a minute or two.

### Adding a photo to the reel

Upload the photo (for example `evelyn-7.jpg`), then copy one of the `<figure>` blocks in the photo-roll section of `index.html`, change the `src` to the new file name, and write a short `alt` description of the photo.

## Notes

- Guestbook messages currently appear only in the visitor's browser and are not saved. Connecting the guestbook to storage is planned.

---

*Forever in our hearts.*
