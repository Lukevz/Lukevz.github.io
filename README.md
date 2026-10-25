# lukevz.github.io

The public pages for **Puffin'** — support, privacy policy and terms of use.

| Page | URL |
|---|---|
| Support (App Store "Support URL") | https://lukevz.github.io/support/ |
| Privacy Policy | https://lukevz.github.io/privacy-policy/ |
| Terms of Use | https://lukevz.github.io/terms-of-use/ |

These are the URLs hardcoded in `Puffin/Sources/App/Links.swift` in the app repo,
and the ones App Review opens by hand. **Changing a permalink here means shipping a
new build there** — don't rename a page without doing both.

## These pages have moved to startpuffin.com

The support, privacy and terms pages now live on
[startpuffin.com](https://www.startpuffin.com/) (the `Lukevz/puffin-site` repo),
at `/support/`, `/privacy/` and `/terms/`. The home page forwards to
https://www.startpuffin.com/. GitHub Pages can't send a server redirect, so each
copy here sets `canonical_url` and `redirect_to` in its front matter (the layout
turns them into a canonical link and an instant meta refresh), shows a "moved"
line at the top, and keeps its full text underneath as a fallback.

**Keep these copies and their permalinks.** Shipped app builds, the App Store
listing and App Review still open the lukevz.github.io URLs above, and the
forward is the only thing that gets them to the new pages.

**Never change `join/` or `.well-known/`.** Every shared invite link
(`https://lukevz.github.io/join/?code=CODE`) and the app's universal links
(`applinks:lukevz.github.io`) depend on them. They don't use the layout and don't
forward anywhere.

## How the site is built

Plain Jekyll on GitHub Pages: each page needs YAML front matter (a Markdown file
without it is served as raw text, not HTML), and `_layouts/default.html` is
deliberately self-contained so the site doesn't depend on a theme gem resolving.
