---
title: "Writing a description in several languages"
meta_description: "Write one event description covering several languages — each visitor reads the one matching their interface language, on one event page with one guest list."
section: "Creating events"
section_position: 20
position: 54
status: published
generated: from whitetown/cloomba-content — do not edit here, open an issue instead
---

Running an event for people who read different languages? Write one description with a section per language. Each visitor sees the section matching the language they are using Cloomba in — on one event page, with one link and one guest list.

Nothing is translated for you. You write each section yourself.

---

### How to write it

Mark each language with a `#` heading whose entire text is the language code:

```markdown
## Postgres evening

Doors 18:00 · Bratislava · free

# en
Join us for an evening of Postgres talks.

# sk
Príďte na večer prednášok o Postgrese.
```

Someone reading Cloomba in Slovak sees the Slovak lines. Everyone else sees the English ones. Both see the two lines above the first language heading.

---

### The part everyone sees

Everything above the first language heading is shared. It goes to every reader, above their own section — so it is where the facts that need no translating belong: the venue, the time, the price, the poster.

You can skip it and start straight at `# en`.

---

### Two rules

**One `#`, and nothing but the code.** `# en` and `# SK` work. `## en`, `# ENG`, `# en talks` and `#en` do not — those stay as ordinary text.

**At least two languages.** A description with a single `# en` in it is not a translated description, so it is left exactly as written.

Both rules fail the same way. If what you wrote is not unmistakably a set of language sections, your text is shown as you typed it — nothing is hidden and nothing is guessed.

---

### Your own headings start at `##`

Since `#` marks a language, write the headings inside each section as `##` or `###`. See [formatting text with markdown](/help/markdown).

---

### Which codes work

`en` · `cs` · `de` · `es` · `fr` · `it` · `nl` · `pl` · `pt` · `sk` · `uk`

These are the languages the Cloomba interface is available in. Capitals are fine.

---

### What each visitor sees

- The section in their language, if you wrote one.
- Otherwise the English section.
- Otherwise the whole description, headings and all — showing someone every language beats handing them one they cannot read with no sign the rest exists.

---

### Where else your sections are used

Event emails use the section matching the language of the person receiving them.

Calendar files, feeds, and the preview text shown when your link is shared carry one language only, because there is nowhere in them to choose.

Only the **description** works this way. Titles, updates, guest questions, and comments are single-language — see [language and locale settings](/help/language-and-locale).

---

### Keep it short

Two well-written paragraphs per language beat a full translation nobody finishes. Let the shared part at the top carry everything factual — date, place, price — so each language section only has to make the case for coming.
