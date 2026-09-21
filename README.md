# convoy-site

The public pages for the Convoy app, served by GitHub Pages:

- `/live/` - the "follow this rider" page a live-location link opens (`?t=<token>`).
- `/privacy/` - the privacy policy.

Both are generated from the app repo (`convoy-app`):

```
node scripts/build-live-page.js      # -> web/live/index.html
node scripts/build-privacy-html.js   # -> legal/privacy-policy.html
```

Copy the outputs into `live/index.html` and `privacy/index.html` here and push.