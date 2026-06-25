# ai-workflow-skills

Claude skills for software project planning, team collaboration, and AI coding workflows.

---

## Skills Overview

| Skill | Phases | Token Usage | Recommended? |
|-------|--------|-------------|--------------|
| [project-planning-5phase](#-project-planning-5phase--5-phases) | 5 | 🟡 Medium | ⭐ YES — Start here |
| [team-collaboration-workflow](#-team-collaboration-workflow--7-steps) | 7 | 🟠 High | ⚠️ High token use |
| [advanced-sdlc-workflow](#-advanced-sdlc-workflow--19-phases) | 19 | 🔴 XHigh | ⚠️ Very high token use |
| [ai-coding-multi-agent-workflow](#-ai-coding-multi-agent-workflow--28-phases) | 28 | 🟣 Advanced | ⚠️ Extreme token use |

---

## ⭐ project-planning-5phase — 5 Phases

> **RECOMMENDED — Start with this one**
> **Token usage: 🟡 Medium**

The core project planning workflow. Best balance of depth and token cost.
Covers everything you need before writing a single line of code.

**Phases:**
1. Requirements & Scope
2. Architecture Planning
3. Code Planning
4. Implementation Plan
5. Execution Infrastructure

**When to use:** Solo or team projects, any stack, any size. If you don't know which skill to use — use this one.

---

## ⚠️ team-collaboration-workflow — 7 Steps

> **Token usage: 🟠 High — not recommended for quick sessions**

Structured team collaboration setup covering roles, architecture planning process,
task ownership, communication, Git workflow, progress tracking, and sprint reviews.
Includes the most common group failure points and fixes.

**Steps:**
1. Define Roles Before Anything
2. Collaborative Architecture Planning
3. Task Breakdown + Ownership
4. Communication Structure
5. Git Workflow for Teams
6. Progress Tracking
7. Review Cycles

**When to use:** Setting up a new dev team, group project kickoff, team of 2+ people.
**Avoid when:** Solo project or quick planning session — use the 5-phase skill instead.

---

## ⚠️ advanced-sdlc-workflow — 19 Phases

> **Token usage: 🔴 XHigh — not recommended unless you need full SDLC coverage**

Professional-grade end-to-end SDLC with corrected phase order, explicit gate criteria,
and 10 documented feedback loops. POC before detailed design. Testing strategy before
implementation. Security embedded early.

**Phases:**
Requirements → Feasibility Study → High-Level Architecture → POC → Architecture Validation
→ Security/Threat Modeling → Detailed Design → Testing Strategy → Implementation Planning
→ Code Architecture Review → Implementation → Continuous Verification → Architecture
Conformance Check → Test Execution → Requirements Validation → Risk Review →
Release Readiness → Deployment → Post-Release Monitoring

**When to use:** Full team product delivery, client projects, anything going to production.
**Avoid when:** Prototypes, quick builds, solo side projects — use 5-phase instead.

---

## ⚠️ ai-coding-multi-agent-workflow — 28 Phases

> **Token usage: 🟣 Advanced — extremely high token consumption, use with care**

Multi-agent collaborative workflow where N agents (2–7) work through all 28 phases of an
advanced AI coding architecture. All agents work the same phase simultaneously, debate it,
surface disagreements with specific problems and fixes, and must reach full consensus before
advancing. Includes 8 AI-specific phases not present in traditional workflows.

**Agents available:** Tech Lead, Architect, Security Engineer, QA Lead, Product Manager,
DevOps Engineer, AI/ML Engineer

**Phases:** All 19 SDLC phases + Spec Writing, Knowledge Base/RAG Setup,
Prompt Engineering + Context Chunking, Prompt Version Control,
Human-in-the-Loop Gate Definition, Multi-Agent Task Distribution,
AI Code Review per Chunk, AI Output Logging, Retrospective

**When to use:** AI-powered projects with multiple collaborators, when you need every phase
stress-tested from multiple expert perspectives.
**Avoid when:** Solo builds, tight token budgets, simple projects — use 5-phase instead.

---

## Token Usage Guide

```
🟡 Medium   — project-planning-5phase       ~2,000–5,000 tokens per session
🟠 High     — team-collaboration-workflow   ~5,000–10,000 tokens per session
🔴 XHigh    — advanced-sdlc-workflow        ~10,000–25,000 tokens per session
🟣 Advanced — ai-coding-multi-agent         ~25,000–80,000 tokens per session
```

If you are unsure which to use: **start with the 5-phase skill.**
You can always switch to a more detailed skill if you need more depth.

---

## Install

Download the `.skill` file and install it in Claude Code or your Claude environment.
