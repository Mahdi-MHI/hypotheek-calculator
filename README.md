# 🏠 Dutch Mortgage Calculator / محاسبه‌گر وام مسکن هلند

An interactive, single-file web calculator for buying a home in the Netherlands. Everything runs in the browser — no server, no tracking, no dependencies to install.

**Live demo:** `https://mahdi-mhi.github.io/hypotheek-calculator/`

The interface is in **Persian (Farsi)**, with the Dutch financial terms shown alongside so users learn the local vocabulary (`hypotheek`, `annuïteit`, `hypotheekrenteaftrek`, `overwaarde`, and so on).

## Features

- **Monthly payment** (`maandlast`) for both mortgage types: annuity (`annuïteit`) and linear (`lineair`).
- **Per-payment breakdown** — how much of each installment is interest (`rente`) vs. principal (`aflossing`).
- **Tax deduction** (`hypotheekrenteaftrek`) — net refund after `eigenwoningforfait`, with a selectable 2026 bracket rate (35.75% / 37.56%).
- **Full amortization table** — monthly (first year) or yearly view.
- **Buy-vs-rent / sell-after-N-years analysis** — projects the sale price, remaining debt (`restschuld`), net proceeds (`overwaarde`), the true cost of owning, and compares it against renting.
- Adjustable inputs with a live highlight so you can see exactly which figures respond to each change.

## How to use

Open the live link, then move the sliders — loan amount, interest rate, term, WOZ value, appreciation rate, rent, and costs. Every result updates instantly.

## Interest rates

Default rates reflect the Dutch market as of **September 2026** (10-year fixed ≈ 3.78%). Rates change frequently — adjust the interest slider to your own quote.

## Tech

A single self-contained `index.html` file (HTML + CSS + JavaScript). The only external resource is the Vazirmatn web font from Google Fonts. Host it anywhere static: GitHub Pages, Netlify, Cloudflare Pages, etc.

## Disclaimer

This tool is for **educational and estimation purposes only**. It is not financial advice. Actual figures depend on your lender, income, `NHG` eligibility, and personal circumstances. Always confirm with a licensed mortgage adviser (`hypotheekadviseur`).

## License

MIT — free to use, modify, and share.
