# Mary Agboola portfolio: redesign v3 (for review, not deployed)

Plain static site. No build step, no frameworks. Open `index.html` in a browser to preview.

## Files
- `index.html`, `lacelyf.html`, `s-and-s-automations.html`, `writing.html`
- `article-1.html` to `article-8.html` (original URLs kept)
- `css/style.css` (all styling), `js/main.js` (mobile menu, article contents list)
- `assets/mary-cutout.png` (your cutout, trimmed), `assets/og-image.png` (social share image, 1200x630)
- `favicon.svg`, `sitemap.xml`, `robots.txt`

## Deploy (only after you approve)
1. Test first: create a NEW Netlify site and drag the unzipped folder onto it. Do not touch the live site yet.
2. When happy, replace the files in your GitHub repo with these ones, keeping the same filenames, and commit.

## Design notes
- Pure white pages. No dark sections. Berry is used for type only.
- Watercolour blooms are painted with SVG filters (pooled edges, ragged bleed), not flat blobs. They sit at section edges and behind your photo.
- Hand-drawn crown, heart, flower and star details are limited to the hero, Pick My Brain and a few other places.
- The share image reuses the same blooms and your cutout, so it matches the site.
- Positioning line in the hero: "B2B brand & content marketer, SEO / AEO / GEO". The old tag line above the headline was replaced by it.
- Two handwritten notes ("Good content finds good people", "Big questions? Let's talk") come from your reference screenshots. Delete them if you don't want them.

## Content decisions (unchanged from before)
- Removed: 35% leads, 30-50% traffic, Page 1 rankings, all testimonials, HRoes, Inkthreadable.
- Em dashes removed everywhere, including inside articles (each became a comma). Article words and figures are untouched; a script checks this.
- No dates shown. Reading times = words / 210, rounded up (articles 1 to 8: 4, 3, 3, 3, 3, 6, 5, 6 minutes).
- Clockify listing tag reads "Unsolicited Pitch".

## Not verified
- Fonts (Fraunces, Hanken Grotesk, Caveat) load from Google Fonts. The test sandbox had no internet, so I never saw them load. In my screenshots the handwritten parts showed in a fallback serif. Check the live preview: the handwriting should look like handwriting.
- External links were not opened: Calendly, the two Lacelyf articles, LinkedIn, and the APA link in the Clockify article.
- Tested only in Chromium, desktop and phone width. Not Safari, Firefox or a real phone.
- Your cutout is 454 pixels wide. It is sharp at normal sizes but will look soft on big or high-density screens. A larger cutout would fix that.
- The share image text uses a system serif (the site fonts were not available offline). Check how it looks once shared on LinkedIn.
- Canonical URLs use the `.html` form. Check `/article-1` vs `/article-1.html` on Netlify.

## Needs your decision
- Chick-fil-A is named on the S&S page with a "no endorsement implied" line.
- The "$3,200/day" figure in the Clockify article is a hypothetical model, kept at your instruction.
