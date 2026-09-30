# Kitchen Profit SA

**Know your cost. Grow your business.**

A mobile-first food costing and small-business toolkit for culinary students, home bakers, food vendors, and community sellers in Pretoria. This version runs entirely offline on your own PC — no internet connection, account, or install required after download.

## What's inside

- **Recipe cost calculator** — add ingredients and their cost, get total batch cost and cost per item
- **Selling price calculator** — 30% / 50% / 100% / custom markup, built on your recipe cost
- **Profit calculator** — units sold × price, with a South African VAT mode (inclusive / exclusive / none, 15%)
- **Inventory tracking** — stock levels with low-stock alerts ("Only 2kg flour remaining")
- **Pretoria supplier compare** — enter prices from Makro, Checkers, Shoprite, Pick n Pay side by side; the cheapest price per item is highlighted
- **Baking planner** — a simple scheduled list for orders, deliveries, school practicals, and community markets
- **Batch cost estimator** — type something like "I want to bake 50 chocolate cupcakes" and get an offline cost/price/profit estimate based on your saved recipe data (rule-based, not a live AI — see Notes below)
- **Business dashboard** — revenue, costs, profit, and margin for the period, plus your best-seller

## How to run it

You don't need to install anything. Pick whichever is easiest:

**Option A — just open it**
1. Unzip the folder if needed.
2. Double-click `index.html`.
3. It opens in your default browser and works immediately, offline.

**Option B — run it on localhost** (useful if your browser blocks local file features)
1. Open a terminal/command prompt in the app folder.
2. Run:
   - Windows: `python -m http.server 8000` (or `py -m http.server 8000`)
   - Mac/Linux: `python3 -m http.server 8000`
3. Open `http://localhost:8000` in your browser.
4. No internet connection is needed for this — the local server only serves files from your own PC.

## Where your data lives

Everything you type — recipes, prices, stock, planner entries, dashboard figures — is saved in your browser's local storage on this computer only. Nothing is uploaded anywhere. If you clear your browser's site data for this page, your entries will be cleared too.

To back up your data or move it to another computer:
- Use the same browser profile, or
- Ask for a future version with an Export/Import (CSV) button — not included in this build.

## Notes and limits of this offline build

- **No AI, no cloud sync, no payments, no marketplace.** Those need an internet connection and a backend server, so they're intentionally left out of this offline build. The "Batch cost estimator" tab gives a rule-based estimate using your own saved recipe cost — it's a planning shortcut, not a live AI assistant.
- **Single user, single device.** There are no logins and no multi-staff accounts in this build.
- **Supplier prices are entered by you.** There's no live price feed — the compare table just highlights the lowest price you've entered per item.

## Files in this folder

| File | Purpose |
|---|---|
| `index.html` | The entire app — open this file to run it |
| `README.md` | This file |

## Roadmap (if you outgrow this offline version)

1. **Phase 1** — Recipe costing and profit calculator *(this build)*
2. **Phase 2** — Live supplier price feeds and inventory sync *(this build has manual entry only)*
3. **Phase 3** — Online marketplace for Pretoria sellers
4. **Phase 4** — Nationwide South African food entrepreneur network, real AI assistant, multi-user Business Pro accounts

A companion document, `Kitchen Profit SA - Business Overview.docx`, covers the product, target users, pricing tiers, and roadmap in more detail for sharing with partners or investors.
