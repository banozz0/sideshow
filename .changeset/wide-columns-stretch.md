---
"sideshow": minor
---

Add an opt-in wide layout: a toggle beside Stream/Timeline lets the feed column grow past 860px (up to 1600px) on wide windows so diffs, code and html use the space, while markdown prose keeps a readable ~80-character measure. The choice is saved per workspace (`PUT /api/width` with `{"id":"wide"}`), and normal stays the default.
