---
title: "Tracking links"
meta_description: "Add ?utm_source= to the links you share and see in Reports how many visits and registrations each one brings."
section: "Tips & tricks"
section_position: 120
position: 56
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

Add a label to a link to your event, and Reports counts the visits and registrations that came through it. Give each place you share the event its own label — your newsletter, the QR code on a poster, an Instagram post — and you see which one brings people.

---

### Labelling a link

Add `?utm_source=` and a name of your choice to the end of your event link:

```
https://cloomba.com/e/your-event?utm_source=newsletter
https://cloomba.com/e/your-event?utm_source=poster
```

If the link already has a `?` in it, add `&utm_source=` instead.

A short link (**Share → Get short link**) takes a label the same way, and keeps it when it opens the event: `https://cloo.mba/abc123?utm_source=poster`. So does an invite link: `https://cloomba.com/s/abc123?utm_source=poster`.

Labels ignore capitals and spaces at either end — `Poster` and `poster` count as one. Short names you'll recognise later work best.

---

### Labels on embeds

On an embedded event or calendar, the label goes on the embed:

- **Inline card or calendar** — `utm_source=` in the `src` URL, e.g. `…/embed/e/your-event?utm_source=partner-site`
- **Registration button** — the `data-cloomba-utm-source="partner-site"` attribute

The snippets and the other options are in [Embed an event on your website](/help/embed-event) and [Embed your community calendar on your website](/help/embed-calendar).

---

### Reading the results

Open your event's **Manage → Reports**. Two tables show where your guests came from:

- **UTM** — for each label, its views, its guests, and guests as a share of views
- **Referrals** — the same numbers for each invite link, one row for each date you sent personal invitations with the number you sent beside it, and one row for each person whose shared link brought guests. Cloomba removes invitations about five weeks after an event ends, and their row goes with them

Guests who cancelled, were refunded or were rejected are not counted.

Each guest counts once. Someone who joins through an invite link counts under that link, even if it also carries a label. Otherwise they count under the label of the link they arrived through; if they opened several labelled links on the way, the last one counts.

Views count page loads, so a reload adds one and a visitor with an ad blocker adds none. Read them as a guide rather than an exact count.

The period you pick at the top of Reports, from **Past 24 hours** to **Lifetime**, applies to **UTM**. **Referrals** always shows **Lifetime**.

Printed tickets carry a label of their own: the event code at the bottom of a printed ticket opens your event with `utm_source=printed-ticket`, so it shows under **UTM** beside your labels.

The **Manage → Reports** of a community or personal calendar shows the same numbers for all the events whose home it is. Its owners and admins can open it.

Both tables are part of the [Pro plan](/info/pricing).
