# 🎄 Secret Santa Jeopardy Generator

A reusable ChatGPT-powered skill for generating **full Jeopardy-style games** for Secret Santa game nights.

This treats Jeopardy generation as a **first-class project capability**, just like team generation — not a one-off prompt.

---

## ✨ What This Does

Given a set of inputs, the Jeopardy Generator will:
- Generate a complete Jeopardy board
- Support a **variable number of categories**
- Ensure **increasing difficulty** (100 → 500) within each category
- Use **user-specified categories** or intelligently **auto-suggest categories**
- Save the result as a **yearly artifact** for reuse

---

## 🚀 Canonical Prompt (Recommended)

Copy-paste this into the **Secret Santa ChatGPT Project**:

```
Use the Secret Santa Jeopardy Generator.

Number of categories: <N>
Category names (optional):
- <Category 1>
- <Category 2>
- <Category 3>

Rules:
- Each category must have 100, 200, 300, 400, and 500 point questions
- Difficulty must strictly increase
- Questions should be family-friendly and Christmas-appropriate

If categories are not provided, auto-suggest categories and confirm them before generating.

Generate the full Jeopardy board and save it as this year’s artifact.
```

---

## 🧠 Built-In Guarantees

The generator always ensures:
- Every category has **exactly five questions** (100–500)
- Question difficulty increases logically
- Answers are unambiguous and correct
- Categories are balanced (not all movie or trivia-heavy unless requested)
- Output is clean and host-ready

If categories are auto-suggested, **generation pauses for confirmation** before proceeding.

---

## 🔁 Year-Over-Year Usage

Each year, simply say:

```
Generate a Jeopardy game for this year using the usual rules.
We want 5 categories.
```

Optionally override categories:

```
Categories:
- Christmas Movies
- Christmas Food
- Fill in the Blanks
- Christmas Carols
- Random
```

---

## 🎁 Philosophy

Holiday games deserve production-quality tooling:
- Clear inputs
- Deterministic structure
- Zero manual question-writing

Jeopardy — automated 🎄⚡