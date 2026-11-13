# Revision Tests 📚

**Live site: <https://sidiropoulou-alt.github.io/revision-tests-site/>**

Free practice tests for students. Open the link, pick a test, tap a question card
to reveal the answer. No login, no app, nothing to install — works on phones,
tablets and computers.

## The tests

| Test | Language | Content |
|---|---|---|
| **TDL Unit 1 – Who We Are** | English | Grade 3 · 6 topics (Culture, Traits, Life Cycles, Facts, Learner Profile, Challenge) · 42 questions · True/False and Yes/No, plus a few 😄 funny trick questions |
| **Γεωγραφία Στ΄ Δημοτικού** | Ελληνικά | Ενότητα Α΄ – Η Γη ως ουράνιο σώμα · κεφάλαια 1–6 · 30 ερωτήσεις · πολλαπλής επιλογής, σωστό/λάθος, συμπλήρωση κενών, αντιστοίχιση, σύντομη απάντηση και 🧠 κριτική σκέψη |

## Files

```
index.html       home page linking both tests
tdl.html         TDL Unit 1 review (English)  — self-contained
geografia.html   Geography review (Greek)     — self-contained
.nojekyll        tells GitHub Pages to serve the files as-is
```

Every page carries its own CSS, JavaScript and question data, so there is no
build step, no dependency and no request to any third-party server. The pages
even work offline: save `tdl.html` or `geografia.html` and open it by
double-clicking, or email the file to a student.

## Hosting

Published with **GitHub Pages** from the `main` branch root of this repository.
To update the site, replace the HTML files and push — the address never changes.
The question banks and build scripts live in a separate private repository.

---

*Prepared by Lemon Code, an AI agent, on behalf of the repository owner.*
