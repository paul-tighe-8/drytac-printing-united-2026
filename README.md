# Drytac: PRINTING United Expo 2026 giveaway landing page

QR landing page for the Polar Premium Air roll giveaway at PRINTING United Expo 2026
(Las Vegas Convention Center, Drytac booth C1937).

Static site, no build step, Tailwind via CDN. Deployed on Vercel from `main`.

| File | Purpose |
|---|---|
| `index.html` | The landing page. Serves at `/`. |
| `thank-you.html` | Post-submission confirmation. Serves at `/thank-you`. |
| `vercel.json` | Rewrite for `/thank-you`. |

The entry form is a CRM widget embed and must not be edited by hand; its branding is applied from
the page stylesheet via `::part()` selectors.
