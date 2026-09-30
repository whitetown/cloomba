---
title: "Payment accounts"
meta_description: "How payment accounts work on Cloomba — several Stripe accounts, choosing one per event, sharing an account with a co-organizer, and where refunds go."
section: "Tickets & payments"
section_position: 40
position: 45
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

A payment account is a Stripe account connected to Cloomba. Card payments for your tickets and memberships go into it. With one account, every paid event you organize uses it automatically.

You can connect more than one — for a club and a company, or for each bank account you want money in — and choose which one each event is paid into. Organizers who run events together on one calendar each keep their own money.

---

### Where the money goes

- **An event** is paid into the account chosen for it. If none is chosen, it uses its organizer's **default** account at the moment of each sale — change your default, and those events follow it.
- **A calendar's memberships** are paid into the calendar's account, which is always one of the calendar owner's own accounts.

The account's holder is the seller: the payout, the Stripe receipts, refunds and disputes all belong to that account.

---

### Adding an account

1. On cloomba.com, open **Account** from the navigation and find **Payment accounts**.
2. Select **Connect Stripe** for your first account, or **Add** for another one.
3. Finish Stripe's onboarding — your business details and a bank account.

Your first account becomes your default. You can have up to 10, set up one at a time: while one is unfinished, its row shows **Continue setup** in place of **Add**.

Select an account's row to give it a name you will recognise, make it your default, or open it with **Manage on Stripe**. An account becomes your default once it is ready to take payments.

---

### Choosing the account for an event

Open **Manage → Registration → Getting paid** on a paid event and pick one under **Payment account**. The list shows your own accounts — your default marked **(Default)** — and the accounts shared with you. An account still in onboarding is shown as **Onboarding incomplete** and can be picked once it is ready.

The choice applies from the next sale. Tickets already sold stay on the account that took them.

---

### Choosing the account for a calendar

On the calendar's **Manage** page, the **Payments** tab shows the account its membership payments go to. The owner picks one of their own accounts.

Members who pay by subscription stay on the account they subscribed through, so the account can't change while any of their subscriptions run. It can change again once the last one has ended. The first member who subscribes also fixes the calendar to the account they paid into, so a later change of your default leaves the calendar where it is.

---

### Sharing an account

You can let someone else sell into one of your accounts — a co-organizer, or someone running their first paid event before they have a Stripe account of their own.

1. Under **Payment accounts**, select the account's row.
2. Under **Shared with**, enter their Cloomba username and select **Share**.

They are notified, and from then on they can choose the account on the events they organize. The account stays yours: its name, its default setting and its Stripe dashboard are yours alone. You can share one account with up to 20 people, and the row shows which events use it.

You are the seller for everything sold through your account. The payouts come to you, and so do the refunds and disputes for those sales.

To stop, select **Remove** next to their name. The events of theirs that used the account go back to their own default account, and they are notified. Sales already made stay on your account, with their refunds.

---

### Admins and payment accounts

An event admin can change the event's account too: to the organizer's default account, or to one of the organizer's accounts shared with them. A calendar admin can do the same on the calendar's **Payments** tab, with the owner's accounts shared with them. The organizer or calendar owner is notified when an admin makes the change. See [Adding co-hosts and managers](/help/cohosts).

---

### Refunds and past sales

A refund always goes back through the account that took the payment — also after the event switched accounts or the account was unshared. Switching an account moves future sales only. See [Issuing refunds](/help/refunds).

---

### Questions

**Is my Stripe account tied to my calendar?**
No. Each event chooses its own account; a calendar's account is used only for its memberships. Events from several organizers can sit on one calendar, each paid into its own organizer's account.

**Can two events on the same calendar be paid into different accounts?**
Yes. That is the usual case when several people organize on one calendar.

**I run a club and a company. How do I keep the money apart?**
Connect an account for each and choose the right one on each event. Make the one you use most your default, so new events start there.

**My co-organizer should receive the money for our event. How?**
Either they organize the event, or they share their account with you and you choose it on the event.

**Can I sell tickets before I have my own Stripe account?**
Yes, when someone shares their account with you. Choose it on your event, and the money goes to them as the seller. Once your own account is ready, switch the event to it — sales from then on come to you.

**What happens to tickets already sold when I switch accounts?**
They stay on the account that took them, and so do their refunds.

**Why can't I change my calendar's account?**
Members pay into it by subscription. The account can change again once the last subscription has ended.

**Do extra accounts cost anything?**
No. Adding an account is free, and the fee on each sale is the one described in [How Cloomba fees work](/help/pricing-fees).
