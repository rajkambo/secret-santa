# How to Use This Project (ChatGPT + GitHub)

This repo is a **template** for running an annual Secret Santa game night using reusable “skills” (prompts/instructions) inside a ChatGPT Project.

The repo is the **source of truth**.
ChatGPT is the **execution engine**.

---

## Quick Start (Once Per Year)

1) Update your participant list (if needed)
2) Run the team generator in ChatGPT
3) Run the Jeopardy generator in ChatGPT
4) Save outputs into `/artifacts/<YEAR>/`

---

## Set Up the ChatGPT Project

In ChatGPT:
1. Create a **Project** named something like `Secret Santa`
2. Paste the canonical skill instructions into **Project Instructions** (or keep them in canvases and copy-paste when needed)
3. When you want to run a skill, use the one-line invocation prompts (see `INVOCATION_CHEATSHEET.md`)

---

## Running a Skill

Each skill has:
- `skills/<skill>/INSTRUCTIONS.md` (canonical rules/behavior)
- `skills/<skill>/README.md` (simple usage prompt)

When you want output:
- Invoke the skill in ChatGPT
- Copy the result back into this repo under `/artifacts/<YEAR>/`

---

## Artifacts Convention

Save yearly outputs here:

/artifacts/2025/teams.md  
/artifacts/2025/jeopardy.md  

This makes next year’s reruns easier (avoid repeats, compare teams, reuse categories, etc.).

---

## Recommended Hosting

- Publish this repo as a **GitHub Template**
- Each year, click “Use this template” to create a new year’s working repo (optional)
  - OR keep one repo and add a new `/artifacts/<YEAR>/` folder annually.
