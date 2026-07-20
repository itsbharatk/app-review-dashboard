# App Review Insights Dashboard

A dashboard that turns raw App Store and Google Play reviews into sentiment analysis, categorized complaints, and feature-request tracking — built as a single self-contained tool, no backend or signup required.

> This is a showcase page for the project. The tool itself is private — see "Want to try it?" below.

## What it does

- **Live App Store fetching** — pulls reviews directly from Apple's public reviews feed for any app, by region.
- **Google Play support** — reviews can be pasted or uploaded (CSV/JSON/plain text) and analyzed the same way as App Store data.
- **Sentiment analysis** that blends star ratings with review text, with keyword coverage across English, Japanese, and Hindi/Hinglish.
- **Automatic complaint categorization** — crashes & bugs, performance, confusing UI, login issues, ads, pricing, customer support, notifications, sync/data loss, battery/storage, update problems, and privacy concerns, ranked by frequency.
- **Feature-request detection** — flags reviews asking for something new or missing, grouped by theme (dark mode, offline support, integrations, and more).
- **Interactive charts** — rating & sentiment trend over time (with adaptive day/week/month granularity), sentiment breakdown, and complaint category breakdown.
- **A filterable, searchable review table** with CSV export.
- Everything runs client-side in the browser — no reviews or data are ever sent to a server.

## Screenshots

<img width="1260" height="598" alt="Screenshot 2026-07-20 at 10 59 08 PM" src="https://github.com/user-attachments/assets/d7b5f369-d08b-4fd0-a188-de36e6348d51" />

<img width="1255" height="544" alt="Screenshot 2026-07-20 at 10 59 31 PM" src="https://github.com/user-attachments/assets/c787100e-c1a2-4696-acb1-dff55e2f9584" />

<img width="1256" height="646" alt="Screenshot 2026-07-20 at 10 59 48 PM" src="https://github.com/user-attachments/assets/ac7734fd-ae1d-4d09-9741-2e24fa56a3e7" />

<img width="1253" height="265" alt="Screenshot 2026-07-20 at 11 00 23 PM" src="https://github.com/user-attachments/assets/ea81cfe4-cfa6-4caf-8622-c175c99e26a8" />

<img width="1256" height="654" alt="Screenshot 2026-07-20 at 11 00 46 PM" src="https://github.com/user-attachments/assets/814501bc-7ad1-4166-94fd-368861e55e95" />


## Want to try it?

This project isn't publicly distributed right now. If you'd like a live walkthrough or a copy to use yourself, reach out to me.

## Built with

Vanilla HTML/CSS/JavaScript and [Chart.js](https://www.chartjs.org/) — a single file, no build step, no dependencies to install.
