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

<img width="1246" height="597" alt="Screenshot 2026-07-20 at 11 11 08 PM" src="https://github.com/user-attachments/assets/d4ee1028-b422-4865-a24e-681b84a9611d" />

<img width="1250" height="561" alt="Screenshot 2026-07-20 at 11 11 40 PM" src="https://github.com/user-attachments/assets/5564bbea-ac88-4607-b0f5-7d13060a6740" />

<img width="1255" height="580" alt="Screenshot 2026-07-20 at 11 11 59 PM" src="https://github.com/user-attachments/assets/fba7b68d-a994-4585-8fde-fb35f2397ee7" />

<img width="1253" height="204" alt="Screenshot 2026-07-20 at 11 12 17 PM" src="https://github.com/user-attachments/assets/18010a0f-766f-45a8-bc6a-4cb84539c924" />

<img width="1247" height="655" alt="Screenshot 2026-07-20 at 11 13 04 PM" src="https://github.com/user-attachments/assets/cd3f7334-7a1e-4fa0-a154-ca1397f63f8a" />

## Want to try it?

This project isn't publicly distributed right now. If you'd like a live walkthrough or a copy to use yourself, reach out to me.

## Built with

Vanilla HTML/CSS/JavaScript and [Chart.js](https://www.chartjs.org/) — a single file, no build step, no dependencies to install.
