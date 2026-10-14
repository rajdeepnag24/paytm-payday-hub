# Payday Hub — Paytm-inspired collections & payment-planning prototype

A mobile-first, interactive product concept exploring how people can plan recurring obligations, review payment reminders, and move from **“I need to pay this”** to a clear next action.

**Live prototype:** https://payday-hub-vercel.vercel.app/  
**Repository:** https://github.com/rajdeepnag24/paytm-payday-hub

> **Disclaimer:** This is an independent concept prototype for portfolio and product-design exploration. It is not an official Paytm product and is not affiliated with or endorsed by Paytm. All names, balances, transactions, and messages are illustrative. No real payments, SMS reading, or push notifications occur.

## Product idea

People often remember a payment only when it is nearly due. Payday Hub explores a single place to see recurring obligations, understand what is coming up, and choose how to act: pay through a simulated flow or schedule a reminder for a time that suits them.

The experience follows Paytm-inspired blue-and-white visual cues while keeping the interface compact, familiar, and action-oriented.

## What you can explore

- **Payday Hub overview:** monthly obligations, upcoming payments, and a monthly-income summary.
- **Payment list and filters:** narrow planned payments by minimum/maximum amount and due-day range.
- **Payment breakdowns:** inspect the monthly plan or near-term obligations.
- **Detected-payment review:** review a fictional rent message before adding or matching it to the plan.
- **Pay now:** follow a sample payment journey, including a simulated success and tagging step.
- **Flexible reminders:** choose a date and time for a payment reminder in the review flow.
- **Income and insights screens:** explore illustrative income sources and spending summaries.

## Try it locally

There is no build step, package manager, or third-party dependency.

1. Clone or download this repository.
2. Open index.html in a modern browser.

To serve it locally, run this from the repository directory:

    python -m http.server 8000

Then open http://localhost:8000.

## Project structure

    .
    ├── index.html                 # Self-contained HTML, CSS, and JavaScript prototype
    ├── docs/
    │   ├── PRODUCT_NOTES.md       # Product intent, flows, and design constraints
    │   └── QA_CHECKLIST.md        # Manual smoke-test checklist
    └── CHANGELOG.md               # High-level changes

## Implementation notes

- Plain HTML, CSS, and vanilla JavaScript in one page; screens are switched client-side.
- Prototype data lives in in-memory JavaScript state and resets on reload.
- No backend, database, authentication, payment gateway, SMS permission, or notification service is connected.
- The “schedule reminder” action currently confirms a chosen date/time in the UI only. It does not register an operating-system notification or persist the schedule.
- The QR and payment success screens are simulated. Do not enter real payment credentials or treat the UI as a payment service.

## Current limitations

- Data is fictional and seeded for demonstration.
- Reminder schedules and other state are not persisted across refreshes.
- Some non-core Paytm-style controls are visual placeholders.
- Amount/date filters use the prototype's planned amount and day-of-month fields, not a full transaction ledger or calendar engine.
- Browser and device coverage has not been exhaustively tested; use the checklist in docs/QA_CHECKLIST.md before presenting a new build.

## Suggested review path

1. Open the live prototype and enter Payday Hub.
2. Review the planned payments and try amount/date filters.
3. Open the simulated SMS review.
4. Expand **Remind me to pay**, choose a date and time, and schedule it.
5. Try **Pay now** to see the sample payment flow.

## License

No open-source license has been added. Unless a license is added, standard copyright rules apply; contact the repository owner for reuse permission.
