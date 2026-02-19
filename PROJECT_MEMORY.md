# PROJECT_MEMORY.md
## Handoff Brief — Idiot's Guide to Building a Fully Automated Software Company

> **For the AI reading this:** This document was written by Claude Sonnet 4.6 on February 19, 2026 to preserve full context of a multi-session project with user Onur Dikyar (İzmir, Turkey). Read this entire document before responding to the user. You are continuing ongoing work — not starting fresh.

---

## 1. WHO IS THE USER

**Name:** Onur  
**Location:** İzmir, Turkey  
**Timezone:** Europe/Istanbul  
**Technical level:** Intermediate — comfortable with Terminal, Git, npm, Python basics. Not a professional developer but technically curious and learning fast.  
**Primary goal:** Build a fully automated agentic software company that ships iOS apps with minimal human involvement.  
**Hardware:** Likely Mac Mini M1 (16GB) — this was the primary recommendation given. May not have it yet, still planning/purchasing phase.  
**Current tools:** Claude.ai (claude.ai), Claude Desktop, Google Drive MCP integrated.  
**Subscriptions:** Claude Pro ($20/mo) — access to Cowork research preview.  
**Communication style:** Casual, concise messages. Typos are normal (e.g. "wprk" = "work"). Appreciates direct, structured answers with practical commands and links.

---

## 2. WHAT THIS PROJECT IS

A **step-by-step HTML helpbook** titled:

> *"The Idiot's Guide to Building a Fully Automated Software Company"*

It is a self-contained interactive HTML file with:
- Dark theme (bg: #0d0f14)
- Left sidebar navigation with 13 chapters (00–12)
- Right content pane with full chapter content
- Interactive checkboxes with progress bar tracking in header
- Copy-to-clipboard buttons on code blocks AND inline checklist commands
- Keyboard navigation (arrow keys between chapters)
- Turkish purchase links for hardware
- Learning resource links throughout

**Font stack:** Plus Jakarta Sans (body) + JetBrains Mono (code/UI) + Syne (headings)

---

## 3. CURRENT STATE OF THE GUIDE

### Chapters Written (all complete):

| # | Title | Status |
|---|---|---|
| 00 | Introduction & Vision | ✅ Complete |
| 01 | Prerequisites | ✅ Complete |
| 02 | Hardware & Machine | ✅ Complete — includes Turkish e-commerce links |
| 03 | Accounts & API Keys | ✅ Complete |
| 04 | Claude Code CLI | ✅ Complete |
| 05 | Virtual Environments | ✅ Complete — covers venv, uv, pyenv, conda, direnv |
| 06 | Choose Framework (CrewAI + LangGraph + n8n) | ✅ Complete |
| 07 | Build Agent Team | ✅ Complete — 3-agent crew Python code |
| 08 | CI/CD Automation | ✅ Complete — GitHub Actions + Fastlane |
| 09 | Memory & Persistence | ✅ Complete — ChromaDB + Pinecone |
| 10 | Monitoring & Costs | ✅ Complete — LangSmith + cost tables |
| 11 | Security & Safety | ✅ Complete |
| 12 | Go Live & Scale | ✅ Complete — phased timeline |

### Current Version: v1.1

---

## 4. FILE LOCATIONS

| File | Location |
|---|---|
| HTML Helpbook (main deliverable) | `~/Projects/Claude/BuildAgenticCompany/build_guide.html` |
| This memory file | `~/Projects/Claude/BuildAgenticCompany/PROJECT_MEMORY.md` |
| Entry point for AI | `~/Projects/Claude/BuildAgenticCompany/INSTRUCTIONS.md` |
| Google Drive copy | AI/Reports/Claude folder (ID: 12Dw1xfVcKbPQLnYfq6gR79fem765EMnr) |

> **Note for Cowork:** The `build_guide.html` is also copied here. You can open, read, and edit it directly from this folder.

---

## 5. DESIGN DECISIONS MADE (don't change these without asking Onur)

- **Dark theme only** — user prefers dark UI
- **Font:** Plus Jakarta Sans for body text (switched from Lora after feedback "more readable"). JetBrains Mono for all code/monospace.
- **Font size:** 16px base, 1.85 line-height — bumped up from original 15.5px after feedback "quantum bigger"
- **Copy buttons:** Present on BOTH code blocks (top-right of block) AND individual checklist items (inline right side). This was added after user feedback.
- **Turkish hardware links:** 6 shop cards in a 3-column grid — Apple TR, Hepsiburada, Trendyol, Sahibinden, SaveAsTech, Mac Marketi. Keep these.
- **Virtual Environments chapter:** User specifically requested free tools only. Four covered: venv (built-in), uv (fastest), pyenv (multi-version), conda/miniconda.
- **No word docs** — user asked "it doesn't have to be Word" and we moved to HTML format. Keep as HTML.

---

## 6. TECH STACK RECOMMENDED TO ONUR

This is what the guide teaches and what Onur is building toward:

```
Primary AI:          Claude Sonnet 4.6 (code), Opus 4.6 (PM agent decisions)
Cheap tasks:         Claude Haiku 4.5
Design agent:        GPT-4o + DALL-E
Orchestration:       CrewAI (role-based), LangGraph (complex stateful flows)
CI/CD triggers:      n8n (self-hosted) + GitHub Actions
iOS deployment:      Fastlane → TestFlight
Observability:       LangSmith (free tier)
Vector memory:       ChromaDB (local dev) → Pinecone (production)
Remote access:       Tailscale
Code editor:         Claude Code CLI (primary), VS Code/Cursor (secondary)
Package manager:     uv (recommended) or venv
```

**Hardware recommendation given:** Mac Mini M1 16GB (used, from Turkish market: Sahibinden/SaveAsTech/Mac Marketi, ~20,000–28,000 TL)

---

## 7. WHAT WAS DISCUSSED (key decisions in session)

1. **Model comparison:** Claude Pro recommended as primary. Claude Sonnet 4.6 is best for iOS coding (77.2% SWE-bench). Gemini 2.5 Flash cheapest for bulk tasks. DeepSeek R1 for budget fallback.

2. **Multi-agent frameworks:** CrewAI (primary orchestration) + LangGraph (complex workflows). AutoGen/Microsoft now merged with Semantic Kernel.

3. **OpenClaw:** Discussed but NOT recommended for this project. Security concerns (prompt injection documented by CrowdStrike). Creator Peter Steinberger joined OpenAI Feb 2026. Use only if Onur is comfortable with Node.js and API key security on isolated machine.

4. **Cowork vs Claude Code:** Claude Code CLI is the right tool for actual code. Cowork is better for file organization, document creation, non-code tasks. This chat (claude.ai) for planning/strategy.

5. **Product surface map given to Onur:**
   - Xcode/Swift code → Claude Code CLI
   - CrewAI agents/Python → Claude Code CLI
   - File org/docs → Cowork
   - Planning/strategy → claude.ai
   - Web tasks/App Store → Claude in Chrome

6. **Google Drive MCP:** Successfully integrated in a previous session. Google Drive MCP server running at `/Users/onurdikyar/mcp-googledocs/dist/index.js`. Token at `~/.config/google-docs-mcp/token.json`.

7. **AI Strategy Master Plan:** A full Word document was created earlier and moved to Google Drive (AI/Reports/Claude folder). The HTML guide is the evolution of this.

8. **Kali WiFi adapters spreadsheet:** User had two versions. Older one was trashed, newer kept. (Unrelated to this project but part of the session history.)

---

## 8. THINGS ONUR ASKED FOR THAT STILL NEED DOING

These were not yet built — potential next tasks:

- [ ] **Save/export the HTML guide to Google Drive** (he has the MCP connector working)
- [ ] **Add a "Quick Reference" chapter** — one-page cheatsheet of all commands
- [ ] **Add estimated TL prices** next to the Turkish hardware shop cards (prices change but ballpark helps)
- [ ] **Print/PDF version** of the guide (user might want to print it)
- [ ] **Mobile-responsive version** of the guide (currently desktop-only layout)
- [ ] **Dark/light mode toggle** (not requested but would be a nice addition)
- [ ] **Progress persistence** — currently checkboxes reset on page reload. Could use localStorage to persist.
- [ ] **Agent crew code files** — the guide shows code but doesn't create the actual Python files in the project folder
- [ ] **Start actually setting up CrewAI** on Onur's machine (guide is written, now implement it)

---

## 9. HOW TO CONTINUE THIS PROJECT

### If Onur says "carry on" or "continue the guide":
Read the HTML file at `build_guide.html` in this folder, understand the current structure, and ask what chapter or feature he wants to work on next. Suggest from the pending list above.

### If Onur wants to add a new chapter:
Follow the existing HTML pattern exactly:
1. Add nav item in sidebar with correct chapter number
2. Add `<div class="page" id="page-CHAPTERID">` in main content
3. Use `.section-header` > `.section-num` + `.section-info` structure
4. Use `.checklist` with `.check-item` elements including `check-copy` buttons where relevant
5. Add `.page-nav` with Back and Next buttons at bottom
6. Add the page ID to the `pageOrder` array in the `<script>` section

### If Onur says "update the guide":
Edit `build_guide.html` in this folder directly. Save it. Tell him what changed.

### If Onur asks about pricing:
- Claude Pro: $20/mo | Claude Max 5×: $100/mo | Claude Max 20×: $200/mo
- API: Sonnet 4.6 = $3/1M input, $15/1M output | Haiku 4.5 = ~$0.80/$4 | Opus 4.6 = $15/$75
- Turkish TL prices fluctuate — check current rates before quoting

### If Onur wants to upload to Google Drive:
Use the Google Docs MCP tools available. Target folder ID: `12Dw1xfVcKbPQLnYfq6gR79fem765EMnr`

---

## 10. PERSONALITY & COMMUNICATION NOTES

- Onur types fast and casually. Don't correct typos, just understand intent.
- He prefers **direct answers** over lengthy explanations.
- He likes things **practical** — real commands, real links, real prices.
- He responds well to **structured tables and bullet points** for comparisons.
- He appreciates **Turkish-language context** where relevant (hardware prices, store names).
- He may switch between English and implicit Turkish context (e.g. asking about Turkish e-commerce sites).
- Don't over-explain things he already knows. Trust his competence.

---

## 11. SESSION METADATA

- **Original session date:** February 19, 2026
- **Claude version that wrote this:** Claude Sonnet 4.6 (claude-sonnet-4-6)
- **Total session context:** AI model strategy → multi-agent frameworks → OpenClaw → agent company architecture → Google Drive MCP setup → HTML helpbook creation → 4 rounds of improvements
- **Guide version at handoff:** v1.1
- **Next suggested version:** v1.2 — add Quick Reference chapter + localStorage checkbox persistence

---

## 12. SESSION PROTOCOL — WHAT TO DO EACH SESSION

**At the START of a session:**
1. Read `INSTRUCTIONS.md` (entry point)
2. Read `PROJECT_MEMORY.md` (this file — full context)
3. Read `SNAPSHOT_LOG.md` — scan from top, read the last 1–2 snapshots closely
4. Confirm to Onur what you understood and ask how to proceed

**At the END of a session:**
1. Update Section 8 of this file (pending tasks — tick completed, add new ones)
2. Update Section 6 (guide version number if it changed)
3. Append a new snapshot entry to `SNAPSHOT_LOG.md` using the template at the bottom of that file
4. Save all files

> **For detailed per-session change history, see `SNAPSHOT_LOG.md`** — that file has the full structured log of what each model did, what was decided, and what to do next.
