# Nishita & Akshay — Wedding Invitation

A responsive, standalone wedding invitation with an animated wax-sealed envelope, traditional family invitation, scratch-to-reveal wedding date, animated portrait reveals, family photography, a wedding countdown, music and reveal sound controls, and event locations.

## Preview locally

Run `python3 -m http.server 4173` from this folder, then open http://localhost:4173.

## Deploy

Upload the contents of this repository to any static web host. No build step, backend, account, or login is required. The entry point is `index.html`; keep `style.css`, `app.js`, `wedding.ics`, and `assets/` alongside it.

For GitHub Pages, select **Settings → Pages → Deploy from a branch → main → / (root)**.

Music starts when a guest opens the envelope and can be paused using the floating music button. Fonts load from Google Fonts, with local serif and sans-serif fallbacks.

## Editing

- Invitation text, family details, event times, phone numbers, and map links: `index.html`
- Appearance and animations: `style.css`
- Envelope, scratch card, and music interactions: `app.js`
- Calendar download: `wedding.ics`
- Supplied audio and Ganesha artwork: `assets/`
