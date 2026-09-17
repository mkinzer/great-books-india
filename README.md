# Great Books of the Indian Subcontinent

A "Great Books" reading-list project for South Asia and the Indosphere — the
primary texts a serious, non-specialist reader would want in order to follow the
region's long intellectual and literary tradition. It takes "Indian" in the
broad, older sense: India, Pakistan, Bangladesh, Sri Lanka, Nepal, and the
Afghan and Pashto sphere; the Hindu, Buddhist, Jain, Sikh, and Islamic
traditions; and some twenty languages, from Sanskrit and Pali to Sindhi,
Kashmiri, Odia, and Chagatai Turkish. The list is organized by theme rather than
strictly by chronology, and it deliberately stops at 1950.

The site is three finished pieces plus a landing page. Everything is plain,
self-contained static HTML/CSS/JS — no build step, no server, no external calls.

## The pieces

- **[The Atlas](indian-great-books-atlas.html)** — every work plotted on a map
  of South Asia, color-coded by theme and shaped by era, with a synced,
  filterable table. (D3 is inlined; nothing is fetched at runtime.)
- **[Western ↔ Indian](western-to-indian-great-books.html)** — a crosswalk
  pairing well-known Western works (Euclid, Machiavelli, the *Iliad*,
  Aristotle's *Poetics*…) with the comparable Indian text or tradition, over the
  full reading list, with hover tooltips and click-to-jump navigation.
- **[The Reading List](reading-list.html)** — the full list, roughly 120 works
  across nine themes, each with an annotation on why it earns a place and how it
  speaks to the works around it.

The prose reading list is also available as Markdown:
[`great-books-indian-subcontinent.md`](great-books-indian-subcontinent.md).

## A note on the scholarship

Dates for the oldest works are given as contested ranges on purpose, not fixed
years. The list stops at 1950 by design. Controversial texts are kept in, each
set against a counter-text — an editorial stance, not an oversight. Map
placements and crosswalk pairings are scholarly approximations that match role
and preoccupation, not exact claims of equivalence or provenance.

## Hosting

The site is served with GitHub Pages from the repository root. `index.html` is
the entry point, and every internal link is relative, so the files must stay in
the same directory with their filenames unchanged (GitHub Pages is
case-sensitive). A `.nojekyll` file is included so Pages serves the files —
including the `.md` — exactly as they are, without Jekyll processing.
