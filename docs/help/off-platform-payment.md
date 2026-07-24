---
title: "Off-platform payment for paid events"
meta_description: "How Cloomba's off-platform payment mode works — collect ticket money via bank transfer, PayPal, or cash and confirm guests manually."
section: null
section_position: 0
position: 35
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

Cloomba supports a second mode for paid events: you collect the money yourself, off platform, and confirm guests manually once you've been paid. Useful when Stripe Connect isn't an option, or when you want to handle bank transfers / PayPal / cash directly with attendees.

---

### When to use off-platform payment

- You already have an established way to take money (a club bank account, a community PayPal, in-person cash on the door)
- You're not ready to go through Stripe Connect onboarding
- Your event is small enough that manually marking a handful of guests as paid is fine

If you're running paid events regularly or at any real scale, **Stripe checkout** is still the cleaner option — see [Setting up paid tickets](/help/paid-tickets).

---

### How it works

When you switch the event to **Paid → Off-platform**, you fill in two fields:

- **Payment URL** — optional. A link attendees should follow to pay you (e.g. a PayPal.me link or a hosted invoice page).
- **Payment instructions** — free text explaining what to do. Bank account number, payment reference, deadline, anything attendees need.

A new RSVP lands in **Pending payment** instead of being confirmed. The attendee sees your payment instructions on the RSVP screen and pays you outside Cloomba.

Once the money arrives, you mark the guest as paid from the guest list. Their status flips to **Confirmed** (or to **Waitlist** if the event is full by then).

---

### Mutual exclusivity with Stripe

Off-platform payment and Stripe paid mode are mutually exclusive on the same event — pick one. You can switch modes before the first RSVP is taken; switching after that gets messy and is best avoided.

---

### What Cloomba does and doesn't store

Cloomba never sees the money. There's no amount on the ticket type and no payout. The price lives only in your instructions text. Refunds, receipts, and any tax handling are entirely between you and the attendee.

---

### Examples of clear instructions

> Pay €12 to **IBAN SK00 0000 ...** with **reference "JS-15 + your name"**. I'll confirm your spot within 24 hours of receiving the transfer. Cancellation deadline: Friday 12:00.

> €5 cash on the door — no advance payment, just RSVP here so I know to expect you.

Use short, exact instructions. Vague ones lead to support questions you'll have to answer in DMs (which Cloomba doesn't have yet — see [How to contact the event organiser](/help/contact-organizer)).
