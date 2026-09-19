# Prompt Log — G Boyz Wire Wheels Week 1 Build

## Entry 1 — 09/17/2026

**Tool:** Claude (chat)

**Prompt:** Scoped the project with Claude: decided on G Boyz Wire Wheels as the subject, locked headline, 3 sections (About, Gallery, Contact), and one CTA button.

**Why:** Needed a real subject with real stakes, tied to the Gboyz rebuild goals,while staying inside spec (no bonus features).

**Result:** Confirmed scope as written above: did not let it expand into
the full catalog/checkout vision I have for the real rebuild.


## Entry 2 — 09/17/2026

**Tool:** Claude Code

**Prompt:** Build index.html and style.css for G Boyz Wire Wheels. Headline, one liner, 3 sections (About, Gallery, Contact), one Call to Order button. Dark, chrome, gold style. Comment sections. Plain HTML/CSS only. Used stock wheel images since I don't have real shop photos yet.

**Why:** I locked scope first in a separate chat (style, CTA, section order, images), so this prompt just executed decisions I already made.

**Result:** Matched my scope, confirmed before moving on.


## Entry 3 — 09/17/2026

**Tool:** Claude Code

**Prompt:** Go back and comment the key lines. Plain language, casual tone, only lines that matter. Skip the obvious stuff.

**Why:** I need to explain this build on demo day, not just show it.

**Result:** Asked it to list a few comments back so I could check them without opening the file. Got 4 back — CTA tel: link, grid auto-fit, box-sizing, and the mobile media query.


## Entry 4 — 09/17/2026
**Tool:** Claude Code (self critique) + manual check

**Prompt:** Asked Claude Code to review its own work and admit what it hadn't verified.

**Why:** This is the "catch one mistake" step: checking its self critique
myself instead of just accepting it.

**Result:** It admitted it never opened the site in a browser to verify. Checking that led me to a bigger catch: the log said I used placehold.co images, but index.html has only ever had CSS-only placeholder boxes — no <img> tag exists in the repo history. Found by diffing my prompt log against git log/git show. Log and code had drifted apart.


## Entry 5 — 09/18/2026

**Tool:** Claude Code

**Prompt:** Remove the Call to Order button in the contact section of index.html. Keep the one in the hero. Keep the phone number link as-is.

**Why:** Spec calls for one CTA button; index.html had two (hero + contact section).

**Result:** Removed the duplicate button. It also flagged two comments (in index.html and style.css) that still described two buttons — had it update those too, so the code and its own comments agree.