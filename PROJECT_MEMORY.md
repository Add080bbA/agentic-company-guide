PROJECT_MEMORY
Handoff Brief — Idiot's Guide to Building a Fully Automated Software Company

For the AI reading this: Written by Claude Sonnet 4.6 on 2026-02-19. You are continuing ongoing work — not starting fresh. Read everything before responding. For per-session change history, read SNAPSHOT_LOG.

---

## 1. WHO IS THE USER

Name: Onur
Location: İzmir, Turkey — Timezone: Europe/Istanbul
Technical level: Intermediate. Comfortable with Terminal, Git, npm, Python basics. Not a professional developer but learns fast.
Primary goal: Build a fully automated agentic software company that ships iOS apps with minimal human involvement.
Hardware: Mac Mini M1 16GB — this was the primary recommendation. May still be in purchasing phase.
Subscriptions: Claude Pro ($20/mo). Decided to stay on claude.ai rather than switch to Cowork — Cowork burns quota too fast on Pro.
Google Drive MCP: Connected and working. All project files live in My Drive/AI/Claude/AgenticCompany-Guide/
GitHub username: Add080bbA
Communication style: Casual, concise, typos are normal. Wants direct answers, real commands, real links. Does not need things over-explained.

---

## 2. WHAT THIS PROJECT IS

An interactive HTML helpbook titled:
"The Idiot's Guide to Building a Fully Automated Software Company"

Single self-contained HTML file. Features:
- Dark theme (background: #0d0f14, accent orange: #f5a623, green: #6ee7b7, purple: #a78bfa)
- Left sidebar navigation — 13 chapters (00–12)
- Right content pane per chapter
- Interactive checkboxes with live progress bar in header
- Copy-to-clipboard buttons on code blocks AND on individual checklist items (right-aligned)
- Keyboard navigation (arrow keys between chapters)
- Turkish e-commerce hardware purchase links (6 shop cards)
- Learning resource link cards throughout

---

## 3. CURRENT GUIDE STATE

Version: v1.1 — Last edited by Claude Sonnet 4.6 on 2026-02-19

---

## 4. FILE & URL LOCATIONS

| File | Location |
|---|---|
| HTML Guide | `~/Projects/Claude/agentic-company-guide/index.html` |
| GitHub Repo | https://github.com/Add080bbA/agentic-company-guide |
| Live URL | https://add080bba.github.io/agentic-company-guide/ |
| Google Drive | My Drive/AI/Claude/AgenticCompany-Guide/ |

Deploy workflow (after every update):
`git add index.html && git commit -m "message" && git push` → auto-deploys via GitHub Pages

---

## 5. DESIGN DECISIONS (do not change without asking Onur)

- Dark theme only — never suggest light mode unless asked
- Fonts: Plus Jakarta Sans (body), JetBrains Mono (code/UI), Syne (headings) — switched from Lora after feedback
- Font size: 16px base, 1.85 line-height — bumped after "quantum bigger" feedback
- Copy buttons: On both code blocks (top-right) AND checklist items (inline right) — added after explicit feedback
- Turkish hardware links: 6 cards, 3-column grid — Apple TR, Hepsiburada, Trendyol, Sahibinden, SaveAsTech, Mac Marketi. Keep these.
- Free tools only for virtual environments — no paid venv tools
- HTML format only — not Word, not PDF (unless Onur asks)
- Version scheme: v1.x = content additions, v2.x = structural overhaul

---

## 6. TECH STACK RECOMMENDED TO ONUR

```
Primary AI:       Claude Sonnet 4.6 (code), Opus 4.6 (PM agent decisions)
Cheap tasks:      Claude Haiku 4.5
Design agent:     GPT-4o + DALL-E
Orchestration:    CrewAI (role-based), LangGraph (complex stateful flows)
CI/CD triggers:   n8n (self-hosted) + GitHub Actions
iOS deployment:   Fastlane → TestFlight
Observability:    LangSmith (free tier)
Vector memory:    ChromaDB (local dev) → Pinecone (production)
Remote access:    Tailscale
Code editor:      Claude Code CLI (primary), VS Code/Cursor (secondary)
Package manager:  uv (recommended) or venv
```

---

## 7. KEY DECISIONS MADE THIS SESSION

- Cowork vs claude.ai: Stayed on claude.ai — Cowork burns quota fast on Pro
- Product surface map: Xcode/Swift → Claude Code CLI | CrewAI/Python → Claude Code CLI | File org/docs → Cowork | Planning → claude.ai | Web tasks → Claude in Chrome
- OpenClaw: Discussed but NOT recommended — security risks, creator joined OpenAI Feb 2026
- Google Drive folder rule: Always write to My Drive/AI/Claude/{project-subfolder}. Never to root or Claude folder directly.
- GitHub Pages: Guide is live and public. After every update → git push → auto-deploys.

---

## 8. PENDING TASKS (next things to build)

- [ ] Quick Reference chapter — one-page command cheatsheet
- [ ] localStorage checkbox persistence — checkboxes reset on page reload currently
- [ ] Mobile-responsive layout — currently desktop only
- [ ] Estimated TL prices in hardware section
- [ ] Add live URL link into the guide header itself
- [ ] Create actual Python agent crew files (not just code shown in guide)
- [ ] Print/PDF version of guide

---

## 9. SESSION PROTOCOL

At START of session:
1. Read INSTRUCTIONS → PROJECT_MEMORY → SNAPSHOT_LOG (last 2 entries)
2. Confirm context to Onur in 2–3 sentences, ask how to proceed

At END of session:
1. Update Section 3 (guide version) and Section 8 (pending tasks) in this document
2. Append a new snapshot entry to SNAPSHOT_LOG
3. Bump guide version number if anything changed

---

## 10. COMMUNICATION NOTES

- Onur types fast and casually — understand intent, don't correct typos
- Prefers tables and structured lists for comparisons
- Appreciates Turkish context where relevant (prices in TL, Turkish store names)
- Direct, practical, no fluff
- Trust his competence — don't over-explain basics
