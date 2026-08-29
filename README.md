# Teresa's Pet Care — New Bern, NC

A draft website for Teresa, Hahn Tech's first Local Ladder client.
**She has not approved it yet.** This repo is private for that reason.

## Finish this tomorrow — four things, in order

**1. Her phone number.** Open `site/index.html`, find:

    var PHONE = "";

Put her number between the quotes. The **Text me now** and **Call me now**
buttons switch on by themselves — no other edit needed. Until it is filled
they honestly say "needs Teresa's number" rather than pretending.

**2. Everything marked NEEDS TERESA.** Search the file for `NEEDS TERESA`.
Each one is a blank we deliberately did not guess: her rates, how far she
travels, whether she carries her own insurance, and whether she does baths.
**Her answers, in her words.** Do not invent them.

**3. Pick the domain, then change it in four places.** Currently set to
`newbernpetsitting.com`. If you buy something else, update:
`<link rel="canonical">`, `og:url`, `og:image`, `robots.txt` and `sitemap.xml`.

**4. Claim her Google Business Profile.** This is the piece that actually
makes the phone ring — more than the website does. Service-area business,
New Bern + Craven County, **no home address published**.

## What is already done
- Services, why-trust-her, service area, an eight-question FAQ
- A "Made in New Bern" section — all facts verified, not recalled
- Down East Dog Park details and free pet resources
- "Join the pack" — the Local Ladder network, built into the page
- Music generated in the browser with Web Audio: no file, no licence,
  nothing anyone can ever claim. Never autoplays.
- `og-image.png` 1200×630 share card, `favicon.svg`, robots, sitemap
- Light and dark themes, both rendered and inspected

## Deploying
Static. Cloudflare Pages or GitHub Pages both work — `site/` is the root.
Nothing to build, no dependencies.

## Two lines that must not be softened
On her page: she works **at a veterinary office**. She is **not** described
as a veterinary technician — that is a licensed title in North Carolina and
hers is unconfirmed.

## Contact
David Hahn — Hahn Technologies Corp
Text: (252) 253-9629 · hahntechnologiescorp@gmail.com · hahntechcorp.com
