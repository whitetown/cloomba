---
title: "Embed an event on your website"
meta_description: "Add a Cloomba event to your own site — as an inline card people can RSVP to, or a button that opens a registration pop-up."
section: "Embedding"
section_position: 65
position: 20
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

You can put any of your events on your own website in two ways: an **inline card** people can RSVP to in place, or a **button** that opens the event in a pop-up. Copy either from your event's **Manage → Advanced → Embed** section.

Replace `your-event` with your event's address (the part after `/e/` in its URL).

---

### Inline card

Shows the event — cover, date, location, and an RSVP button — right on your page.

```html
<iframe
  class="cloomba-embed"
  src="https://cloomba.com/embed/e/your-event"
  style="width: 100%; height: 300px; border: none"
  loading="lazy"
  title="My event"
></iframe>
<script src="https://cloomba.com/embed/embed.js" async></script>
```

The `embed.js` script resizes the card to fit. Free events can be RSVP'd to right in the card (visitors sign in inside the widget); paid events open Cloomba to complete payment.

---

### Registration button

A button that opens the event in a centred pop-up — handy when you just want a call-to-action.

```html
<a
  class="cloomba-checkout--button"
  data-cloomba-event="your-event"
>Register for Event</a>
<script src="https://cloomba.com/embed/button.js" async></script>
```

The button comes with a default style. To use your **own** styling, remove the `cloomba-checkout--button` class and style the `<a>` however you like — the pop-up still works.

---

### Customising

**Inline card** — add query parameters to the `src` URL (e.g. `…/embed/e/your-event?theme=dark`):

| Parameter | Values | What it does |
| --- | --- | --- |
| `locale` | `en`, `sk`, `uk`, … | Language of the card |
| `theme` | `light`, `dark` | Force light or dark (default: follows the visitor) |
| `accent` | `%23rrggbb` | Override the accent colour (write `#` as `%23`) |
| `bg` | `transparent`, `%23rrggbb` | Card background — `transparent` blends into your page |

**Button** — pass the same options as `data-cloomba-*` attributes; they're forwarded to the pop-up:

```html
<a
  class="cloomba-checkout--button"
  data-cloomba-event="your-event"
  data-cloomba-locale="sk"
  data-cloomba-theme="dark"
>Register</a>
<script src="https://cloomba.com/embed/button.js" async></script>
```

---

### Good to know

- Only **public** and **unlisted** events can be embedded — private events don't render.
- Registration needs a Cloomba account (no anonymous sign-ups), so visitors sign in inside the widget or pop-up. Paid tickets always complete on Cloomba.
- Add the `embed.js` / `button.js` script once per page, even with several embeds.
