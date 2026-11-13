# Ledger – Company Accounts

A dark, minimal, mobile-friendly accounting app. No build step, no dependencies: one `index.html`.

## Features
- **Dashboard**: cash balance, revenue, gross and net profit, expenses, stock value, receivables, payables, 6-month chart, recent activity, low-stock alerts
- **Sales** with Prepaid or COD (partial advance supported, "Collect balance" on delivery), auto profit per sale, stock reduced, **Purchases** (stock increased, weighted-average cost)
- **Stock** with opening quantity, cost, price and low-stock alerts
- **Expenses** by category, **Capital** (investment / withdrawal), **Payments** (received / paid)
- Company name, currency and tax number in Settings
- Data saved in the browser (localStorage); backup and restore as JSON

## Run
Open `index.html`, or host it free with GitHub Pages (Settings > Pages > Deploy from branch `main`, folder `/root`).

## How the numbers work
- Profit = sales - cost of goods sold - expenses
- Cash = capital in - withdrawals + money received - money paid - expenses
- Customers owe you = sales - received at sale - payments received
- You owe suppliers = purchases - paid at purchase - payments paid

## Note
Data lives in each browser. Download a backup regularly. A shared multi-device backend can be added later.
