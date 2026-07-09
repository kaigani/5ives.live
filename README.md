# 5ives.live

The public download and landing page for **5ives LIVE** — community broadcast TV for the AI film era. A free desktop app (Mac & Windows) for channels of AI film and openly licensed video on shared schedules, streamed peer-to-peer. No accounts, no algorithm, no gatekeepers.

- **Live site:** https://kaigani.github.io/5ives.live/ (will become https://5ives.live)
- **Downloads:** see the [latest release](https://github.com/kaigani/5ives.live/releases/latest) — installers are attached as release assets, and the site's download buttons always point at the latest release.

## Publishing a new build

1. Attach the new installers to a release with these exact asset names (the site links depend on them):
   - `5ives-LIVE-macOS.dmg`
   - `5ives-LIVE-Windows-setup.exe`
2. Tag it as a full release (not a pre-release) so `releases/latest` resolves to it.

## Custom domain

When pointing `5ives.live` at this repo: add a `CNAME` file containing `5ives.live`, set the domain in the repo's Pages settings, and create the DNS records GitHub Pages asks for (A/AAAA records for the apex, or a CNAME for `www`).
