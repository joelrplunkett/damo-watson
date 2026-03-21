# Damian Watson SEO Checklist

## After Deploy

1. Confirm the live homepage resolves at `https://www.damowatson.com/`.
2. Confirm `https://www.damowatson.com/robots.txt` loads.
3. Confirm `https://www.damowatson.com/sitemap.xml` loads.
4. Check page source and verify the canonical URL is `https://www.damowatson.com/`.
5. Check page source and verify the title starts with `Damian Watson`.

## Google Search Console

1. Add the property for `https://www.damowatson.com/` or the full domain property.
2. Verify ownership using the recommended DNS method in Cloudflare.
3. Submit `https://www.damowatson.com/sitemap.xml`.
4. Use URL Inspection on `https://www.damowatson.com/`.
5. Click `Request Indexing` after the new version is live.

## Cloudflare Checks

1. Make sure the site is not blocked by a `noindex` header or rule.
2. Make sure there is no redirect loop between `damowatson.com` and `www.damowatson.com`.
3. Pick one canonical host and redirect the other to it permanently.
4. If using caching rules, purge cache after deployment.

## Off-Site Signals

1. Update Damian's Instagram bio link to the final site URL.
2. If possible, add the site URL to Strava, UTMB, DUV, or race profile bios.
3. Ask podcast, race, or profile pages to link using the full name `Damian Watson`.
4. Keep the same name format across the site and social profiles: `Damian Watson` with `Damo Watson` as the nickname.

## Expectation

Search ranking changes are usually not immediate. After indexing is requested, movement can take several days or a few weeks.
