# Product notes

## Problem hypothesis

Recurring obligations are easy to forget when they are scattered across messages, mental notes, and payment apps. A useful planning experience should make upcoming commitments visible and offer a clear next step without making the user manage a complicated system.

This is a product hypothesis explored by a prototype, not a validated research finding.

## Core user journey

1. **Discover:** enter Payday Hub from the home screen.
2. **Understand:** review monthly obligations and what is coming due soon.
3. **Narrow:** filter by amount range or due day.
4. **Choose an action:** pay through the simulated payment flow or choose a reminder date and time.
5. **Review:** confirm a fictional detected payment before adding or matching it to the plan.

## Product principles

- Keep the core path short and mobile-first.
- Use familiar Paytm-inspired blue/white styling, compact cards, and restrained decoration.
- Keep payment actions explicit; a reminder should not be confused with a payment.
- Ask for confirmation before adding a detected payment.
- Be clear that this is a prototype and does not access messages or move money.

## Scope boundaries

### Included in this prototype
- Illustrative monthly obligations and income sources.
- Amount and due-day filters.
- Monthly and near-term payment breakdowns.
- A fictional detected-rent review flow.
- Simulated Paytm payment journey.
- Date/time reminder scheduling interaction.

### Not implemented
- Real payment processing or UPI integration.
- Reading SMS, email, bank data, or account-aggregator feeds.
- Push/local notifications or background scheduling.
- Persistent storage, user accounts, backend APIs, or multi-device sync.
- Production-grade analytics or validated financial calculations.

## Design rationale

The main experience prioritizes the next useful decision: understand the obligation, then choose to pay or set a reminder. Filters are intentionally limited to amount and date to avoid turning a lightweight payment list into a complex reporting interface.

## Success criteria for a future usability test

- Participants can locate their planned obligations without help.
- Participants can filter to a relevant amount/date range.
- Participants understand the difference between “Pay now” and “Remind me to pay.”
- Participants understand that the payment and reminder flows are simulated.
- Participants can explain what will happen after each primary action.

These are proposed test criteria, not measured results.
