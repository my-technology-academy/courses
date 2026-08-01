# Module 4: Report Writing for Penetration Testers

- **Gamma editor:** https://gamma.app/docs/uja6fanlxcnbrih
- **Source PPTX:** Module_4_Slides.pptx
- **Slides in source:** 33
- **Final cards:** 33
- **Generated:** 2026-08-01
- **Theme:** tkszchn8552lzjg

## QA summary
- Blockers: 1
- Minor issues: 3

## Blockers (manual fixes needed)
- Card 3, "Where Module 4 Sits in PEN-200": accent image is sourced from an Instagram crawler proxy URL (`lookaside.instagram.com/seo/google_widget/crawler/...`). This is a high risk of a broken/non-rendering image, and the source metadata references an unrelated Instagram caption rather than an actual PEN-200 curriculum roadmap. Fix: open the card in the Gamma editor and manually replace the image with a stock or AI-generated graphic depicting a course curriculum/module roadmap.

## Minor issues
- Card 1 (title slide), "Report Writing for Penetration Testers": accent image is pulled from a third-party CTF write-up blog (tantosec.com) with metadata referencing "DownUnderCTF Scoreboard Security Assessment," unrelated to OSCP/PEN-200. The image itself (an open report on a desk) is generically on-topic, but consider swapping for a more directly relevant stock/AI-generated image.
- Card 22, "Writing Technical Reports — What You Should Now Hold" (4.2 Recap): accent image is an Amazon product listing photo of binder dividers/tabs. Thematically fits ("organizing report sections") but is a commercial product photo that may carry subtle branding elements; consider a cleaner stock alternative.
- Card 33, "Module 5: Information Gathering": accent image (Nmap terminal screenshot) is topically correct, but its source URL path contains an unusual future date string; low risk, monitor for link rot over time.
