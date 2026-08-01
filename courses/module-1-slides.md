# Module 1: Penetration Testing with Kali Linux — General Course Introduction

- **Gamma editor:** https://gamma.app/docs/i07xtfb011p57dj
- **Source PPTX:** Module_1_Slides.pptx
- **Slides in source:** 57
- **Final cards:** 57
- **Generated:** 2026-08-01
- **Theme:** tkszchn8552lzjg

## QA summary
- Blockers: 2
- Minor issues: 4

## Blockers (manual fixes needed)
- **Card 55–56 area — "Knowledge Check" content missing.** Source slide 55 ("Which Learning Unit covers the course inventory, the attacking Kali VM, the PWK VPN, and Module Exercises?" with answers A–D, correct answer B) does not appear anywhere in the generated deck. Fix: manually add a new card between "Common Misconceptions" and the closing "24 Learning Modules" card, recreating the multiple-choice question and answer options from the source slide.
- **Card 56 — two unrelated topics merged onto one card.** The card with id `tm778451pc4b35g` stacks the big-number "24 — Learning Modules in the Official PEN-200 Syllabus" content and the separate "Module 1 Summary — Three Lines" content on a single card, divided only by an `<hr>`. This will likely render as cluttered/overloaded. Fix: split into two separate cards in the Gamma editor (one big-number card, one three-unit summary card), matching the two distinct source slides (54 and 56).

## Minor issues
- **Acronym Spotlight table (card "Acronym Spotlight — Terms Introduced in Module 1") is incomplete.** Source slide 52 lists 8 acronyms (PEN-200, PWK, OSCP, VM, VPN, OSINT, NSE, AD); the generated table only kept 5 (PEN-200, PWK, OSCP, VPN, VM), dropping OSINT, NSE, and AD. Consider re-adding the missing rows for completeness.
- **Reference table regrouping differs from source.** The "24 Learning Modules — Grouped Reference" card condenses the syllabus into 8 blocks (e.g., merging Modules 10–13 and 14–16 differently than the source's 9-block breakdown). Content is accurate but the grouping boundaries changed during condensing; verify the new grouping still matches the course's intended block breakdown before publishing.
- **Two divider-style cards fall under the 40-word threshold.** "Welcome to PWK" (Objective 1.1 divider, ~42 words — borderline) and specifically "How to Approach the Course" (~39 words) and "Summary of PWK Learning Modules" (~38 words) are short. This is expected for section-divider cards but is flagged per the length-balance QA check; no action needed unless more visual weight is desired.
- **Card 3 image only loosely relevant.** The accent image for "Course Context — 24 Learning Modules" (alt: "network topology diagram on dark monitor screen") is a generic pentesting-adjacent visual rather than one literally depicting a course/module map. Acceptable but could be swapped for a clearer course-roadmap-style image if desired.
