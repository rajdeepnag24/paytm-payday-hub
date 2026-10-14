# Manual QA checklist

Run these checks after editing the prototype and before sharing it in a portfolio. Test in a current desktop browser and at a narrow mobile viewport.

## Navigation and layout
- [ ] Home screen loads without console errors.
- [ ] Payday Hub opens from the home entry point.
- [ ] Back actions return to the expected screen.
- [ ] Cards, buttons, and text remain readable at mobile width.
- [ ] No horizontal overflow or overlapping controls.

## Planned payments
- [ ] View payments shows monthly obligations and due-this-week summary.
- [ ] Minimum and maximum amount filters work independently and together.
- [ ] Due-day-from and due-day-to filters work independently and together.
- [ ] Reset clears all four filter fields.
- [ ] Empty filter results show a useful empty state.
- [ ] Pay actions open the simulated payment flow for the selected obligation.

## Detected-payment review
- [ ] Simulated SMS entry opens the review flow.
- [ ] Nothing is added before the user confirms.
- [ ] “Confirm & add to plan” adds or matches the illustrative rent obligation.
- [ ] “Remind me to pay” expands the scheduler.
- [ ] A user can choose a date and time and receive an in-app confirmation.
- [ ] The UI does not imply that a real push notification has been registered.
- [ ] “Pay now” opens the sample payment journey with the rent amount.
- [ ] Payment success is clearly labeled as simulated.

## Safety and honesty
- [ ] No real credentials or UPI PIN are requested.
- [ ] Copy does not imply that SMS is being read.
- [ ] Copy does not imply that real money moves.
- [ ] Reminder behavior is described as prototype-only.
- [ ] Independent-concept disclaimer is visible in the README.

## Before a portfolio presentation
- [ ] Open the deployed URL in a private/incognito window.
- [ ] Confirm the deployed build reflects the latest commit.
- [ ] Capture fresh screenshots only after verifying the UI.
- [ ] Describe features as prototype interactions, not production integrations.
