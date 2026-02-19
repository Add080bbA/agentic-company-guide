SNAPSHOT_LOG
Project Snapshot History — Idiot's Guide to Building a Fully Automated Software Company

For the AI reading this: This is your institutional memory. Every model that works on this project appends a snapshot entry at the BOTTOM before ending the session. Read top to bottom for full history. The most recent entry is always at the bottom.
The append template is at the end of this file. Copy it, fill it in, paste it at the bottom.

---

## HOW TO READ THIS LOG

Each snapshot answers 5 questions:
1. Who — which model, which surface
2. When — date and approximate time (Istanbul)
3. What changed — files modified, chapters added, features built
4. What was decided — choices future models must respect
5. What's next — recommended first action for the next model

---

## SNAPSHOT #001

Date: 2026-02-19
Time: ~16:00–17:30 Istanbul
Model: Claude Sonnet 4.6 (claude-sonnet-4-6)
Surface: claude.ai (web chat)
Session duration: ~4 hours (compacted context, long session)
Triggered by: Onur asked for a step-by-step guide for building an agentic software company

### What Was Built
- Created build_guide.html from scratch — dark-theme interactive HTML helpbook
- 13 chapters (00–12), complete sidebar navigation, interactive checkboxes with progress bar

### What Was Improved (4 rounds of iteration)

| Round | Change | Trigger |
|---|---|---|
| 1 | Fonts: Lora → Plus Jakarta Sans + JetBrains Mono. Size 15.5px → 16px | "quantum bigger, more readable" |
| 2 | Copy buttons on checklist items (inline right) | "copy button missing in checklist" |
| 3 | Chapter 05: Virtual Environments (free tools only) | "add free venv tools" |
| 4 | Turkish hardware shop cards (6 cards, 3-col grid) | "Turkish ecommerce links" |

### What Was Discussed (not built, but decided)
- Product surface map: Claude Code CLI for code, Cowork for files, claude.ai for strategy
- Cowork runs Opus 4.6 but burns quota fast — Onur decided to stay on claude.ai Pro
- OpenClaw discussed and rejected — security risks, creator joined OpenAI
- Google Drive MCP confirmed working — folder rule established: always My Drive/AI/Claude/{subfolder}
- Handoff document system designed: INSTRUCTIONS + PROJECT_MEMORY + SNAPSHOT_LOG

### Files Created/Modified
```
build_guide.html     ← CREATED (v1.1)
INSTRUCTIONS.md      ← CREATED
PROJECT_MEMORY.md    ← CREATED
SNAPSHOT_LOG.md      ← CREATED (this file)
```

### Design Decisions Locked In
- Dark theme only
- Plus Jakarta Sans + JetBrains Mono + Syne fonts
- Copy buttons on both code blocks AND checklist items
- Turkish hardware links stay (6 cards)
- HTML format only
- Google Drive path rule: My Drive/AI/Claude/{project-subfolder} always

### Guide State at End of Session
- Version: v1.1
- Chapters: 13 (all complete)
- Pending tasks:
  - [ ] Quick Reference chapter
  - [ ] localStorage checkbox persistence
  - [ ] Mobile-responsive layout
  - [ ] TL price estimates in hardware section
  - [ ] Upload build_guide.html to Drive
  - [ ] Actual Python agent crew files
  - [ ] Print/PDF version

### Recommended Next Action
Upload build_guide.html to the AgenticCompany-Guide Drive folder, then start v1.2 with the Quick Reference chapter (one-page command cheatsheet) and localStorage persistence for checkboxes.

---

## SNAPSHOT #002

Date: 2026-02-19
Time: ~17:30–18:00 Istanbul
Model: Claude Sonnet 4.6 (claude-sonnet-4-6)
Surface: claude.ai (web chat)
Session duration: ~30 minutes (continuation of same session)
Triggered by: Onur asked to save the guide to Google Drive and host it publicly

### What Was Built
- GitHub repository created: https://github.com/Add080bbA/agentic-company-guide
- GitHub Pages enabled — guide is live at: https://add080bba.github.io/agentic-company-guide/
- Google Drive folder created: My Drive/AI/Claude/AgenticCompany-Guide/ (ID: 1k0Fn18JScroydBgj6_h3GhLWDSKa1ta3)
- INSTRUCTIONS, PROJECT_MEMORY, SNAPSHOT_LOG written to Drive folder
- ai_strategy_master_plan.docx moved back to Claude root folder (was misplaced)
- Stray duplicate INSTRUCTIONS doc trashed

### What Was Discussed
- Google hosting options compared: GitHub Pages won (free, AI-updatable via Claude Code CLI, auto-deploys)
- claude.ai cannot write directly to Mac filesystem — only Cowork and Claude Code CLI can
- Deploy workflow established: update file → git commit → git push → live in 60 seconds
- Memory saved: Google Drive path rule + GitHub repo details

### Files Created/Modified
```
index.html           ← CREATED (renamed from build_guide.html for GitHub Pages)
INSTRUCTIONS         ← CREATED on Google Drive
PROJECT_MEMORY       ← CREATED on Google Drive
SNAPSHOT_LOG         ← CREATED on Google Drive
```

### Design Decisions Made
- File is named index.html in the repo (not build_guide.html) — required for GitHub Pages root URL
- Deploy is always from ~/Projects/Claude/agentic-company-guide/ on Onur's Mac
- After every guide update: push to GitHub → auto-publishes → no manual steps needed

### Guide State at End of Session
- Version: v1.1
- Chapters: 13 (all complete)
- Live URL: https://add080bba.github.io/agentic-company-guide/
- Pending tasks:
  - [ ] Quick Reference chapter
  - [ ] localStorage checkbox persistence
  - [ ] Mobile-responsive layout
  - [ ] TL prices in hardware section
  - [ ] Add live URL link into guide header
  - [ ] Actual Python crew files
  - [ ] Print/PDF version

### Recommended Next Action
Add the live URL as a clickable link in the guide header (top-right, next to progress bar). Then tackle v1.2: localStorage persistence for checkboxes so progress survives page reloads, and the Quick Reference chapter.

---

## APPEND TEMPLATE

When your session ends, copy the block below, fill it in, and paste it above this section.

---

### SNAPSHOT #[last number + 1]

Date: YYYY-MM-DD
Time: ~HH:MM Istanbul
Model: [model name and version]
Surface: [claude.ai / Cowork / Claude Code CLI / other]
Session duration: [approximate]
Triggered by: [Onur's opening request]

### What Was Built
-

### What Was Improved

| Round | Change | Trigger |
|---|---|---|

### What Was Discussed
-

### Files Created/Modified
```
[filename]  ← CREATED / MODIFIED / DELETED
```

### Design Decisions Made
-

### Guide State at End of Session
- Version: vX.X
- Chapters: X (status)
- Pending tasks:
  - [ ] task

### Recommended Next Action
[One paragraph — what should the next model do first?]
