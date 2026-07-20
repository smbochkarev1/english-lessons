# English Lessons — Interactive Self-Study

Self-checking English practice that runs entirely in the browser. No build step, no dependencies, nothing saved — open a page and start.

**Live:** https://smbochkarev1.github.io/english-lessons/

## Contents

| Page | Level | What's inside |
|------|-------|----------------|
| [`index.html`](index.html) | — | Landing page / lesson index |
| [`dk-practice.html`](dk-practice.html) | A2 · Beginner | Interactive drills for Units 1–5: "to be", present simple (routines), present continuous, present-continuous questions, and action vs. state verbs — plus a real street-interview **listening** section |
| [`relocation-b1.html`](relocation-b1.html) | B1 | Vocabulary, reading, comprehension, grammar, speaking & writing around relocation / visas / citizenship |

## The practice engine

`dk-practice.html` is a single self-contained file with a small data-driven engine. Exercise types:

- **choice** — cross out the incorrect word
- **gap** — fill in the blank (contractions & minor typos accepted)
- **match** — dropdown matching
- **tf** — reading + true / false / not given
- **forms** — rewrite a sentence in its other form(s)
- **order** — tap the words into the correct order
- **category** — sort words into groups
- **scene** — pick the sentence that matches a picture
- **speak** — speaking prompts with model answers

Add or edit exercises by changing the `UNITS` array — no other code changes needed.

## Images & audio

- Exercise pictures (`img/ex-*.png`) are the original book illustrations, cropped for the picture-based tasks (2.4, 3.2, 3.8, 4.3, 4.7, 5.5, and the 2.5 blog photo).
- Every exercise links to its **official DK audio** (free) on `apps.dk.com/efe/…` — for listening tasks it's the recording, for the others the spoken answers. Nothing copyrighted is rehosted here; the links open DK's own player. Correct answers are also in each exercise's key.
- `audio/street-interview.mp3` is a separate A2 street-interview recording — a fully working listening task in the bottom section, with answers verified against its transcript.

## Notes

- Exercises are rebuilt as interactive drills from *English for Everyone — Practice Book, Level 2 (Beginner)*, Units 1–5, for personal study. Answers were verified against the book's Answers section.
