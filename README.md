# Room to Expand — student practice site

A single, self-contained marketing page for Sean's Pantarei Approach student practice in Berlin.

## Files
- `index.html` — the entire site. No build step, no dependencies to install. Fonts (Google Fonts) and the booking calendar (Cal.com) load from their CDNs at runtime.

## Deploy on Netlify
1. Push this folder to a GitHub repo.
2. In Netlify: **Add new site → Import an existing project → pick the repo.**
3. Build command: **(leave empty)**. Publish directory: **`/`** (root).
4. Deploy. Every push to the default branch auto-deploys.

You can also deploy instantly without Git: drag this folder onto the Netlify "Sites" page.

## Editing
- All copy and styles live inline in `index.html`.
- Booking is wired to the Cal.com event `roomtoexpand/student-pantarei-session` on the EU instance (`app.cal.eu`).
- The About section uses an "S" monogram placeholder — drop in a real photo of Sean by replacing the `.portrait` block.
