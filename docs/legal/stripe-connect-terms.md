---
title: "Stripe Connect Terms for Paid Organisers"
meta_description: "A plain-language summary of the Stripe Connected Account Agreement that paid-event organisers accept when they connect a Stripe account to Cloomba."
section: null
section_position: 0
position: 70
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

When you set up paid ticketing on Cloomba, you connect a **Stripe** account via Stripe Connect. Stripe — not Cloomba — is the payment processor and the contracting party for the funds you take in.

This page summarises what that means in practice. The authoritative documents are Stripe's, linked below.

---

### Who's who

- **You (organiser)** — the seller of the ticket. The merchant of record.
- **Stripe** — the payment processor. Holds funds, runs card networks, transfers payouts to your bank account.
- **Cloomba (WhiteTown s.r.o.)** — the platform you use to run the event and the storefront for the ticket. Charges a 5% platform fee. NOT the merchant of record.

---

### What you accept when you connect Stripe

During Stripe onboarding (the first time you set up a paid event), you accept:

- **Stripe Services Agreement** — Stripe's general terms.
- **Stripe Connected Account Agreement** — the terms that apply specifically to Connect accounts like yours.

Read them in full on Stripe's site:

- [Stripe Connected Account Agreement](https://stripe.com/legal/connect-account)
- [Stripe Services Agreement](https://stripe.com/legal/ssa)

---

### Practical implications

- **Refunds** are issued through your Stripe dashboard. See [Issuing refunds](/help/refunds).
- **Disputes / chargebacks** flow through Stripe. You'll receive notifications and have a chance to submit evidence.
- **VAT and tax** on ticket sales are your responsibility as merchant of record. See [Taxes and VAT for EU organisers](/help/taxes-vat).
- **Payout schedules** are set by Stripe — typically 2–7 business days. See [Getting paid — how payouts work](/help/payouts).
- **Account holds or closures** by Stripe (e.g. for KYC, suspected fraud) freeze your payouts until resolved. Cloomba can't override Stripe decisions; contact Stripe support.

---

### Cloomba's 5% platform fee

Cloomba's 5% fee is collected from each successful sale via Stripe's `application_fee_amount` mechanism — you don't pay it separately, it's just deducted from your gross before payout.

If you later refund the ticket, Cloomba **refunds this fee too** — a full refund costs you nothing on our side.

---

### Disconnecting Stripe

You can disconnect your Stripe account from Cloomba at any time. Pending payouts continue per Stripe's schedule. Without a connected Stripe account you can't publish new paid events, but your existing event pages remain intact.

---

### Contact

For Stripe-side questions, use [Stripe Support](https://support.stripe.com).
For Cloomba-side questions, [contact us](/info/contact).
