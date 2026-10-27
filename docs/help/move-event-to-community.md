---
title: "Moving an event to another community"
meta_description: "How to move a Cloomba event to another community — who can move it, and what changes for its admins, payments, email allowances, and integrations."
section: "Communities"
section_position: 50
position: 28
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

Every event has one home. Moving the event changes that home: the event belongs to the new community, and the new community's settings apply to it from then on.

---

### How to move an event

1. Open the event, choose **Manage › Overview**, and find the **Community** card. The community row at the top of the Manage menu jumps to it.
2. Select **Change community**.
3. Pick the new community. Before you confirm, the dialog lists what the move changes.
4. Select **Move**.

In the app, open the event, tap **Manage**, and use **Change community** in the community card.

The button is there when you have another community to move the event to. Picking **Personal** puts the event on its organizer's personal calendar.

---

### Who can move it

The event's organizer can always move it. An event admin can move it when they also run the community it is in now. To move an event into a community, you need to be one of its owners or admins.

---

### What changes

- **Admins** — the new community's owners and admins become admins of the event. People whose admin role came with the old community lose it. Access someone was given by hand on the event itself stays. See [Community admins and ownership](/help/community-admins).
- **Payments** — from the next sale, the event is paid into the new community's default [payment account](/help/payment-accounts). If the event is still selling tickets by card and the new community has no default, the dialog asks you to pick one of its accounts — and if it has none, the move waits until its owners connect one. Tickets already sold stay on the account that took them, and so do their refunds.
- **Refund policy** — the new community's refund policy is shown below the description of a paid event. See [Issuing refunds](/help/refunds).
- **Email** — invitations and event updates count towards the new community's [email sending limits](/help/email-sending-limits).
- **People** — the event's guests count on the new community's **People** tab, and stop counting on the old one's.
- **API keys and webhooks** — those of the old community stop reaching the event, and the dialog lists them; those of the new community reach it.

The event's address, organizer, guests, tickets, photos, and comments stay as they are.

---

### When an event can't move

An event with members-only ticket types can't change its community: who counts as a member comes from its community's membership tiers. Remove that restriction from those ticket types first.
