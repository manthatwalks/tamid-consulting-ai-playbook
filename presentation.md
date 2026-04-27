# TAMID Consulting AI Playbook

**5–7 minute presentation deck**
Format: Gamma-compatible markdown. Paste into [gamma.app](https://gamma.app) → "Generate" → "Paste in text" to auto-build the deck. Each `---` is a slide break. Speaker notes are in `> blockquote` form below each slide.

---

# TAMID Consulting AI Playbook

A practical AI toolkit for TAMID consulting teams.

**Follow along →** `[YOUR DEPLOYED URL]`

> **Speaker notes (~30 sec):** "Before I start, pull out your phone or laptop and open this link. Everything I'm about to walk through is on the site, so you can follow along, click into anything that catches your eye, and have it as a reference after the session. The site is the project. The slides are the tour."

---

## The Problem

AI usage across TAMID chapters is **inconsistent and shallow**.

- **Tool Choice** — teams default to whichever interface or tool they heard about or popped up first, not necessarily the right tool for the task.
- **Source Discipline** — numbers go into decks unsourced; hallucinated statistics survive into client deliverables.
- **Quality Variance** — output ranges from excellent to obviously generic, sometimes within the same project.

> **Speaker notes (~45 sec):** "Every TAMID chapter is using AI right now in some form. The question isn't whether to use it — it's whether we use it well. Right now, most of us don't. Different teams pick different tools for the same task, often based on what they happened to hear about. Numbers go into decks unsourced. And quality varies wildly even within a single project. This playbook addresses that gap."

---

## Our Deliverables

1. **The Playbook** — research-paper-style reference for model selection, research workflows, synthesis, slide drafting, and ethics.
2. **The Prompt Library** — five prompt workflows for the most common TAMID tasks.
3. **The Workshop** — a 20–30 min interactive lesson, structured as a live case sprint.
4. **The Rollout Guide** — how to push the playbook through TAMID's existing chapter structure.

> **Speaker notes (~35 sec):** "Four deliverables, designed to work together. The playbook is the reference. The prompt library is the daily-use tool. The workshop is how a chapter learns to use it. The rollout guide is how it spreads through the chapter. On the site, each one is its own clickable section."

---

## Inside the Playbook — Models

The right model for the right task. This changes quarterly; we link to the live source on the site.

| Task | Recommended models |
|------|---------------------|
| Deep reasoning | Claude Opus 4.7 · GPT-5.5 |
| Daily drafting | Claude Sonnet 4.6 |
| Fast / shallow work | Kimi K2 · Claude Haiku |
| Long context (200k+) | Gemini 3.1 Pro |
| Cited web research | Perplexity Pro |

*Live reference: artificialanalysis.ai*

> **Speaker notes (~50 sec):** "Most consultants pick a model the way you pick a coffee shop — whichever one's closest. The playbook tells you which one is actually right for what you're doing. Deep reasoning work — financial logic, strategic frameworks — go to Opus or GPT 5.5. Daily drafting, Sonnet 4.6. Long context, like loading an entire client data room, only Gemini 3.1 Pro can handle that. And anything that needs citations, you should be using Perplexity, not raw ChatGPT. The models change every quarter so we link to a live ranking on the site."

---

## Inside the Playbook — Tools by Workflow

| Workflow | Tools |
|----------|-------|
| Competitive Analysis | OpenAI Deep Research · Gemini Deep Research · Exa.ai · AlphaSense |
| Data Synthesis | NotebookLM · Granola · ChatGPT ADA · Claude Code |
| Slide Drafting | Gamma · Plus AI · Napkin.ai · Mermaid |
| Risk + Ethics | Enterprise tiers · source grading · citation integrity |

> **Speaker notes (~40 sec):** "Beyond model selection, every section of the playbook names the actual services to use. NotebookLM, for example, is dramatically underused by TAMID — it's purpose-built for synthesizing twenty interview transcripts and won't hallucinate outside the source set. Napkin.ai turns prose into professional diagrams in seconds. The playbook tells you what to reach for, and when."

---

## The Prompt Library

Five workflows. Every prompt has inputs, when to use it, and how to validate the output.

- **Market sizing** — TAM/SAM/SOM with assumption tables and source grading
- **Customer segmentation** — actionable segments, not demographic wallpaper
- **SWOT** — evidence-backed and company-specific
- **Financial modeling logic** — structure first, numbers second
- **Interview synthesis** — themes, verbatim quotes, dissent

> **Speaker notes (~30 sec):** "These are the prompts you can copy-paste tomorrow. Each one is engineered to force the model to do the things it's bad at by default — citing sources, flagging weak assumptions, refusing to invent quotes. Click into the prompt library on the site to see all five in full."

---

## Chapter Rollout

**Adoption is just distribution.** TAMID's existing structure does the work.

1. **Director of Consulting** — sends the playbook to Project Leads at semester kickoff.
2. **Project Leads** — read it, brief their teams on the parts that apply.
3. **Project Members** — use it on real client work.

> **Speaker notes (~30 sec):** "We don't need a special program for this. The Director of Consulting sends the playbook to Project Leads at the start of the semester. Project Leads read it and brief their teams on the parts that apply to their engagement. Members use it on real work. Three roles, three responsibilities. That's it."

---

## Take It With You

**TAMID Consulting AI Playbook →** `[YOUR DEPLOYED URL]`

- Read the full playbook
- Copy any prompt
- Run the rollout in your chapter

*Questions?*

> **Speaker notes (~20 sec):** "Everything I just walked through is at this link. The playbook, the prompt library, the rollout guide — all of it. If you take one thing from this session, take the link. Open to questions."

---

## Notes on Timing

- 8 slides, ~30–50 sec each → **~5 min** with comfortable pacing
- Add 1–2 min for live demo of the site (click through Playbook → Prompts → one prompt example) → **~6–7 min total**
- Q&A buffer separate

## Notes on Delivery

- **Slide 1:** Pause for ~10 seconds while people open the link. Don't talk through it.
- **Slides 4 + 5 (the tables):** These are the densest slides. Don't read them — point at one row (e.g., NotebookLM) and tell the story behind it.
- **Slide 7 (Rollout):** Lean on TAMID's existing structure as the punchline — "we don't need to invent a program; the chapter already has one."
- **Slide 8:** End on the link, not on "thank you." The link is the action you want them to take.

## Replace Before Presenting

- `[YOUR DEPLOYED URL]` appears on slide 1 and slide 8. Deploy the site (Vercel or Netlify — drag-and-drop, ~1 min, free) and paste the URL in both places.
- Optional: generate a QR code from the deployed URL and add it to slide 1 for in-room viewing.
