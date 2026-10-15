---
title: "Payment accounts"
meta_description: "How payment accounts work on Cloomba — each calendar's own Stripe accounts, its default, choosing one per event, and where refunds go."
section: "Tickets & payments"
section_position: 40
position: 45
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

A payment account is a Stripe account connected to Cloomba. Every payment account belongs to a calendar — your personal calendar, or a team calendar. Card payments for an event go into one of its calendar's accounts, and membership payments into the calendar's default account.

A calendar can have more than one account — for a club and a company, or for each bank account you want money in — and each event on it can be paid into a different one.

---

### Where the money goes

- **An event** is paid into the account chosen for it, which is always one of its calendar's accounts. If none is chosen, it uses the calendar's **default** account at the moment of each sale.
- **A calendar's memberships** are paid into the calendar's default account.

The account's holder is the seller: the payout, the Stripe receipts, refunds and disputes all belong to that account.

---

### Adding an account

- **Your personal calendar:** on cloomba.com, open **Calendars** in the top bar, select **Personal calendar** — the first card under **Your calendars** — and open its **Payments** tab.
- **A team calendar:** open the calendar's **Manage** page and its **Payments** tab. The calendar's owners add and manage its accounts; its admins can see them.

Select **Connect Stripe** for the first account, or **Add** for another one, and finish Stripe's onboarding — your business details and a bank account. A calendar's first account becomes its default. A calendar can have up to 10, set up one at a time: while one is unfinished, its row shows **Continue setup** in place of **Add**.

Select an account's row to give it a name you will recognise or make it the default. An account becomes the default once it is ready to take payments. **Manage on Stripe** opens the Stripe dashboard for the person who connected the account — Stripe sends its login code to them.

---

### Choosing the account for an event

Open **Manage → Registration → Getting paid** on a paid event and pick one under **Payment account**. The list shows the accounts of the event's calendar, the default marked **(Default)**. An account still in onboarding is shown as **Onboarding incomplete** and can be picked once it is ready. The calendar's owners and admins choose; the organizer is notified when someone else makes the change. When the calendar has only one account, its name is shown in place of the list.

The choice applies from the next sale. Tickets already sold stay on the account that took them. An event moved to another calendar is paid into that calendar's accounts from then on — see [Moving an event to another calendar](/help/move-event-to-calendar).

---

### A calendar's default

The calendar's owners choose its default. Members who pay by subscription stay on the account they subscribed through, so the default can't change while any of their subscriptions run. It can change again once the last one has ended.

A calendar keeps its accounts and its default when its owners change.

---

### Refunds and past sales

A refund always goes back through the account that took the payment — also after the event switched accounts or moved to another calendar. Switching an account moves future sales only. See [Issuing refunds](/help/refunds).

---

### Questions

**Can two events on the same calendar be paid into different accounts?**
Yes. Connect both accounts to the calendar and choose one on each event.

**I run a club and a company. How do I keep the money apart?**
Give each its own calendar with its own account, or connect both accounts to one calendar and choose the right one on each event.

**My co-organizer should receive the money for our event. How?**
Put the event on a calendar where their account is connected — a team calendar they own.

**What happens to tickets already sold when I switch accounts?**
They stay on the account that took them, and so do their refunds.

**Why can't I change my calendar's default?**
Members pay into it by subscription. It can change again once the last subscription has ended.

**Do extra accounts cost anything?**
No. Adding an account is free, and the fee on each sale is the one described in [How Cloomba fees work](/help/pricing-fees).
