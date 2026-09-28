# Fasting Coach website

The marketing site for Fasting Coach, an intermittent fasting app for iPhone. Three static pages, no build step.

- `index.html`: the site
- `privacy.html`: the privacy policy (give this URL to App Store Connect)
- `support.html`: support and FAQ (the support URL for App Store Connect)

## Hosting on GitHub Pages

1. In the repository settings, open Pages and set the source to the `main` branch, root folder.
2. Add your domain under Custom domain. GitHub writes a `CNAME` file for you.
3. At your DNS provider, point the domain at GitHub Pages: an `A` record for the apex to 185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153, or a `CNAME` for `www` to `<your-username>.github.io`. Turn on Enforce HTTPS once the certificate is issued.

## Before launch

- Replace the placeholder App Store link (`apps.apple.com/app/id0000000000`) in `index.html` with the real one, and fill in the Smart App Banner tag in the head.
- Swap the plain black button for Apple's official App Store badge from Apple's marketing resources.
- Keep `privacy.html` in step with the legal repository.
