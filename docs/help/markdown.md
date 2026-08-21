---
title: "Formatting text with markdown"
meta_description: "The markdown Cloomba supports — bold, headings, lists, links, tables and images — and where it behaves differently from markdown elsewhere."
section: "Creating events"
section_position: 20
position: 52
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

Most boxes where you write more than a line accept **markdown**: a small set of plain-text marks that turn into formatting when the page renders. You type `**sold out**`, readers see **sold out**.

Every one of those boxes has a **Preview** button. Use it — it renders exactly what your readers will see.

---

### Where it works

- Your event description
- Event updates
- Agenda sessions and speaker bios
- **How to get there** — parking, transit, and doorbell notes
- Payment instructions, when you collect money off Cloomba
- The description under a guest question
- Calendar newsletters

Titles, names, and comments are plain text — markdown marks typed there show up as the characters you typed.

---

### The basics

```markdown
**bold**   *italic*   ~~struck out~~

- a bullet
- another bullet

1. first
2. second

> a quoted line
```

Three dashes on a line of their own draw a divider across the page.

---

### Headings

**Start your headings at `##`.** A single `#` is reserved — Cloomba uses it to mark [language sections](/help/multilingual-descriptions) in event descriptions.

```markdown
## Schedule

### Morning
```

That still leaves five levels, more than any event page needs. On an event page every heading level renders at close to the same size anyway: headings are there to give your text structure and something to scan, not big type.

---

### Line breaks

This is the one place Cloomba differs from markdown elsewhere: **a single line break is a real line break.** Type a schedule one line at a time and it stays that way.

```markdown
18:00 — doors
18:30 — first talk
19:15 — break
```

Leave a blank line between blocks to start a new paragraph.

---

### Links

```markdown
[our venue](https://example.com/venue)
```

Links to other sites open in a new tab, so someone half-way through filling in your registration form does not lose their answers. A web address typed on its own becomes a link automatically.

---

### Tables

Good for schedules, line-ups, and price tiers.

```markdown
| Time  | Session         | Speaker |
| ----- | --------------- | ------- |
| 18:30 | Indexing basics | Jana    |
| 19:15 | Query plans     | Marek   |
```

Keep the number of columns small — the same table has to fit on a phone.

---

### Images

```markdown
![](https://example.com/poster.jpg)
```

In your **event description** there is a shortcut: paste an image from the clipboard, or drag a file into the box, and it uploads and inserts itself. Images sit on their own line and fill the width of the text column.

---

### What does not work

- **HTML.** Tags, `<iframe>` embeds, and scripts are ignored rather than shown. That includes embedded video players — link to the video instead.
- **Footnotes and mathematical notation.**

---

### If it looks wrong

Open **Preview**. Almost every surprise is one of three things: a heading with no space after the `##`, an emphasis mark opened and never closed, or HTML pasted in from another site and dropped.

---

See also [writing your event description](/help/event-description) and [writing a description in several languages](/help/multilingual-descriptions).
