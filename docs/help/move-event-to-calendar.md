---
title: "Moving an event to another calendar"
meta_description: "How to move a Cloomba event to another calendar — who can move it, and what changes for its admins, payments, email allowances, and integrations."
section: "Calendars"
section_position: 50
position: 28
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

Every event has one home calendar. Moving the event changes that home: the event belongs to the new calendar, and the new calendar's settings apply to it from then on.

---

### How to move an event

1. Open the event, choose **Manage**, and find the **Calendar** card at the bottom of the **Overview**.
2. Select **Change calendar**.
3. Pick the new calendar. Before you confirm, the dialog lists what the move changes.
4. Select **Move**.

In the app, **Change calendar** is on the event's **More** tab.

The button is there when you have another calendar to move the event to. Picking **Personal calendar** puts the event on its organizer's personal calendar.

---

### Who can move it

The event's organizer can always move it. An event admin can move it when they also run the calendar it is on now. To move an event onto a team calendar, you need to be one of its owners or admins.

---

### What changes

- **Admins** — the new calendar's owners and admins become admins of the event. People whose admin role came with the old calendar lose it. Access someone was given by hand on the event itself stays. See [Calendar admins and ownership](/help/calendar-admins).
- **Payments** — from the next sale, the event is paid into the new calendar's default [payment account](/help/payment-accounts). If the event is still selling tickets by card and the new calendar has no default, the dialog asks you to pick one of its accounts — and if it has none, the move waits until its owners connect one. Tickets already sold stay on the account that took them, and so do their refunds.
- **Refund policy** — the new calendar's refund policy is shown below the description of a paid event. See [Issuing refunds](/help/refunds).
- **Email** — invitations and event updates count towards the new calendar's [email sending limits](/help/email-sending-limits).
- **People** — the event's guests count on the new calendar's **People** tab, and stop counting on the old one's.
- **API keys and webhooks** — those of the old calendar stop reaching the event, and the dialog lists them; those of the new calendar reach it.

The event's address, organizer, guests, tickets, photos, and comments stay as they are.

---

### When an event can't move

An event with members-only ticket types can't change its calendar: who counts as a member comes from its calendar's membership tiers. Remove that restriction from those ticket types first.
