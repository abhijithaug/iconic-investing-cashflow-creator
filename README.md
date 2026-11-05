# Iconic Investing – Cashflow Creator

Investor portal for [Iconic Investing](https://iconicinvesting.com.au): a home page plus four property calculators, in the Iconic Investing navy-and-gold brand.

Live site: https://iconiccalculator.netlify.app

## What's inside

| File | What it is |
|---|---|
| `index.html` | The full portal. Opens on the Home page and links to each tool. |
| `landing.html` | Stand-alone marketing landing page that links out to the portal. |
| `assets/iconic-investing-logo.webp` | The Iconic Investing logo (light version, for dark backgrounds). |

Everything runs in the browser from a single HTML file. There is no build step, server or database.

## Pages

Each page has its own address, so you can link straight to it:

| Address | Page |
|---|---|
| `/#home` | Home: mission, live example result, tool tiles, how it works, insights, events, partners |
| `/#cashflow` | Cashflow & capital growth: after-tax weekly cashflow, yields, break-even rent, 10–30 year forecast, save and compare properties |
| `/#stamp-duty` | Stamp duty & government fees: transfer duty, registration fees, owner-occupier and first home buyer concessions, First Home Owner Grant |
| `/#repayments` | Loan repayments: principal & interest vs interest only |
| `/#yield` | Rental yield: gross and net yield |

## Stamp duty data

Rates and fees are as at 1 July 2026 (2026–27) for all eight states and territories. They were cross-checked against BOQ's stamp duty calculator (InfoChoice) across 1,000 combinations of state, price and buyer type, and match to within $1.

When rates change (usually 1 July each year), update the `SCALES` table and the `stampDuty`, `dutyFor`, `govFees` and `fhogFor` functions in `index.html`.

Not included: foreign purchaser surcharges, off-the-plan concessions, and eligibility tests for concessions and grants.

## Deploying to Netlify

1. In Netlify, open the site and go to **Deploys**.
2. Drag this folder onto the upload box, or connect this GitHub repository so every push deploys automatically.

## Disclaimer

Figures are estimates for general information only and are not financial, tax or legal advice. Confirm stamp duty, LMI, lending and tax with a broker and accountant.
