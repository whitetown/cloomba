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

A short link (**Share → Get short link**) takes a label the same way, and keeps it when it opens the event: `https://cloo.mba/abc123?utm_source=poster`.

Labels ignore capitals and spaces at either end — `Poster` and `poster` count as one. Short names you'll recognise later work best.

---

### Labels on embeds

On an embedded event or calendar, the label goes on the embed:

- **Inline card or calendar** — `utm_source=` in the `src` URL, e.g. `…/embed/e/your-event?utm_source=partner-site`
- **Registration button** — the `data-cloomba-utm-source="partner-site"` attribute

The snippets and the other options are in [Embed an event on your website](/help/embed-event) and [Embed your community calendar on your website](/help/embed-calendar).

---

### Reading the results

Open your event's **Manage → Reports**. Two cards show your labels:

- **UTM sources** — how many visitors arrived through each label
- **Registrations by source** — how many people registered through each label, and how many of them are confirmed

A registration counts under the label of the link the guest arrived through; if they opened several labelled links on the way, the last one counts. The period you pick at the top of Reports, from **Past 24 hours** to **Lifetime**, applies to both cards.

The **Manage → Reports** of a community or personal calendar shows the same two cards for all the events whose home it is. Its owners and admins can open it.

Both cards are part of the [Pro plan](/info/pricing).
