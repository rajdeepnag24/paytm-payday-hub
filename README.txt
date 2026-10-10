Payday Hub — Vercel prototype package
====================================

Contents
- index.html: self-contained interactive prototype. No build step or npm dependencies.
- README.txt: this file.

Update the existing Vercel project
1. Keep the existing Vercel project; do not create a new project if you want to retain its domain.
2. In Vercel, open the project that owns https://payday-hub-vercel.vercel.app/.
3. If the project supports uploading/redeploying files, replace its deployed source with the contents of this ZIP and redeploy that same project. If the dashboard only offers creating a new deployment from a folder, ensure it is attached to the existing project before deploying; do not use a fresh project.
4. Verify the existing URL after deployment on mobile and desktop. If Vercel's upload flow cannot update an existing project, use the project's Deployments / Settings workflow or connect the same project to a Git repository for stable repeat deployments.

Design pass
- Home is aligned to the provided Paytm screenshot: pale grey background, RN avatar, Paytm + UPI wordmark treatment, four navy circular shortcuts, Recharge & Bills ordering, reward strip, offer tiles and service chips.
- Profile/settings now follows the screenshot's tall white settings sheet and list rows. Payday Hub remains a menu item, not a home card. No bottom navigation is added.
- Floating compact “Simulate SMS · DEMO” button retains its glow.

Prototype scope / safety
- All user and transaction data are fictional.
- SMS is simulated; no SMS, bank, Account Aggregator or Paytm services are connected.
- Payment screens are demonstrations only; no money moves and no UPI PIN is requested.
- Search, profile, recharge and some service controls are visual placeholders.
- This is an independent concept prototype, not an official Paytm product.
