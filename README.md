# Kodiak Legion — Public Team Hub

Static public website for Kodiak Legion 14U flag football, ready for GitHub Pages.

## Publish on GitHub Pages

1. Create a **public** repository named `kodiak-legion` under your personal GitHub account.
2. Upload the contents of this folder to the **root** of the repository (`index.html`, `assets/`, `README.md`, `.nojekyll`). Do not upload the ZIP itself as the site.
3. Go to **Settings → Pages**. Select **Deploy from a branch**, **main**, **/(root)**, then **Save**.
4. Your site will be at `https://YOUR-USERNAME.github.io/kodiak-legion/` after publishing.

## Updating the calendar

Edit the event descriptions and dates in `index.html` and the `events` object in `assets/app.js`. Both must be updated to keep displayed events and downloadable `.ics` files in sync. The calendar month currently displays November 2026.

## Important privacy and branding notes

- This repository is **public**. Do not upload the original coaching website, player evaluation spreadsheets, private roster/contact information, scouting reports, or depth charts.
- The approved Kodiak Legion neon bear crest is included in the assets folder and used throughout the site.
- This site does not have logins or a backend. The checklist is saved only in the visitor's browser.
- Tournament venue, kickoff time, and detailed rules remain unconfirmed.
- Practice location and timing were supplied by the team organizer; confirm field permission and availability independently.

## V6.2 Miami Vice color refresh

Colors now use neon cyan (`#35D8F5`), hot pink (`#FF56AE`), and deep ocean navy (`#070E19`). The public content and GitHub Pages setup remain unchanged. The official crest was added in V6.4.

## V6.3 color update
The Miami Vice palette now includes electric blue `#147DFF` alongside vice pink `#FF56AE`, neon cyan `#35D8F5`, and ocean navy `#070E19`. Electric blue is used in gradients, secondary buttons, selected events, and focus outlines.


## V6.4 crest branding
The uploaded neon Kodiak Legion crest is included at `assets/kodiak-legion-crest.png` and displayed in the header, hero, and favicon. The smaller WebP is used for the hero to improve loading performance.

## V6.5 tournament correction and scouting privacy

The November 13, 2026 4v4 tournament date is updated in both the public page and calendar exports. The private opponent scouting report is delivered **separately**, not inside this public GitHub ZIP. Never commit that report, private playbooks, athlete evaluations, or personal data to the public repository.

## V6.6 first practice reschedule

First practice is now **Sunday, October 25, 2026, 2:30–3:45 PM**, at Blue Lakes Park. Suggested arrival: 2:20 PM. The 75-minute practice agenda and downloadable calendar events are synchronized; calendar times use America/New_York. November 13 tournament details remain unchanged.


## V6.7 roster update
Added eight-player public roster with first names, nicknames, jersey numbers, and **provisional** primary/secondary positions from the October 2026 roster spreadsheet. Full surnames, apparel sizes, payment/order fields, and player evaluations are intentionally excluded from this public static website.

## V6.8 October 25 practice update
Seven athletes are expected; Adrian Velasquez (#51) is absent but remains on the roster. Public pages show only the expected count, not which minor is absent. New `parents.html` provides parent/guardian instructions. The private coaching dashboard and printable PDF are **separate** and MUST NOT be committed to this public repository.
