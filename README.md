## GPT‑AJ02: AskJamie™ — Professional Portfolio

**Not a résumé. A clone of your best self.**  
GPT‑AJ02 turns your work, wins, and weirdly specific strengths into a living, conversational portfolio you can point prospects at 24/7—handling intros, FAQs, and early “tire‑kicker” questions while you focus on real work.

> Note: the public lens page is a work‑in‑progress; sections and links may evolve.

### Canonical links
- **Home (lens page):** https://askjamie.bot/lens-system/professional-portfolio/
- **Launch the public GPT:** https://chatgpt.com/g/g-691fa5845230819199d4ffb89b13e9ab-professional-portfolio-by-askjamietm
- **Notion source page:** https://www.notion.so/overkillhill/AJ02-Professional-Portfolio-5aa8f4f4d9034d0097379db4c80ea4a9
- **Support / Ko‑fi:** https://ko-fi.com/overkillhillp3
- **Contact (white‑glove / co‑design):** sales@overkillhill.com

### What this repo is
This repository is the **storage + version-control home** for everything behind GPT‑AJ02:
- Prompt/instruction architecture (role, boundaries, behavior)
- Knowledge file templates (case studies, offers, testimonials, “how we work,” FAQs)
- Evaluation tests (anti‑drift prompts + rubrics)
- Demo artifacts (notes, transcripts, examples)
- Release notes and changelog

This lens is wired to OverKill Hill P³™ / AskJamie™ as a proof‑of‑concept; the real deliverable is the **recipe**: prompts, patterns, and knowledge scaffolding you can adapt for your own AI portfolio.

### What this lens is (and isn’t)
**It is:** a professional representation system—a narrative engine that can speak for a person, a small company, or a sales team when you’re busy.  
**It isn’t:** a résumé builder, a generic marketing chatbot, or a promise that AI replaces brand strategy and human judgment.

### Repository layout
- `/prompts/` — system prompt, style rules, few‑shot examples
- `/src/` — raw corpus, case studies, transcripts, supporting notes
- `/build/` — compiled “packs” for upload (knowledge / prompt / eval)
- `/eval/` — regression tests + rubrics
- `/ops/` — release checklist, workflows, governance

### Update workflow (quick)
1. Add/edit source material in `/src` and `/prompts`
2. Rebuild `/build/*-pack.md` (keep uploads small in count, big in coverage)
3. Run `/eval` smoke tests
4. Update `CHANGELOG.md`, tag a release, and refresh the uploaded packs in ChatGPT
