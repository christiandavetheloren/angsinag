# Ang Sinag PWA demo

A responsive, mobile-friendly online publication prototype for Eastern Samar National Comprehensive High School.

## Run locally
Open `index.html` in a browser. To enable PWA installation and service-worker behavior, serve this folder over HTTPS or localhost, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Included
- Responsive Home page with publication branding and tagline
- News, Opinion, Feature, and Sports sections
- Editorial Cartooning page with title, artwork, artist, caption, and message
- Article detail views with headline, image, byline, publication date, full story, and photo caption
- Local demo CMS to add, edit, and delete articles and cartoons
- JSON content export
- PWA manifest and basic service worker
- Placeholder text and sample images

## Important limitations
- This is a front-end demonstration. CMS changes are stored in the current browser's localStorage and are not shared between editors or devices.
- It has no secure admin authentication, hosted database, server-side image upload, or multi-user permissions. A production deployment needs a secure backend.
- Sample stories and images are placeholders. Replace them with verified reporting and properly credited/permissioned images before publication.
- Google Fonts and remote sample images require internet access.
