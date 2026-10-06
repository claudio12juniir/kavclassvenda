# KAV CLASS — Investor landing page

Static, bilingual (PT/EN) investor presentation. No build or package installation is required. Deploy the contents of `dist/` to a static web host, or preview with `python3 -m http.server 8080 --directory dist` from this directory.

## Vercel

The repository includes `vercel.json`, which rewrites the site root and its static assets to `dist/`. This lets Vercel deploy the repository directly without requiring a custom Root Directory or Output Directory setting.

## Contact

Set the confirmed investor-contact address in `dist/config.js` (`contactEmail`). When configured, the form prepares a `mailto:` message for review and sending in the visitor's mail application. It does not claim delivery or collect/store data. Without an address, the form clearly offers a local text download instead. A backend or form provider is required for direct submissions and delivery tracking.

## Content and assets

- Technical metrics come from the owner's brief dated October 5, 2026; they are attributed to the founder and have not been independently audited in this task.
- The owner confirmed full IP acquisition and a pre-revenue stage without commercial traction. Asking price is not yet determined; detailed transfer terms and trademark registration remain unconfirmed.
- The real logo is copied from `APP/my-app/assets/images/kavclass.png`.
- `APP/exemples/feed1.png` through `feed4.png` depict Instagram, X, Facebook and TikTok. They are not KAV CLASS screenshots and are intentionally excluded. Capture anonymized SELF and INSTITUTION screens before adding a real product gallery.
- The hero is an architecture diagram, not a simulated product screenshot.
- Google Fonts is optional; the CSS includes local system fallbacks.
- Language preference is stored on the visitor's device. Contact data is never persisted by the site.

## Review before public release

Contact is configured as claudiojrdesenvolvedor@gmail.com. Confirm detailed rights/transfer scope, trademark status and asking price before public release. Capture actual SELF and INSTITUTION screens. The current presentation does not assert competitor exclusivity or financial traction.
