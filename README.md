# CSE309 — Theory of Automata (IBA) | Resource Repository

This repository is a **one-stop, exam-focused resource hub** for **CSE309: Theory of Automata** at IBA Karachi. It consolidates **past papers, quizzes, problem sets, tutorials, lecture decks, topical notes, and curated external university resources** across multiple semesters so students can **practice patterns**, **cover gaps across offerings**, and **prepare efficiently** without spending hours hunting material.

**Maintainer:** Zuha Aqib  
**Purpose:** Student support (practice + revision) and long-term consolidation of high-quality Automata resources.

---

## Table of Contents
- [Why this repository exists](#why-this-repository-exists)
- [Teaching/learning context](#teachinglearning-context)
- [Important note on adding new semester material](#important-note-on-adding-new-semester-material)
- [Quick Links](#quick-links)
- [How to use this repo (recommended exam-first workflow)](#how-to-use-this-repo-recommended-exam-first-workflow)
- [Repository structure](#repository-structure)
- [What to practice for each major topic](#what-to-practice-for-each-major-topic)
- [External resources included](#external-resources-included)
- [Academic integrity](#academic-integrity)
- [Contributing](#contributing)

---

## Why this repository exists
CSE309 is one of those courses where **past assessments matter**: patterns repeat, proof styles become predictable, and strong practice comes from seeing *how questions are asked across multiple offerings*. Students also often face a common problem:

- One semester has stronger materials for **regular languages**, another has better **CFG/PDA** coverage, another has more structured **decidability / reductions**, etc.
- Students end up searching across seniors’ drives, random groups, and scattered links.

This repo fixes that by consolidating **everything useful in one place**:
- Past **quizzes**, **midterms**, **finals**
- **Problem sets/homework** (and in some cases solutions or marking guidance)
- **Tutorials** (great for bridging concepts → exam-style questions)
- **Topical practice notes and links**
- Carefully chosen external resources I personally used while studying

---

## Teaching/learning context
I created and maintain this repo based on my own journey through the course and TA experiences:

- **Took CSE309 in Spring 2024** — Instructor: **Dr. Shahid Hussain** (Chairperson, CS Department)
- **TA in Fall 2024** — Instructor: **Dr. Asma Sanam Larik**
- **TA in Spring 2025** — Instructor: **Dr. Shahid Hussain**
- **TA in Spring 2026** — Instructor: **Dr. Jibran Rashid** (current)

The resources here include material from IBA offerings and external sources that helped me personally while preparing.

---

## Quick Links
### IBA Course Outlines (past offerings)
- `cse309_ToA_spring_2024.pdf`
- `cse309_ToA_fall_2024.pdf`
- `cse309_ToA_spring_2025.pdf`

### High-value exam preparation
- **Midterm resources:** [`mid_exam/`](./mid_exam)
- **Final resources:** [`final_exam/`](./final_exam)
- **Quizzes (practice + solutions where available):** [`quizzes/`](./quizzes)
- **Problem sets/homework:** [`problem_sets/`](./problem_sets)
- **Tutorials (exam-style walkthroughs):** [`tutorials/`](./tutorials)

### Topic-wise reinforcement
- **Topical notes + drills:** [`practice_topical/`](./practice_topical)
- **Hard questions:** [`practice_hard_qs/`](./practice_hard_qs)

### Books & external packs (time-savers)
- **Primary course textbook:** [`book/`](./book)
- **Sipser / MIT-style practice pack:** [`CS_Michael_Sipser/`](./CS_Michael_Sipser)
- **Additional university practice sets + answers:** [`CS341_Elaine_Rich/`](./CS341_Elaine_Rich)

---

## How to use this repo (recommended exam-first workflow)
This workflow is designed for a student who wants results quickly and wants to practice like an exam.

### Step 1 — Start from past assessments (pattern recognition)
1. Open **past quizzes**: [`quizzes/`](./quizzes)  
2. Open **past midterms**: [`mid_exam/`](./mid_exam)  
3. Open **past finals**: [`final_exam/`](./final_exam)

While reviewing, note:
- What topics are tested most
- What proof styles repeat (especially in regular languages & CFG)
- How reductions/decidability questions are framed

### Step 2 — Practice using problem sets (depth + difficulty)
Go to: [`problem_sets/`](./problem_sets)  
Problem sets are usually the best place to build real skill, especially for:
- Regular expressions and automata construction
- CFG design, ambiguity, derivations
- PDA design and CFL arguments
- Reductions and decidability structure
- Complexity topics where included

### Step 3 — Use tutorials to learn “how to write the solution”
Go to: [`tutorials/`](./tutorials)  
Tutorials help you learn:
- The expected format of answers
- How to structure proofs cleanly
- Common mistakes and how to avoid them

### Step 4 — Fill topic gaps using the topical folder
Go to: [`practice_topical/`](./practice_topical)

This is the best folder when you are:
- weak in one topic,
- or your current course coverage feels incomplete,
- or you want extra drills before an assessment.

### Step 5 — Use external packs for extra timed practice (optional)
If you’ve done enough IBA material and want more:
- [`CS_Michael_Sipser/`](./CS_Michael_Sipser)
- [`CS341_Elaine_Rich/`](./CS341_Elaine_Rich)

These are included to save you time searching—use them after your core prep is stable.

---

## Repository structure
```

.
├── book/                      # Primary course textbook (Sipser edition used in class)
├── lectures/                  # Lecture decks/handouts by semester (for reference & gap coverage)
│   ├── 2023-summer/
│   ├── 2024-fall/
│   ├── 2024-spring_me/
│   └── 2025-spring/
├── tutorials/                 # TA tutorials and walkthroughs by semester
│   ├── 2024-fall/
│   ├── 2024-spring_me/
│   └── 2025-spring/
├── problem_sets/              # Homework / problem sets by semester (some include solutions/marking guides)
│   ├── 2023-summer/
│   ├── 2024-fall/
│   ├── 2024-spring_me/
│   └── 2025-spring/
├── quizzes/                   # Quizzes (questions and/or solutions) by semester
│   ├── 2023-summer/
│   ├── 2024-fall/
│   ├── 2024-spring_me/
│   └── 2025-spring/
├── mid_exam/                  # Midterm papers/solutions by semester
│   ├── 2022-fall/
│   ├── 2024-spring_me/
│   └── 2025-spring/
├── final_exam/                # Final papers/solutions by semester
│   ├── 2022-fall/
│   └── 2024-spring_me/
├── practice_topical/          # Topic-wise practice + notes + helpful links
│   ├── 2024-spring_me/        # Topic-wise notes/handouts from Spring 2024
│   ├── decidability/
│   ├── np_reductions/
│   ├── regular_languages/
│   ├── time_complexity/
│   └── links.txt              # Useful links list
├── practice_hard_qs/          # A small set of intentionally hard questions
├── CS_Michael_Sipser/         # Sipser/MIT-style extra practice (problem sets/exams/solutions)
└── CS341_Elaine_Rich/         # Additional university practice sets (often with answers)

```

**Note on lectures:** The lecture decks here are included as **reference and gap coverage** across offerings. Future students should use them to strengthen weak topics, not as a “current semester lecture set.”

---

## What to practice for each major topic
Use this as a quick map to where you should practice depending on what you’re struggling with:

### Regular Languages (DFA/NFA/RE, closure, pumping, proofs)
- `practice_topical/regular_languages/`
- `lectures/2024-fall/` (practice-oriented lecture items)
- `problem_sets/` (multiple semesters)
- `quizzes/` (multiple semesters)

### CFG & CFL (grammars, derivations, ambiguity, CNF basics)
- `lectures/2024-spring_me/`
- `practice_topical/2024-spring_me/` (topic notes)
- `problem_sets/` + `tutorials/`

### PDA (design + reasoning)
- `lectures/2024-fall/`
- `tutorials/`
- `problem_sets/`

### Turing Machines (variants + constructions)
- `lectures/2024-fall/`
- `CS_Michael_Sipser/` for additional practice

### Decidability / Undecidability (mapping reductions, HALT-style structure)
- `practice_topical/decidability/`
- `lectures/2024-fall/`
- `problem_sets/` + `mid_exam/` + `final_exam/`

### Reducibility / NP reductions (structure + correctness proofs)
- `practice_topical/np_reductions/`
- `practice_topical/2024-spring_me/` (topic notes)
- `final_exam/` and advanced practice packs

### Time Complexity / Complexity Theory (where included)
- `practice_topical/time_complexity/`
- `lectures/2024-fall/`
- `practice_topical/2024-spring_me/`

---

## External resources included
Students often waste time searching for high-quality extra practice sets. I included the external resources I personally used during preparation so you can directly access them here:

- **Michael Sipser / MIT-style content**: `CS_Michael_Sipser/`  
  Helpful for problem sets, exam-style questions, and solution style.
- **Additional university practice sets**: `CS341_Elaine_Rich/`  
  Useful for timed mid/final practice, with answers available.

These should be used **after** you’ve covered the main IBA-style patterns.

---

## Academic integrity
This repository is for learning and practice.

- Follow your instructor’s policy for your current offering.
- If a resource resembles an active assessment, do not misuse it.
- For assignments: attempt first, then consult solutions (if present) strictly for learning.
- If you reuse an idea in your write-up, cite appropriately.

---

## Contributing
Contributions are welcome if they improve student learning and comply with policy.

Guidelines:
- Place files in the correct folder (`quizzes/`, `mid_exam/`, `final_exam/`, `problem_sets/`, etc.)
- Use clear filenames
- Do not upload any material that violates instructor/university policy
- Prefer adding resources **after** a semester ends unless explicitly permitted

If you contribute, include a short note describing:
- what you added,
- which topic it helps,
- and how it should be used (practice / reference / solution / marking guide).

---