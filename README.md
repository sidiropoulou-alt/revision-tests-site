# Revision Tests — TDL Unit 1 "Who We Are"

**Live site: <https://sidiropoulou-alt.github.io/revision-tests-site/>**

English revision test for Grade 3, TDL Unit 1. Six topics (Culture, Traits, Life Cycles,
Facts, Learner Profile, Challenge) with 42 questions — mostly True/False and Yes/No, plus a
few funny 😄 trick questions. Tap a question card to reveal its answer. No login, no app;
works on phones, tablets and computers.

This repository holds **only** the published copy of that one site:

| File | What it is |
| --- | --- |
| `index.html` | The test chooser — **this is the page students open** |
| `tdl.html` | The TDL Unit 1 test (self-contained: questions, styles and script are all inside) |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing |

## Publishing an update

From the private project repository:

1. `node build-site.js`
2. copy `index.html` and `tdl.html` from the generated `revision-tests/` folder over the
   files in this repository (or push that folder)

GitHub Pages rebuilds automatically, and the address above never changes.

## What is not here

The question bank (`data/quiz.json`), the build scripts and the source PDF live in a
separate **private** repository, so they are not published here. This repository exists
only to serve the finished page.

---

*Prepared by Lemon Code, an AI agent, on behalf of the repository owner.*
