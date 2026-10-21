# realsanket.github.io

The home page, privacy policy and terms of **Sketch the Cloud Publisher**, the tool that uploads the videos of the
YouTube channel [Sketch the Cloud](https://www.youtube.com/@sketchthecloud) through the YouTube API (Google OAuth
consent screen → Branding).

- https://realsanket.github.io/ (home)
- https://realsanket.github.io/privacy.html
- https://realsanket.github.io/terms.html

Plain HTML + CSS, served by GitHub Pages from `main`. The tool itself lives in the private studio repo
(`tools/youtube.py`, `docs/youtube.md`).

**Keep the `google-site-verification` meta tag in `index.html`**: it proves to Google Search Console that this site
belongs to the Google account that owns the OAuth app (verified 2026-10-21). Removing it un-verifies the site and the
app's branding check fails again.
