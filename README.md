# MoneyFlow PWA

A Persian RTL personal finance tracker and installable Progressive Web App.

## Live demo
https://khandanian.github.io/moneyflow-pwa/

## Features
- Add, edit, and delete income and expense transactions
- Categories, search, type and month filters
- Monthly budget, category breakdown, and six-month chart
- CSV export compatible with Excel
- Browser-local storage and offline support after the first visit
- Responsive, installable PWA with no backend

## Important limitations
This is a portfolio demonstration, not a banking or accounting service. It does not connect to bank accounts or sync across devices. Data may be lost if browser storage is cleared. Export CSV for backups. Amounts are in Iranian toman; input dates use the Gregorian calendar.

## Local development
Run `python -m http.server 8080` and open http://localhost:8080.

## GitHub Pages
Enable **Settings → Pages → Source: GitHub Actions** once, manually. The deployment workflow in `.github/workflows/deploy.yml` deploys pushes to main and does not attempt to create the Pages site with the restricted Actions token.
