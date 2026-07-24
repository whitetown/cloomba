---
title: "Customising RSVP emails"
meta_description: "How to customise the approved- and declined-RSVP emails Cloomba sends to your guests, with placeholder variables for personalisation."
section: null
section_position: 0
position: 57
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

For events that use **Require approval**, Cloomba sends an automatic email to each guest when you approve or decline their request. You can override the default text with your own per-event template.

---

### What you can customise

Two templates per event:

- **Approved** — sent when you approve a pending RSVP
- **Declined** — sent when you decline a pending RSVP

The defaults are short and friendly. Customise them when you want a specific voice, to add practical details ("door opens at 18:30, ring bell #4"), or to soften a decline with context.

---

### Variables

Templates support a handful of placeholders that get filled in per recipient:

- `{{guest_name}}` — the guest's display name
- `{{event_title}}` — your event's title
- `{{event_url}}` — direct link back to the event page
- `{{event_date}}` — formatted event date
- additional event-specific tokens shown in the editor

Drop them into the body and Cloomba substitutes the real values when sending.

---

### Sending a test

The editor has a **Send test** button — it sends the current draft to your own email address so you can preview the rendering before saving.

---

### Resetting to default

If you change your mind, the **Reset to default** button restores Cloomba's stock copy for that template.

---

### Other emails

The transactional emails Cloomba sends for reminders, ticket confirmations, and waitlist alerts are not customisable per event today — they use platform defaults. See [Email reminders & alerts](/help/email-notifications).
