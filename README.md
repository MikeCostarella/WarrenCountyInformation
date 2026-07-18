# Warren County Information

A searchable, filterable directory of meaningful links across **Warren County, Ohio** (county seat: Lebanon) — government, education, health, business, community, recreation, and news.

## What's inside

```
WarrenCountyInformation/
├── react-app/                  # the Vite + React browsing app
│   └── src/data/links.js       # single source of truth for all links
├── data/
│   └── warren_county_links.csv # the same directory as a spreadsheet
└── README.md
```

## Run it

```bash
cd react-app
npm install
npm run dev
```

Then open the URL Vite prints (usually http://localhost:5173/WarrenCountyInformation/).

## Add or edit links

Edit `react-app/src/data/links.js`. Keep `data/warren_county_links.csv` in sync if you rely on the spreadsheet.

## Notes

- Links were researched and reviewed on July 18, 2026 (17 links).
- This is a community reference tool, not an official government site.
