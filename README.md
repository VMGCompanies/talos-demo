# Talus Technologies — platform preview

Live preview: **https://vmgcompanies.github.io/talus-demo/**

A labor margin platform for commercial janitorial contractors. This repository
holds the compiled preview build only; the application source is private.

The preview runs entirely in the browser against a deterministic seeded dataset
(Sentinel Building Services — a fictional 42-building, 380-cleaner contractor in
Texas). No real data, no backend, no third-party writes.

## What is built so far

| Area | Status |
|---|---|
| Design system, rail + flyout navigation, command palette | Complete |
| Data layer — full schema, seeded ledger, burden engine (SUTA / NCCI 9014 / EMR) | Complete |
| Drill framework and Explain This Number lineage | Complete |
| Time and Attendance, field app, checkpoints, Live Coverage | Complete |
| Workloading, standards library (ISSA 612 + own actuals), Scheduling, Labor Variance | Complete |
| Payroll Guard — exception queue, period close, payroll exports | Complete |
| Site Survey to Bid to Proposal to Account P&L with bid-to-actual bridge | Complete |
| Forecast and Simulation — wage shock, turnover cost, overtime, reprice | Complete |
| Subcontractors and COI, supplies and cost capture | In progress |
| Quality, client portal, credentials | In progress |
| Insights, audit, admin, integrations, developer API | In progress |

## Notes for reviewers

- Start on the Command Center; every figure is clickable, and the small info
  icon on any number opens its full calculation lineage.
- The demo user, entitlement tier, language and theme all switch from the user
  menu at the bottom of the left rail.
- Nothing persists to a server. Reload restores the seeded state.
