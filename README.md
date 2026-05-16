# Paris — 13 to 16 July 2026

A three-night trip to Paris for **Louise Facon**, **Aurélie Facon** and **Anneleen De Paepe**.

**Live page:** https://pascalfacon.github.io/Paris/

## How this works

`index.html` is the public itinerary page, served via GitHub Pages.

Louise and Aurélie email ideas to Pascal. An Apps Script trigger forwards the email body to a GitHub Actions workflow, which runs an autonomous coding agent (Claude Code) that edits `index.html` and commits the change back to `main`. GitHub Pages then redeploys within ~1 minute.

See `.github/workflows/update-itinerary.yml` for the automation.

## Bookings

- **Train:** SNCF Lille Flandres ↔ Paris Nord — reservation `DQZRMB`
- **Hotel:** ibis Styles Paris Batignolles, 119 Avenue de Clichy, 75017 Paris — reservation `QCHHDHHZ` — 3 nights, breakfast included, €594.12 pay at hotel
