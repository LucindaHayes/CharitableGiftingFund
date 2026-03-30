# Charitable Gifting Fund — Website

Three-page static site for `charitablegiftingfund.org`.

## Files

| File | Page | URL |
|------|------|-----|
| `index.html` | Main landing page | `charitablegiftingfund.org/` |
| `wealth-management.html` | Wealth management audience | `charitablegiftingfund.org/wealth-management` |
| `institutions.html` | Institutional partners | `charitablegiftingfund.org/institutions` |

## Deployment (GitHub Pages)

1. Push all files to the `main` branch
2. In the repository **Settings → Pages**, set source to `main` branch, root `/`
3. The site will publish at `https://[username].github.io/[repo]/` or your custom domain

## Custom Domain

To serve from `charitablegiftingfund.org`:
1. Add a `CNAME` file to the repo containing `charitablegiftingfund.org`
2. Point your DNS A records to GitHub Pages IPs (185.199.108–111.153)
3. Enable "Enforce HTTPS" in Settings → Pages once DNS propagates

## Notes

- All three files are fully self-contained — no build step, no dependencies
- Google Fonts load via CDN; pages require an internet connection to render correctly
- Internal navigation links use relative paths — all three files must remain in the same directory
