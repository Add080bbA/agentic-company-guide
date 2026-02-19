# SNAPSHOT_LOG.md
## Project Snapshot History — Idiot's Guide to Building a Fully Automated Software Company

> **For the AI reading this:** This is your institutional memory. Every time a model works on this project, it appends a snapshot entry at the BOTTOM of this file before ending the session. Read from top to bottom to understand the full history. The most recent entry is always at the bottom.
>
> **Append template is at the end of this file. Copy it, fill it in, paste it at the bottom.**

---

## HOW TO READ THIS LOG

Each entry answers 5 questions:
1. **Who** — which model, which surface (claude.ai / Cowork / Claude Code CLI)
2. **When** — date and approximate time
3. **What changed** — specific files modified, chapters added, features built
4. **What was decided** — design/architecture choices made that future models must respect
5. **What's next** — what the model recommends as the next action

---

## SNAPSHOT ENTRIES

---

### SNAPSHOT #001
**Date:** 2026-02-19  
**Time:** ~16:00–17:00 Istanbul time  
**Model:** Claude Sonnet 4.6 (`claude-sonnet-4-6`)  
**Surface:** claude.ai (web chat interface)  
**Session duration:** ~3–4 hours (long session, compacted context)  
**Triggered by:** Onur asked for a step-by-step guide for building an agentic software company  

#### What Was Built
- Created `build_guide.html` from scratch — dark-theme interactive HTML helpbook
- 13 chapters (00–12), left-sidebar nav, right content pane
- Interactive checkboxes with progress bar
- Copy-to-clipboard on code blocks

#### What Was Improved (4 rounds of iteration)
| Round | Change | Trigger |
|---|---|---|
| 1 | Switched fonts: Lora → Plus Jakarta Sans + JetBrains Mono. Font size 15.5px → 16px | "Fonts quantum bigger, more readable family" |
| 2 | Added copy buttons inside checklist items (right-aligned) | "Copy button for commands missing in checklist areas" |
| 3 | Added Chapter 05: Virtual Environments (venv, uv, pyenv, conda, direnv) — free tools only | "Include free virtual environment management tools" |
| 4 | Added Turkish e-commerce hardware links (6 shop cards: Apple TR, Hepsiburada, Trendyol, Sahibinden, SaveAsTech, Mac Marketi) | "Provide purchase links for Turkish ecommerce sites" |

#### What Was Discussed (not built, but decided)
- Claude Code CLI vs Cowork vs claude.ai — product surface map given to Onur
- Cowork runs Opus 4.6, claude.ai runs Sonnet 4.6 — Cowork is stronger model for non-code tasks
- Cowork does NOT share memory with claude.ai — hence this handoff document system
- OpenClaw: discussed but NOT recommended (security risks, creator left for OpenAI)
- CrewAI + LangGraph chosen as orchestration stack
- Mac Mini M1 16GB chosen as recommended hardware

#### Files Created/Modified
```
~/Projects/Claude/BuildAgenticCompany/build_guide.html     ← CREATED (v1.1)
~/Projects/Claude/BuildAgenticCompany/INSTRUCTIONS.md      ← CREATED
~/Projects/Claude/BuildAgenticCompany/PROJECT_MEMORY.md    ← CREATED
~/Projects/Claude/BuildAgenticCompany/SNAPSHOT_LOG.md      ← CREATED (this file)
```

#### Design Decisions Locked In (do not change without asking Onur)
- Dark theme only (`--bg: #0d0f14`)
- Font: Plus Jakarta Sans body, JetBrains Mono code, Syne headings
- Copy buttons on BOTH code blocks AND checklist items
- Turkish hardware links stay (6 cards, 3-column grid)
- No Word docs — HTML only
- Guide version numbering: v1.x for content additions, v2.x for structural overhauls

#### Guide State at End of Session
- **Version:** v1.1
- **Chapters:** 13 (all complete)
- **Pending tasks identified:**
  - [ ] Quick Reference chapter (command cheatsheet)
  - [ ] localStorage checkbox persistence (survive page reload)
  - [ ] Mobile-responsive layout
  - [ ] Print/PDF version
  - [ ] Upload to Google Drive (MCP connector available)
  - [ ] Actual Python files for the agent crew (not just code in guide)
  - [ ] Estimated TL prices in hardware section

#### Recommended Next Action
Upload `build_guide.html` to Google Drive folder `12Dw1xfVcKbPQLnYfq6gR79fem765EMnr`, then tackle the Quick Reference chapter as v1.2.

---

### SNAPSHOT #002
**Date:** YYYY-MM-DD  
**Time:** ~HH:MM Istanbul time  
**Model:** [e.g. Claude Opus 4.6 / Claude Sonnet 4.6 / GPT-4o / etc.]  
**Surface:** [claude.ai / Cowork / Claude Code CLI / Claude in Chrome]  
**Session duration:** [approximate]  
**Triggered by:** [what Onur asked for at the start of this session]  

#### What Was Built
- 

#### What Was Improved
| Round | Change | Trigger |
|---|---|---|
| 1 | | |

#### What Was Discussed
- 

#### Files Created/Modified
```
[list files with CREATE / MODIFIED / DELETED]
```

#### Design Decisions Made
- 

#### Guide State at End of Session
- **Version:** vX.X
- **Chapters:** [count] ([status])
- **Pending tasks:**
  - [ ] 

#### Recommended Next Action
[What should the NEXT model do first when it opens this project?]

---

## APPEND TEMPLATE

When your session ends, copy everything below the dashes, fill it in, and paste it at the bottom of this file above this section.

```
---

### SNAPSHOT #[INCREMENT LAST NUMBER BY 1]
**Date:** YYYY-MM-DD  
**Time:** ~HH:MM Istanbul time  
**Model:** [model name and version]  
**Surface:** [claude.ai / Cowork / Claude Code CLI / other]  
**Session duration:** [approximate]  
**Triggered by:** [Onur's opening request]  

#### What Was Built
- 

#### What Was Improved
| Round | Change | Trigger |
|---|---|---|

#### What Was Discussed
- 

#### Files Created/Modified
\`\`\`
[filename]  ← CREATED / MODIFIED / DELETED
\`\`\`

#### Design Decisions Made
- 

#### Guide State at End of Session
- **Version:** vX.X  
- **Chapters:** X (status)  
- **Pending tasks:**  
  - [ ] task  

#### Recommended Next Action
[one paragraph — what should the next model do first?]
```
