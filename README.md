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

*(Add a screenshot or two here — the KPI/insight view and one of the charts work well.)*

`![Dashboard overview](./screenshots/overview.png)`

## Demo video

*(Add a link to your recorded walkthrough here once it's ready.)*

## Want to try it?

This project isn't publicly distributed right now. If you'd like a live walkthrough or a copy to use yourself, reach out — [add your preferred contact: email / LinkedIn / etc.]

## Built with

Vanilla HTML/CSS/JavaScript and [Chart.js](https://www.chartjs.org/) — a single file, no build step, no dependencies to install.
