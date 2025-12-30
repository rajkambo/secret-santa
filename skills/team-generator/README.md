# 🎄 Secret Santa Team Generator

A lightweight, reusable ChatGPT-powered tool for generating **fun, balanced teams** for annual Secret Santa game nights.

This project treats team generation as a **first‑class capability** (like an internal tool), not a one‑off prompt.

---

## ✨ What This Does

Given:
- A list of participants
- A desired number of teams

The Secret Santa Team Generator will:
- Create **evenly balanced teams**
- Keep **couples together** by default
- Generate **fun, unique team names** (no reuse across years)
- Ensure **no one is missed**
- Output results in a clean, copy‑paste‑ready format

Each year’s output can be saved as a reusable artifact (e.g. *Secret Santa Teams – 2025*).

---

## 🚀 How to Use (Canonical Prompt)

Copy‑paste the prompt below into the **Secret Santa ChatGPT Project**:

```
Use the Secret Santa Team Generator.

Number of teams: <N>
Participants:
- <Participant 1>
- <Participant 2>
- <Participant 3>
- ...

Constraints (optional):
- Keep couples together
- Balance team sizes
- Avoid repeating last year’s teams

Generate the teams and save the result as this year’s artifact.
```

That’s it. No further explanation required.

---

## 🧠 Built‑In Rules

The generator automatically guarantees:
- Every participant is assigned to **exactly one team**
- Teams are as evenly sized as possible
- Couples stay together unless explicitly allowed otherwise
- Team names are:
  - Fun and playful
  - Game‑night appropriate
  - Not reused from prior years

If any rule cannot be satisfied, the generator will **explicitly warn you** before finalizing output.

---

## 🔁 Year‑Over‑Year Usage

Each year, simply re‑run the prompt with:
- Updated participants
- A new team count (if needed)

Example:

```
Generate 2026 Secret Santa teams using the usual rules.
We have 18 participants and want 5 teams.
```

---

## 🎁 Philosophy

This project treats holiday logistics like good software:
- Clear interface (inputs → outputs)
- Reusable logic
- No hidden state
- Zero manual bookkeeping

Christmas ops, automated 🎄⚙️