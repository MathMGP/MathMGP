## I automate my own problems

Most of these started as *"I can't keep doing this by hand"* moments at work.

| Problem | What I built |
|---|---|
| Comparing 5+ export PDFs for errors before a shipment leaves | [document-comparator](https://github.com/MathMGP/document-comparator) — drag the docs, Gemini reads them all and flags every mismatch |
| PDF too large for a government upload portal | [pdf-compressor](https://github.com/MathMGP/pdf-compressor) — system tray app, drag and done in seconds |
| Small business drowning in 15 spreadsheet tabs | [parking-pwa](https://github.com/MathMGP/parking-pwa) — offline PWA, single HTML file, no backend, installable on iOS/Android |
| Claude Code losing context in the middle of a long task | [claude-agent-pipeline](https://github.com/MathMGP/claude-agent-pipeline) — 4-agent pipeline that resumes exactly where it stopped |
| Consolidating product quantities from hundreds of NF-e XML files | [nfe-products-extractor](https://github.com/MathMGP/nfe-products-extractor) — reads XML per contract folder, outputs formatted Excel |

---

**Stack:** Python · Claude & Gemini APIs · asyncio · tkinter · Telegram Bot API · Proxmox · systemd

**Currently:** Export operations by day. Automating everything that slows me down.
