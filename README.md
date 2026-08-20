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

Plain Jekyll on GitHub Pages: each page needs YAML front matter (a Markdown file
without it is served as raw text, not HTML), and `_layouts/default.html` is
deliberately self-contained so the site doesn't depend on a theme gem resolving.
