---
title: "Embed your calendar on your website"
meta_description: "Drop your Cloomba calendar onto your own site with a single snippet — it auto-resizes and stays in sync with your events."
section: "Embedding"
section_position: 65
position: 10
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

You can embed any of your Cloomba calendars on your own website. Visitors see your upcoming events in a clean, self-updating widget — no account needed to browse.

Grab the ready-made snippet from your calendar's **Manage → Embed** section, or build it yourself from the examples below.

---

### The snippet

Paste this where you want the calendar to appear. Replace `your-calendar` with your calendar's address (the part after `/c/` in its URL).

```html
<iframe
  class="cloomba-embed"
  src="https://cloomba.com/embed/c/your-calendar"
  style="width: 100%; height: 800px; border: none"
  loading="lazy"
  title="My calendar"
></iframe>
<script src="https://cloomba.com/embed/embed.js" async></script>
```

The `embed.js` script makes the calendar **resize itself** to fit its content, so there's never an inner scrollbar or empty space below it. Add it once per page, even if you embed several calendars.

---

### Customising the calendar

Add options to the `src` URL as query parameters — for example `…/embed/c/your-calendar?view=week&theme=dark`.

| Parameter | Values | What it does |
| --- | --- | --- |
| `locale` | `en`, `sk`, `uk`, … | Language of the widget |
| `view` | `month`, `week`, `day`, `list` | Which view to open on |
| `tz` | e.g. `Europe/Bratislava` | Time zone to show times in |
| `theme` | `light`, `dark` | Force light or dark (default: follows the visitor) |
| `accent` | `%23rrggbb` | Override the accent colour (write `#` as `%23`) |
| `bg` | `transparent`, `%23rrggbb` | Card background — `transparent` blends into your page |

A dark Slovak calendar opening on the week view:

```html
<iframe
  class="cloomba-embed"
  src="https://cloomba.com/embed/c/your-calendar?locale=sk&view=week&theme=dark"
  style="width: 100%; height: 800px; border: none"
  loading="lazy"
  title="My calendar"
></iframe>
<script src="https://cloomba.com/embed/embed.js" async></script>
```

---

### Good to know

- The widget only shows **public** events — private and unlisted events never appear.
- Every event links out to its full page on Cloomba in a new tab; registration and sign-in happen there.
- The starting `height` is only a fallback for the moment before the script loads — after that the widget sizes itself.
