# PharmaCare — Pharmacy Management Demo

A single-file pharmacy inventory and sales interface: stock with live status (OK / low / expiring), one-click selling, expiry tracking, supplier balances, and an add-medicine form. No dependencies, no backend.

![Stack](https://img.shields.io/badge/stack-vanilla%20JS-c8f542) ![Deps](https://img.shields.io/badge/dependencies-0-c8f542)

## Features

- **Inventory table** — search across name, category and supplier; filters for low stock and expiring within 60 days
- **Sell flow** — one click decrements stock and counts the day's sales; empty stock locks the button
- **Expiry tracking** — days-to-expiry per row plus an expiring counter in the header
- **Header stats** — total stock value, low-stock count, expiring count, units sold today
- **Suppliers panel** — contact, outstanding balance and payment terms per supplier
- **Add medicine** — validated form (name, price and expiry required)

## Run it

```bash
open index.html
```

Demo data only. The production version of a system like this pairs the interface with a Laravel/MySQL backend and offline-first sync for pharmacies with unstable connectivity.

---

*Demo project by [Jameel Ali](https://github.com/jalidev).*
