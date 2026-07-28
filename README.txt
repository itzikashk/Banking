After Go-Live — banking production research
===========================================

This folder is a complete static website. One page, no build step,
no server-side code, no database.

  index.html   the whole site (report + presentation mode)
  robots.txt   tells search engines not to index it

TO PUBLISH
  Drag this whole folder onto any static host (Netlify, Cloudflare
  Pages, Vercel, GitHub Pages). No configuration needed.

TO MAKE IT PUBLICLY SEARCHABLE
  Delete robots.txt and remove this line from index.html:
  <meta name="robots" content="noindex, nofollow, noarchive">

TO VIEW WITHOUT PUBLISHING
  Double-click index.html. It opens in any browser.
  Fonts load from Google Fonts; offline it falls back to system fonts.
