# WARGAME: aufderaubistro
Date: 07/07/2026. See also C:\ZZZWebsites\.md\WARGAME-portfolio-seo.md.

## Mission and real state
Small bistro site, 6 pages, stable since 09/03/2026. Has canonical/OG/desc/analytics and llm.txt. Missing: JSON-LD entirely, _headers. Sitemap 5 URLs vs 6 pages. Deploys via wrangler.jsonc.

## Posture
Execute small, single pass. A restaurant with no Restaurant schema is leaving the biggest local-SEO lever unused.

## Moves
1. Add Restaurant JSON-LD (name, address, geo, openingHours, servesCuisine, menu URL, telephone) sourced ONLY from the site's own pages. Failure: invented hours/phone; counter: if a field is not on the site, omit it and flag.
2. Add _headers, reconcile sitemap (6th page in or deliberately out).
3. Check Google Business Profile consistency. [VARIABLE: does the client have a GBP, and does its NAP match the site?]

## Fragility
- Menus and hours rot fastest of any content type. If the real bistro changed anything since March, the site is already wrong. Verify with the owner before adding schema that hard-codes hours.

## Stretch
- Menu page with schema.org Menu markup, plus Thai/German language note (bistro audience mix). Judge later: only if the client is actually engaged.

## Abort
- No verifiable opening hours or phone from site content or Shayne: ship schema without those fields rather than guess.
