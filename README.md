# imbandita.com

The public website for Imbandita, served by GitHub Pages at https://imbandita.com.

- `index.html` is the whole site, one file, Arabic and English (`/?lang=ar` opens Arabic).
  Source: Amer's site package of 2026-10-21, built with three changes: Arabic in Tajawal
  (free) in place of Janna LT, 92% in place of 93% (5,338 of 5,784 products), and the email
  hand-off worded as the normal path.
- Settings are in `window.IMB_CONFIG` near the bottom of `index.html`: `email` an@dot-cs.com
  (the contact form writes the lead into the visitor's own email app, addressed there),
  `appUrl` https://app.imbandita.com (the Log in button), no form service, no WhatsApp.
- `og-image.png` is the link preview for LinkedIn, WhatsApp and X; `sitemap.xml` and
  `robots.txt` are for search engines.
- DNS lives in GoDaddy: `@` has the four GitHub Pages A records, `www` is a CNAME to
  `amernajjari.github.io`. `app` and `api` point at the app server and are not touched here.
