---
title: "Ticket types and how you price them"
meta_description: "How ticket types work on Cloomba — several types on one event, per-type capacity and sales windows, and the three ways to price one: fixed, on request, or pay what you want."
section: "Tickets & payments"
section_position: 40
position: 15
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

An event can carry more than one ticket type — early bird and general admission, member and non-member, a free slot alongside a paid one. Each type has its own price, its own capacity and its own sales window. You will find them under **Manage → Registration → Tickets**.

---

### Adding a ticket type

Every event has at least one ticket type; it is created for you when you set the event up. Add more from the **Tickets** panel. Each type has:

- **Ticket name** — what guests choose from at checkout
- **Price** — an amount and a currency, plus how that amount behaves (see below)
- **Limit capacity** — an optional cap on this type alone
- **Sales start** and **Sales end** — an optional window; see [Closing registration before the event](/help/registration-deadline)
- **Require a coupon code** — the type still appears on the event page, but only guests holding a coupon linked to it can take it. Guests without the code see **Enter code to unlock**

Drag to reorder — the order in the panel is the order guests see. Removing a type does not affect people who already hold it, and an event always keeps at least one.

---

### Fixed price

The ordinary case. Set the amount and the currency; guests see it and pay it. Leave it at 0 for a free ticket.

---

### Price on request

The price is hidden, not absent. Guests see **On request** where the amount would be, and the ticket stays selectable — the model is that they register first and settle the number with you, rather than filling in an enquiry form and waiting.

There are two shapes, depending on whether you set an amount:

**You set a price.** The guest is charged exactly that at checkout. They see the amount on the payment step, just not on the event page or in listings. Use this when the figure is negotiated per guest and you would rather not advertise it.

**You leave the price at 0.** Available only when you are [collecting payment outside Cloomba](/help/off-platform-payment). The registration holds at **Pending payment** — no ticket and no QR code are issued — until you agree an amount and record it on the guest list. Use this when the price genuinely depends on dates, numbers, or what the guest asks for.

A card-paid event cannot have an on-request ticket at 0, because there would be nothing to charge. Set an amount, or switch the event to off-platform payment.

On-request types are left out of the "from €X" figure shown on event cards and in listings, so a hidden price never leaks out through the cheapest-ticket line.

---

### Pay what you want

The guest chooses the amount. The price you set is the **minimum**, not the price — there is no maximum and no separate suggested figure. Checkout opens pre-filled at your minimum, and the guest can raise it.

Set the minimum to 0 and the ticket is free with support optional. A guest who leaves it at 0 registers on the ordinary free path, with no card involved at all; a guest who types an amount pays it. Fees follow the amount actually paid, so a guest who pays nothing costs you nothing — see [How Cloomba fees work](/help/pricing-fees).

Two limits are worth knowing before you use it:

- **Coupons do not apply.** A discount off an amount the guest picks themselves does not mean anything, so the coupon field is hidden on a pay-what-you-want ticket. See [Discount coupons for paid events](/help/coupons).
- **The mobile apps have not caught up yet.** Someone registering from the iOS or Android app sees the ticket at your minimum and pays that. Only the website offers the choice for now.

---

### Capacity across several types

The event's own **Capacity** field is the total for the whole event, and it holds no matter how many types you add. Each type's **Limit capacity** then caps that one type within the total; a type without its own limit shares whatever remains of it.

So a capacity of 50 with an early-bird type limited to 10 sells at most 10 early-bird and at most 50 overall. See [Using the waitlist](/help/waitlist) for what happens when the event fills up.

---

### What guests see

With more than one type, checkout lists them and the guest picks one. A type outside its sales window is shown with the reason — **On sale from** with the date, or **Sales ended** — and cannot be chosen. A type that needs a code shows **Enter code to unlock** until the code is entered.
