# TAMID Consulting AI Playbook — Workshop Deck

**20–30 minute interactive workshop**
Format: Gamma-compatible markdown. Paste into [gamma.app](https://gamma.app) → "Generate" → "Paste in text" to auto-build the deck. Each `---` is a slide break. Speaker notes are in `> blockquote` form below each slide.

This is a hands-on session, not a lecture. Participants should have a laptop open with at least one AI tool (ChatGPT, Claude, or Perplexity) accessible.

---

# Live Case Sprint
## AI-Powered Consulting in 20 Minutes

**Follow along →** tamid-consulting-ai-playbook.vercel.app

> **Speaker notes (~30 sec):** "We're not going to lecture. We're going to run a real TAMID brief together, in real time, using the tools from the playbook. By the end of this session you'll have seen — and tried — the full pipeline that the playbook describes. Pull out your laptop and open at least one AI tool."

---

## The Deal

In the next 20 minutes we'll run a full TAMID engagement using AI:

1. **Research** the market (Perplexity)
2. **Synthesize** the findings (NotebookLM)
3. **Build** the storyline (Claude)
4. **Draft** the deck (Gamma)

You'll do each step alongside me on your own machine.

> **Speaker notes (~45 sec):** "A normal TAMID engagement on a brief like the one we're about to run takes 3–4 weeks. We're going to compress the research-to-first-draft pipeline into about 20 minutes — not because that's how you should actually do it for a client, but to show you what each tool does best and where they hand off to each other. By the end you'll have a real artifact to take with you."

---

## Before / After

A real market sizing claim from a TAMID deck. Which version would you trust?

**Version A:**
> *"The US plant-based protein market is large and growing rapidly, presenting significant opportunity for Wilkin's expansion."*

**Version B:**
> *"The US plant-based protein market reached $8.4B in 2024 (Good Food Institute, Source A) and is projected to grow at 11% CAGR through 2030 (Bloomberg Intelligence, Source A). Wilkin's premium-tier TAM is $2.1B. Bottom-up: 0.05% household penetration → $4M ARR in Year 1."*

> **Speaker notes (~3.5 min):** "Take 30 seconds — discuss with the person next to you. Which one would survive a client question, and what specifically makes the difference?"
>
> *Then surface answers from the room. Highlight: specificity, named sources, source grading (A/B/C), bottom-up math shown. Land the punchline: Version A is what you get from a one-shot AI prompt with no structure. Version B is what you get when you use the playbook. Same tool, completely different output. The difference is the discipline."*

---

## Today's Brief

**Wilkin's** — an Israeli plant-based protein startup — wants to enter the US market.

Your TAMID team has 4 weeks to deliver:

- US market opportunity (size, growth, segments)
- Competitive landscape
- Recommended go-to-market channel (DTC / retail / foodservice)

**Today, in 20 minutes, we'll do the first-pass research and storyline.**

> **Speaker notes (~1 min):** "This is a realistic TAMID brief. The kind you'd actually get assigned. We're not going to finish the engagement today — we're going to do the part where most teams currently spend three days, in twenty minutes."

---

## Stage 1 · Research with Perplexity

I'll demo. You follow along.

**Open** [perplexity.ai](https://perplexity.ai) → switch to **Deep Research** mode

**Paste this prompt:**

```
Research the US plant-based protein market.
Cover: total market size 2024, growth projections 2025-2030,
top 5 competitors with their positioning, key consumer segments,
and the dominant retail channels.
Cite every claim.
```

> **Speaker notes (~3 min):** "Watch what Perplexity does — it doesn't just answer. It opens 30+ tabs, reads them, and gives you a cited report. Every number traces back to a source you can check. Compare this to asking ChatGPT the same question — you'd get a confident answer with no citations and probably some hallucinated stats. While it runs, talk through the playbook's principle: cited research is non-negotiable. We use Perplexity here, not raw ChatGPT, because the deliverable will need to defend itself."
>
> *While Perplexity runs (~2 min), keep the room engaged. Ask: how long would this research normally take you?*

---

## Stage 2 · Synthesize with NotebookLM

Now we have research from Perplexity, plus 3 industry reports the team already pulled.

**Open** [notebooklm.google.com](https://notebooklm.google.com) → **New Notebook**

**Upload** all 4 sources → **ask:**

```
What are the 5 most important findings across these sources?
For each, quote the source verbatim and grade it A/B/C
based on source quality.
Flag any contradictions between sources.
```

> **Speaker notes (~3.5 min):** "NotebookLM is the most underused tool in TAMID. It will not hallucinate outside the source set you give it — every claim it makes is grounded. This is exactly what you want for synthesis. Watch how it surfaces contradictions across sources, which is the most valuable signal in any research project. Have participants follow along on their own machine if they have NotebookLM access."

---

## Stage 3 · Storyline with Claude

**Your turn.** This is the prompt-improvement exercise.

Below is a weak prompt asking Claude to recommend a channel. **Improve it** in pairs for 3 minutes, then we'll compare.

```
What's the best channel for Wilkin's to enter
the US market — DTC, retail, or foodservice?
```

What's missing? What would force Claude to give you a defensible answer instead of a generic one?

> **Speaker notes (~5 min):** "Give participants 3 minutes in pairs. Then surface 2-3 attempts from the room. Reveal a strong version (next slide). The point isn't 'who wrote the best prompt' — it's that the same model produces wildly different output depending on how you frame the request. The playbook codifies this so you're not reinventing it every time."

---

## What "Good" Looks Like

```
You are advising Wilkin's, a premium Israeli plant-based protein
startup, on US market entry. They have $2M to deploy in Year 1.

Recommend ONE primary channel (DTC, retail, or foodservice).

For each option, evaluate:
- Capital required to reach $1M ARR
- Time to first revenue
- Defensibility (how easily can a competitor copy?)
- Strategic fit with a premium positioning

Then recommend ONE option and defend it in 3 sentences.
Flag the single biggest risk to your recommendation.

Do not recommend "a hybrid approach" — force a choice.
```

Notice: forced choice, evaluation criteria, defensibility check, risk flag.

> **Speaker notes (~1.5 min):** "Walk through what makes this version different. The 'do not recommend a hybrid' line is doing real work — without it, Claude will hedge. Every prompt in the library has constraints like this baked in."

---

## Stage 4 · Draft the Deck with Gamma

**Open** [gamma.app](https://gamma.app) → **Generate**

Paste your storyline (the recommendation + 5 supporting findings) into Gamma. Watch it build a deck in 30 seconds.

This is your **first draft**, not your final deck. You'll restyle it, fix the visuals, and add real charts. But the painful "what should this slide look like" decisions are done.

> **Speaker notes (~2 min):** "Show this live. Have one slide open in Gamma showing what came out. Be honest about where Gamma is good (layout, structure, action titles) and where it's bad (generic visuals, lazy bullet points). The point is that Gamma collapses 3 hours of slide setup into 30 seconds — and that's enough."

---

## Closer · Tool Showdown

We just used 4 tools sequentially. But for any single research question, **which AI is best?**

Same prompt, three tools:

> *"Which retail chains in the US carry premium plant-based protein bars?"*

Run it in:
- **OpenAI Deep Research** (deepest, slowest, ~15 min)
- **Gemini Deep Research** (longest output, integrates with Docs)
- **Perplexity Deep Research** (fastest, best citations)

Same question. Three different shapes of answer.

> **Speaker notes (~3 min):** "Show the three outputs side-by-side if you've prepped them, or just have participants open one of each on their phone. The point is tool selection — there's no universal winner. The playbook tells you which tool to reach for based on the shape of the question. Speed vs. depth vs. citation quality is a real tradeoff and you should make it deliberately."

---

## What You Just Learned

In 20 minutes, you ran the full playbook:

✓ Cited research (Perplexity, not raw ChatGPT)
✓ Grounded synthesis (NotebookLM, not summarization-by-prompt)
✓ Engineered prompts (forced choices, defined output, risk flags)
✓ Fast deck drafting (Gamma, then refine)
✓ Tool selection by task (not by habit)

> **Speaker notes (~1 min):** "Everything we did is in the playbook. You don't have to remember it — you have to use it. That's the only thing that makes the difference."

---

## Take It With You

**TAMID Consulting AI Playbook**

tamid-consulting-ai-playbook.vercel.app

The playbook · The prompt library · The rollout guide
All linked from the homepage.

*Questions?*

> **Speaker notes (~30 sec):** "Bookmark the link. Bring it to your next project meeting. The playbook only works if you actually pull it up when you're sitting down to do real work."

---

## Facilitator Notes

### Total timing
- Opener (Title + Deal + Before/After): ~5 min
- Stage 1 (Perplexity): ~3 min
- Stage 2 (NotebookLM): ~3.5 min
- Stage 3 (Claude prompt exercise): ~5 min
- Stage 4 (Gamma): ~2 min
- Closer (Tool Showdown + recap + link): ~5 min
- **Total: ~23–25 min** (fits comfortably in the 20–30 min target)

### What to prepare in advance
1. **Perplexity Deep Research output** for the Wilkin's market query — pre-run it so you can show the result instantly if the live run is slow.
2. **NotebookLM notebook** with the 3 industry reports + Perplexity output already loaded.
3. **Gamma deck** drafted from a sample storyline so you have a fallback if the live demo doesn't render.
4. **Tool Showdown comparison** — pre-run the same query in OpenAI/Gemini/Perplexity Deep Research and have screenshots ready. The live runs are too slow for a workshop.

### Required tool access for participants
- Minimum: ChatGPT or Claude account (free tier OK)
- Recommended: Perplexity Pro (5-day free trial covers this)
- Bonus: NotebookLM (free with Google account)

### If running asynchronously (recorded session)
Keep the prompt-improvement exercise (Stage 3) — pause the recording and ask viewers to actually try it before unmuting. Self-paced versions of this workshop work, but only if the exercise is preserved as a real exercise, not a passive watch.

### Replace before recording
- All instances of "tamid-consulting-ai-playbook.vercel.app" — confirm URL is current.
- The Wilkin's brief — substitute with a real TAMID engagement if you want; just keep the same shape (Israeli startup, US market entry, 4-week timeline).
