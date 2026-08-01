# Module 15: Windows Privilege Escalation

- **Gamma editor:** https://gamma.app/docs/sf3sectmddog46a
- **Source PPTX:** Module_15_Slides.pptx
- **Slides in source:** 33
- **Final cards:** 33
- **Generated:** 2026-08-01
- **Theme:** tkszchn8552lzjg

## QA summary
- Blockers: 1
- Minor issues: 4

## Blockers (manual fixes needed)
- Card 3 ("Course Context — 24 Learning Modules"): accent image is a mismatched web photo (an AI/GPT-6 news article thumbnail with title "Google Lost Its $2.7 Billion AI Lead to OpenAI...") with no visual relation to the course roadmap topic. Fix: in the Gamma editor, regenerate/replace the image with a search like "course roadmap path networked nodes dark" or switch to the theme's accent image instead of a web-sourced photo.

## Minor issues
- Card 9 ("Finding Sensitive Information in PowerShell Artefacts"): accent image is a generic Linux bash-history terminal screenshot sourced from an unrelated "clear logs on hacked Linux systems" article; thematically close (terminal/history) but not Windows/PowerShell-specific. Fix: replace with a Windows PowerShell console-style image.
- Card 13 ("Hijacking Service Binaries"): accent image is a "binary similarity matrix" chart from an unrelated malware-analysis blog post (matched on the word "binary" rather than the technique). Fix: replace with a Windows service/executable icon or a generic file-replacement graphic.
- Card 29 ("Common Misconceptions About Module 15"): only 5 of the 6 intended misconceptions rendered; the point "Any writable file near a service is exploitable" (the service must actually load/execute that file) was dropped during condensing. Fix: manually add the missing misconception item back in the editor.
- Card 11 ("Objective 15.1 Recap"): the target diagram split content into 4 buckets (Foundation, Search Targets, Tooling, Situational Awareness) instead of the intended 3 themes, since Situational Awareness was pulled out of Foundation, creating minor redundancy. Fix (optional): merge "Situational Awareness" back into "Foundation" in the diagram.
