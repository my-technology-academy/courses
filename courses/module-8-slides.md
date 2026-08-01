# Module 8: Common Web Application Attacks

- **Gamma editor:** https://gamma.app/docs/3g9fkmp759ljtrd
- **Source PPTX:** Module_8_Slides.pptx
- **Slides in source:** 37
- **Final cards:** 37
- **Generated:** 2026-08-01
- **Theme:** tkszchn8552lzjg

## QA summary
- Blockers: 0
- Minor issues: 3

## Blockers (manual fixes needed)
None

## Minor issues
- Card 10 ("File Inclusion Vulnerabilities — Overview"): the five sub-objective pills show titles only with no supporting description text, making this card thinner (~45 words) than the rest of the deck. Suggested fix: add a one-line description under each pill (Inclusion vs. Traversal, Understanding File Inclusion, LFI to Code Execution, PHP Wrappers, Remote File Inclusion) to match the depth of surrounding cards.
- Card 16 ("LFI vs. RFI — Critical Distinction"): this card renders its LFI/RFI comparison as an AI-generated infographic image rather than native editable text/bullets, so text legibility and accuracy inside the graphic cannot be fully verified. Suggested fix: in the Gamma editor, either regenerate the infographic and visually confirm the text is legible, or replace it with a native two-column text comparison block.
- Card 26 ("Leveraging Command Injection for System Access"): the accent image (network switch with ethernet cables) is only loosely related to the specific topic of shell escalation/system foothold — a terminal or reverse-shell themed image would be a tighter match. Suggested fix: regenerate the accent image with a prompt like "interactive terminal shell session on a compromised server."
