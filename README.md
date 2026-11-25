# SoundCare

Public contents of [soundcarewa.com](https://soundcarewa.com/), saved on 25 November 2026.

SoundCare AI is SoundCare LLC’s post-acute placement site for licensed Adult Family Homes in Thurston, Lewis, and Mason counties, Washington. CEO: Henry Oh. Office address published on the site: 12924 SE 301st ST, Auburn, WA 98092. Phone: +1 (415) 767-8875.

## What is in this repo

| Path | Contents |
| --- | --- |
| `site/` | The five distinct HTML pages, with Cloudflare email obfuscation decoded into the published addresses |
| `content/site.md` | The same pages as readable text |
| `content/site.json` | Organization, open-bed listings, regulatory notices, the 10-agent list, form options, privacy policy, and terms |

The live site has no public API, image files, or separate database. Other URLs on the host return the homepage. The homepage navigation links “How It Works” and “Counties Covered” do not point at sections on the page. County coverage is in the footer.

Bed counts, rates, and regulatory dates are the values written into the HTML at the time of the fetch, not a live feed.

Pages still load Tailwind and Google fonts from their CDNs when opened in a browser.
