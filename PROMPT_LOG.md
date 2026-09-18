# Prompt Log — G Boyz Wire Wheels Week 1 Build

## Entry 1 — 09/17/2026

**Tool:** Claude (chat)

**Prompt:** Scoped the project with Claude: decided on G Boyz Wire Wheels as the subject, locked headline, 3 sections (About, Gallery, Contact), and one CTA button.

**Why:** Needed a real subject with real stakes, tied to the Gboyz rebuild goals,while staying inside spec (no bonus features).

**Result:** Confirmed scope as written above: did not let it expand into
the full catalog/checkout vision I have for the real rebuild.


## Entry 2 — 09/17/2026

**Tool:** Claude Code

**Prompt:** Build index.html and style.css for G Boyz Wire Wheels. Headline, one
liner, 3 sections (About, Gallery, Contact), one Call to Order button. Dark,
chrome, gold style. Comment sections. Plain HTML/CSS only. Used stock wheel
images since I don't have real shop photos yet.

**Why:** I locked scope first in a separate chat (style, CTA, section order,
images), so this prompt just executed decisions I already made.

**Result:** Matched my scope, confirmed before moving on.


## Entry 3 — 09/17/2026

**Tool:** Claude Code

**Prompt:** Go back and comment the key lines. Plain language, casual tone, only
lines that matter. Skip the obvious stuff.

**Why:** I need to explain this build on demo day, not just show it.

**Result:** Asked it to list a few comments back so I could check them without
opening the file. Got 4 back — CTA tel: link, grid auto-fit, box-sizing, and
the mobile media query.


## Entry 4 — 09/17/2026
**Tool:** Claude Code (self critique) + manual check

**Prompt:** Asked Claude Code to review its own work and admit what it hadn't
verified.

**Why:** This is the "catch one mistake" step: checking its self critique
myself instead of just accepting it.

**Result:** It admitted it never opened the site in a browser to check rendering
or mobile sizing. I opened it myself, regular tab showed broken gallery images,
but DevTools mobile view showed them loading fine and the gallery correctly
collapsed to one column. Inspected the image tag, confirmed the placehold.co URL
is valid. Likely a caching issue in the first tab, not a code bug. The real
catch: it was right that it hadn't verified, and checking it myself surfaced a
real inconsistency worth confirming further.