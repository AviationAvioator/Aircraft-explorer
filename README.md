# Aircraft Explorer — Stage 4 (static release candidate)

Aircraft Explorer is a responsive, browser-based aviation exploration website.

## Run locally

Open `index.html` directly, or serve this folder using `python3 -m http.server 8000` and open `http://localhost:8000`. An internet connection is required for remote images and Wikipedia searches.

## Publish online

Upload the **contents of this folder** to a static hosting provider such as Netlify, Cloudflare Pages or GitHub Pages. The entrypoint is `index.html`. Hosting and a custom domain are **not** provisioned in this package. Test Wikipedia API behavior on the chosen hosting origin.

## Included

- Discover feed, desktop navigation arrows, mobile swipe navigation, 24 seed aircraft and Wikipedia article lookup.
- Search and filters, aircraft profiles, starter family trees, aviation concepts and glossary, side-by-side comparisons.
- Saved collections, likes, MyAirplane quiz, downloadable match graphic.
- Three selectable themes, unit preference, and import/export of local data.

## Release limitations and next steps

1. **Accounts are not implemented**: real Google/Apple/email login and cross-device sync need a secure authentication provider, database, and deployment configuration.
2. **Aircraft catalog is not yet production scale**: 24 starter profiles plus unverified Wikipedia search results, not the requested large verified aircraft database. Add a normalized, sourced catalog before describing it as comprehensive.
3. **Image rights require review**: Wikipedia thumbnail URLs are not a blanket license. Review the source page, Wikimedia Commons file page, author, license, attribution requirements and any restrictions before public release. A link to the article is included on profiles but may not be sufficient attribution.
4. **Specifications require verification**: values may vary by aircraft variant, payload and measurement conditions; unit preference is saved but does not automatically convert starter specifications.
5. **Storage is local**: backup exports help preserve likes/collections across browsers, but they are not secure account synchronization.
6. **Testing**: JavaScript syntax and archive packaging checked; browser/device acceptance and accessibility testing remain.

This is a static release candidate, not a production-certified aviation reference or a deployed service.
