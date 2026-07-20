# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

StudyOS is Rafael's personal study-tracking system ("second brain") for AI, software engineering, and BrandOS development — not a software project. There is no build, lint, or test tooling; all work is editing Markdown files and committing/pushing with git.

## Structure

- `README.md` — current goals and the weekly routine (Mon–Sat execution, Sunday review/planning).
- `ROADMAP.md` — the learning path (courses in progress/queued) and active project(s). Has a `# Notes` section for time-sensitive constraints (e.g. subscription deadlines, fixed cohort start dates) — check it before proposing schedule changes.
- `ROUTINE.md` — the day-to-day and weekly process, plus the required git commit message conventions (see below).
- `TIMELINE/YYYY-MM-DD_Week-NN.md` — one file per week, named by the Monday start date. Each has: `Weekly Goal`, a `Planning` section with a subsection per day (Monday–Sunday) of checkbox tasks, and a `Weekly Review` section (Completed / Main Learnings / Challenges / Improvements) filled in on Sunday.
- `KNOWLEDGE/*.md` — one file per topic (e.g. `Anthropic.md`, `Python.md`, `RAG.md`), holding only durable, worth-keeping notes — not a full transcript of every course.
- `CERTIFICATES/` — earned certificates.

## Working conventions

- New weekly file is created on Sunday when planning the next week; keep the weekly goal text consistent with what's actually in `ROADMAP.md`'s Notes section (deadlines, course start dates) rather than restating stale info.
- Task checkboxes: `- [ ]` open, `- [x]` done (Week 01 also used `[X]`; either casing has appeared, prefer lowercase `[x]` going forward).
- Only add to `KNOWLEDGE/` what's worth remembering long-term — the routine explicitly says "record only what matters."
- Follow the commit message pattern from `ROUTINE.md`: `study: ...`, `notes: ...`, `docs: ...`, `refactor: ...`. Avoid generic messages like "update" or "fix".
- Standard commit flow: `git add .`, `git commit -m "<type>: <message>"`, `git push` — only when the user asks for a commit.
