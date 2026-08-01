# Module 18: Advanced Tunneling

- **Gamma editor:** https://gamma.app/docs/czi5rz72f9vaa7n
- **Source PPTX:** Module_18_Slides.pptx
- **Slides in source:** 21
- **Final cards:** 21
- **Generated:** 2026-08-01
- **Theme:** tkszchn8552lzjg

## QA summary
- Blockers: 1
- Minor issues: 5

## Blockers (manual fixes needed)
- Card 11 ("HTTP Tunneling vs. DNS Tunneling"): only 37 words of visible card text — the core Chisel-vs-dnscat comparison (speed, first-choice-vs-fallback, common mistake of defaulting to DNS) was pushed entirely into an AI-generated infographic image rather than kept as readable card text/columns. AI-generated infographics often render text inaccurately or illegibly. Fix: in the Gamma editor, replace the infographic block with a two-column text layout (matching the style used on Card 4) so the comparison text is guaranteed legible, or manually verify the infographic renders the comparison text correctly and edit if not.

## Minor issues
- Card 1 ("Advanced Tunneling"): accent image is a stock photo from a "Dura-Line intentional cable cuts" article — depicts physical fiber-optic cable damage rather than a digital/pentest tunneling concept. Suggest swapping for a more on-topic network/tunneling image.
- Card 8 ("Performing HTTP Tunneling with Chisel"): accent image is sourced from a Palo Alto Unit42 threat-report screenshot ("Cybercriminals Abuse Open-Source Tools..."), labeled with alt text "chisel tool server client connection diagram" — verify the image actually shows a relevant Chisel diagram and not an unrelated report screenshot.
- Card 12 ("Objective 18.1 Recap"): accent image is a Cisco DMVPN/NHRP/IPsec architecture diagram — unrelated to the HTTP/DNS tunneling tools (Chisel, dnscat) actually covered in this module. Suggest replacing with a Chisel/dnscat-relevant image.
- Card 16 ("Acronym Spotlight"): the dnscat icon resolves to a generic fallback "user" icon instead of a DNS/network-relevant icon (icon lookup for "dns server globe" appears to have failed). Minor visual inconsistency.
- Card 20 ("Module 18 Summary"): the "Together" icon likewise resolves to a generic fallback "user" icon instead of a toolkit/checkmark icon. Same root cause as Card 16.
