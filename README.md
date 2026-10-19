# Meadow House Repairs

A browser app for reporting and tracking repairs at the fictional Meadow House. Built for the Omega Digital hackathon, 19 October 2026.

## Run it

No install, server or API key is needed.

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

## What it does

- Report a repair with a description, reporter name and Normal or Urgent priority. Blank or spaces-only descriptions and names are rejected.
- Each valid report creates a **New** job with an automatic unique ID (MH-0001, MH-0002, ...), the date, and the house name Meadow House.
- Jobs are independent. Each can be moved to **In Progress**, given progress notes, and marked **Completed** with a required completion note.
- Every change is added to a dated and timed history. Earlier entries are kept.
- Jobs are saved in the browser's `localStorage`, so they survive a refresh.
- All typed text is displayed as plain text (set with `textContent`), so `<b>check gate</b>` appears literally.

## Notes

- Single file (HTML, CSS and JavaScript), no framework or dependencies.
- Fictional data only. To reset the app, clear this site's data in your browser.
