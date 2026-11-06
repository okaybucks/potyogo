# Pötyögő website

Static pages for the App Store listing, published with GitHub Pages from a separate public repository:

| Page | App Store Connect field |
| --- | --- |
| `index.html` | Marketing URL |
| `privacy.html` | Privacy Policy URL |
| `support.html` | Support URL |

No build step, no external requests. Support address: hello@martonv.com. Keep `privacy.html` in step with the app's own privacy screen (`PrivacyView`).

Preview locally:

```bash
python3 -m http.server 8123 --bind 127.0.0.1 --directory site
```
