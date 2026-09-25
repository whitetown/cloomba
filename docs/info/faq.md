---
title: "Frequently asked questions"
meta_description: "Short answers to the questions organizers ask most about Cloomba — what it costs, how registration and deadlines work, coupons, waitlists, guest data and the API."
section: "Product"
section_position: 0
position: 20
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

## Pricing and payments

### Is Cloomba really free?

For free events, yes — at any scale, with no listing fee, no per-guest charge and no subscription. You only pay when you sell tickets: 5% plus card processing, taken out of your payout. Fair-use limits apply to photos, videos, monthly emails, team seats and calendars, set so a normal event never reaches them. See [Pricing & Fees](/info/pricing).

### Do guests pay the fee on top of my ticket price?

No. Guests pay exactly the price you set, and the fee comes out of your payout — nothing is added at checkout. Your event editor shows the exact net amount for your price and currency before you publish. See [How Cloomba fees work](/help/pricing-fees).

### Can guests pay what they want, or add a donation?

Yes. Set a ticket type to **Pay what you want** and the price you enter becomes the minimum rather than the price — checkout opens there and the guest can raise it. Set the minimum to 0 and the event is free with support optional: paying nothing takes the ordinary free path with no card at all. See [Ticket types and how you price them](/help/ticket-types).

### Can I hide the price and agree it privately?

Yes — set the ticket to **Price on request**. Guests see "On request" instead of a number and register as normal; you settle the amount with them. If you have set a price they are charged it at the payment step; if you leave it at 0 on an [off-platform event](/help/off-platform-payment), their place holds as pending until you record what was agreed. See [Ticket types and how you price them](/help/ticket-types).

### Can I take cash or a bank transfer instead of card payments?

Yes. Switch the event to off-platform payment, write your instructions, and confirm guests yourself as the money arrives. Cloomba never sees the payment, so there is no fee and no payout — and refunds and receipts are between you and the guest. See [Off-platform payment](/help/off-platform-payment).

### When do I get paid, and what does a refund cost me?

Stripe pays out to your bank on its normal schedule, typically 2–7 business days after the event ([Getting paid](/help/payouts)). Refunds return the full ticket price to the guest and Cloomba returns its 5% too — you do not pay us to refund someone ([Issuing refunds](/help/refunds)).

## Sign-ups and deadlines

### Can I stop taking sign-ups before the event starts?

Yes — set **Sales end** on your ticket types. Registration closes when every type is past its own deadline, so staged pricing still works: early bird can close while general admission stays open. Guests then see "Registration has closed for this event" and no Join button. See [Closing registration before the event](/help/registration-deadline).

### Can I still let one person in after the deadline?

Yes. An invitation you send **after** the deadline works — you decided to open the door for that person. One sent before the deadline shares it and expires with it. To reopen the event for everyone, extend or clear **Sales end** instead. See [Inviting guests](/help/invite-guests).

### What happens when my event fills up?

New registrations go to the waitlist automatically, and when somebody cancels the next person in line is confirmed without you doing anything. The event-level Capacity field is the total for the whole event; each ticket type's own limit rations that type within it. See [Using the waitlist](/help/waitlist).

### Can I vet guests before confirming them?

Yes. Turn on approval and registrations land in a pending queue for you to approve or decline; guests are emailed either way. It works on paid events too — approved guests then go through to payment, so you never take money from someone you were going to turn down. See [Manual guest approval](/help/guest-approval).

### Can I ask people questions when they register?

Yes — add your own questions to the registration form: short text, long text, choices, website, company, job title and more, each required or optional. Answers land on your guest list and in the CSV export. See [Collecting info from guests](/help/guest-questions).

### Do guests need an account to register?

Yes, and signing in is passwordless — Google, Apple, GitHub, or an email link. That is what lets someone manage their own registration, keep their ticket, and get event updates without you fielding it by hand. See [How to sign in](/help/sign-in).

## Guests and the door

### Can I give discounts or comp tickets?

Yes — create coupon codes with a flat or percentage discount, an optional usage cap and an optional expiry. A code that takes the price to zero is a comp. Coupons do not apply to pay-what-you-want tickets, where the guest already picks the amount. See [Discount coupons](/help/coupons).

### How does check-in work at the door?

Scan each guest's QR code with your phone, or look them up by name — no extra hardware and no charge. Several people can check in at once and the list stays in sync. See [Checking in guests](/help/check-in).

### Can I take my guest list with me?

Yes, any time — one click gives you a CSV with names, answers to your questions and who checked in. It is your list, and the export works the same on the way out as on the way in. See [Exporting your guest list](/help/guest-list-export).

## Your data and your own site

### Is there an API?

Yes. The public API covers events, guests and check-in, authenticated with a key you generate yourself. Reads are free; writes need a Pro plan. Full reference and examples are at [cloomba.com/developers](/developers).

### Can I put my event or calendar on my own website?

Yes — both embed as an iframe you paste into your site, and they stay in sync on their own. See [Embed an event](/help/embed-event) and [Embed your calendar](/help/embed-calendar).

### Where is my data stored?

In the EU. Events, guests, photos and messages live on EU infrastructure, and you can export or delete everything yourself without asking us. See [GDPR & your rights](/legal/gdpr).

Still stuck? [Write to us](/info/contact) — a person reads it.
