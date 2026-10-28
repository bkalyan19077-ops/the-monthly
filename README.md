# The Monthly — Kalyan’s personal ledger

A responsive React application for personal monthly expenses. Includes expense creation, editing and deletion, monthly budgets, daily spending charts, category breakdowns, search, filters, and CSV export. Starts with an empty ledger; all amounts are in USD.

## Run

```sh
npm install
npm run dev
```

## Production build

```sh
npm run build
npm run preview
```

Data is stored in this browser's localStorage on this device. It is not synced across devices. Export CSV to keep a copy of your expenses. Clearing browser storage removes saved expenses and budgets. Google Fonts is optional; system fonts are used if it is unavailable.

## Design

A personal ledger direction created for Kalyan: warm paper surfaces, ink blue accents, a custom typographic k/ mark, editorial serif headings, ruled account summaries, and chapter numbering for each month. Existing browser storage keys are retained so the redesign preserves saved records.

## GitHub Pages

The included GitHub Actions workflow builds and deploys on every push to `main`. In repository Settings → Pages, set the source to **GitHub Actions**. Asset paths are relative so the app works under the repository URL.

Expenses remain in each visitor’s browser; they are not uploaded to GitHub. The deployed site has separate browser storage from localhost, so existing local expenses do not automatically appear on the hosted site.
