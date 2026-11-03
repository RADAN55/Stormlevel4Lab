# The Level 4 Lab

Twelve interactive ELPA21 tasks for grades 9–12, each built around one move that separates a
Level 3 answer from a Level 4 answer.

**Live site:** https://radan55.github.io/Stormlevel4Lab/

Part of the Storm Studio instructional system — EL Publishing, Laurel High School.

---

## What it is

Not a practice test. A set of drills on the behavior an ELPA21 rater is actually scoring.
Each task names its 3 → 4 move up front, then makes the student perform it, and the feedback
explains the move rather than just marking the answer right or wrong.

Every task opens with its **domain coach** — an original animated character who explains the
task, names the move, and gives one concrete tip before the student starts. Four coaches, one
per domain: Coach Okonjo (Reading), Coach Delgado (Writing), Coach Tran (Listening), and
Coach Bell (Speaking). Each coaching script plays in English or Spanish with the device voice,
and the full text is on screen either way.

ELPA21 reports a student Proficient when the score profile reaches Level 4 or higher in every
domain, so one domain stuck at Level 3 holds the whole profile back. Eight of the twelve tasks
sit in Reading and Writing.

## The twelve tasks

### Reading — exit gate
| | Task | The 3 → 4 move |
|---|---|---|
| R1 | Prove It | Point to the line that makes the answer right |
| R2 | Word Detective | Vocabulary in context, and pronoun reference |
| R3 | How the Paragraph Works | Say what a paragraph *does*, not just what it says |
| R4 | Two Texts, One Answer | An answer only true once both documents are read |

### Writing — exit gate
| | Task | The 3 → 4 move |
|---|---|---|
| W1 | Build the Sentence | Subordinate one idea to the other (because / although / if) |
| W2 | Describe What You See | Location phrases and present progressive |
| W3 | Say It to the Principal | Register control in an email |
| W4 | Make a Claim, Back It Up | Claim + evidence from both sources + concession |

### Listening
| | Task | The 3 → 4 move |
|---|---|---|
| L1 | Why Is She Telling Me This? | Speaker purpose, not only detail |
| L2 | Say It Back in One Sentence | Compress a whole talk without losing the point |

### Speaking
| | Task | The 3 → 4 move |
|---|---|---|
| S1 | Read the Graph Out Loud | Compare the numbers and say what they mean |
| S2 | Two Reasons and a Concession | Two distinct reasons plus the other side |

## How students use it

- Open the site, pick a task from the grid. The coach speaks first. Progress saves in that
  browser only.
- **Reading and listening** items give instant feedback that explains the move.
- **Writing** tasks run a live signal check — claim marker, named source, concession, connective
  count, sentence count, length — then show a Level 4 model with the moves highlighted.
  It is a writing-signal check, not a score.
- **Speaking** tasks run a clock (45s and 60s) with an honest self-check against rubric
  behaviors. Nothing is recorded in the browser; pair it with Flashlight360 or a partner if
  you want recorded evidence.
- **See what a 4 or a 5 looks like** sits at the bottom of all six constructed-response tasks
  (W2, W3, W4, L2, S1, S2). Three tabs — Level 3, Level 4, Level 5 — each with a full sample
  response to the same prompt and a list of what a rater sees in it. The Level 3 panel says
  why that answer stops where it does; the Level 5 panel lists only what it adds on top of
  the 4. Every Level 4 and Level 5 sample passes the same signal check the students are
  held to.
- **Listening** uses the device voice, with a **Show the script** button beside Play and an
  automatic fallback to the script if speech is blocked on the device or network. The coaches
  work the same way: if no voice is available the script is already written in the bubble, so
  nothing is lost on a locked-down Chromebook.
- **En español** on every coach swaps the instructions to Spanish, spoken and written. The
  passages themselves stay in English, the way the test is.

Chromebook friendly. No account, no sign-in, no data leaves the device.

## Teacher notes

- Works as a bell ringer (one task), a station rotation (one domain), or an intervention block
  for students sitting at Level 3 in a single domain.
- Progressing lane (ELPA21 3–4) is the target. Emerging students will need the model answers
  read with them first.
- The model answers are the most useful part for whole-class work — project one and ask the
  class to find the four things the rater is counting.
- The coaches are original illustrations drawn in SVG inside `index.html`. They are not real
  staff and are not photographs of anyone.

## Practice content

All passages, emails, figures, and data in this lab are original practice texts written for
classroom use. School names, staff names, dates, and figures inside them are invented and are
not announcements. The sleep graph is labeled practice data, not a real survey.

## Files

- `index.html` — the whole lab, one self-contained file. No build step, no dependencies beyond
  Google Fonts (Fraunces, Inter, IBM Plex Mono).

## Deploy

Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.

---

© Richard A. Daniel, M.Ed. — EL Publishing · Many Voices · One Storm
