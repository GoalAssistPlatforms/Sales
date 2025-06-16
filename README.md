# Sales Dashboard

This repository contains a web-based sales dashboard.

## Opening the Dashboard

Open `index.html` in any modern web browser. No additional setup is required as all logic is contained in the HTML and JavaScript within this file.

## Features

- **Login Screen** – Users log in with a SalesRep ID and password. Successful login shows the main dashboard.
- **Dashboard Tab** – Displays KPI tiles such as marketing posts, engagement, outreach attempts, successful sales, conversion rates, and commission earned. Timeframes (all, weekly, monthly, yearly) can be selected.
- **Achievements** – Achievement cards showcase progress toward marketing, sales, and captain milestones.
- **Leaderboards Tab** – Shows ranking tables for individual and university performance with timeframe filters.
- **Reports Tab** – Provides active scripts and a form to submit marketing and sales activity.

All data is retrieved from Google Sheets, so an internet connection is required for the dashboard to function fully.

## Expected Assets

The dashboard expects several images stored in the repository root:

- `Logo.png` for the login page and sidebar branding.
- Achievement icons such as `CAP001.png`, `ENG001.png`, `MAP001.png`, `NSM001.png`, `SAO001.png`, `SAR001.png`, and corresponding `X` placeholders (e.g., `CAPX.png`, `ENGX.png`).

Ensure these PNG files remain alongside `index.html` so that achievements and logos display correctly.
