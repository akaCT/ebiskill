<div align="center">

<img src="https://ebiskill.com/ebi-demo.gif" alt="EBI improving a page round by round" width="760" />

# EBI — Even Better If

**The recursive improvement loop for everything you make. With AI, or without it.**

[![Website](https://img.shields.io/badge/website-ebiskill.com-22ff88?style=flat-square)](https://ebiskill.com)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](./LICENSE)
[![Works with any LLM](https://img.shields.io/badge/works%20with-Claude%20·%20GPT%20·%20Gemini%20·%20any%20LLM-9d7bff?style=flat-square)](https://ebiskill.com)
[![GitHub stars](https://img.shields.io/github/stars/akaCT/ebiskill?style=social)](https://github.com/akaCT/ebiskill/stargazers)

[**Try it →**](#quickstart) · [**See it run →**](https://ebiskill.com) · [**Recipes →**](https://github.com/akaCT/awesome-ebi-loops) · [**How it works →**](#the-loop)

</div>

---

## Why EBI exists

AI doesn't have an intelligence problem — it has a **self-correction problem.** It produces a first draft and stops. It repeats the same mistakes. It rarely asks, *"how could this be even better?"*

**EBI** is a tiny, recursive process that makes any agent — or any human with any model — critique and improve its own work on a loop, until it's genuinely better. One sentence to learn. Works anywhere.

- **Recursive, not one-shot** — round 5 finds what round 1 couldn't.
- **Tool-agnostic** — Claude, GPT, Gemini, Llama… even pen & paper.
- **Two ways in** — install it as an agent skill, or paste one prompt into any chat.
- **Can't regress** — its one rule is *never ship a version worse than the last.*
- **Self-proving** — [ebiskill.com](https://ebiskill.com) was built with EBI and shows its own rounds.

## The whole idea, in 6 words

> Don't ask *what's wrong.*
> Ask *what would make it even better.*

"What's wrong?" triggers defensiveness — you defend, you patch, the work stays the same shape. "Even better if…?" triggers creativity — you imagine, you reach, the work gets a level better. **Every round.**

## Quickstart

**Option A — install the skill** (for Claude Code, Codex, Gemini CLI & friends):

```bash
git clone https://github.com/akaCT/ebiskill.git
# copy the ebi-process/ folder into your agent's skills directory
```

Then just say **`EBI`** after any piece of work.

**Option B — paste this into any chat** (Claude, GPT, Gemini, anything):

> Run an EBI pass (Even Better If) on what you just made: (1) name what's working, (2) list 5–10 sharp "even better if…" improvements ranked by impact, (3) apply the ones I pick, (4) then offer to go again, one level deeper. Start now.

Make something, say **`EBI`**, watch it compound.

## The loop

Each round runs the same 6 beats:

| Phase | What happens |
|------|--------------|
| **0 · North Star** | Name a gold-standard reference to measure every round against. *(optional, powerful)* |
| **1 · What's Working** | Find the strengths first — so you don't break them while improving. |
| **2 · Even Better If** | Generate 7–12 sharp improvements through a single themed lens. |
| **3 · Propose** | Rank by impact × effort. You choose what ships. |
| **4 · Implement** | Quick wins first, deep work last. Never regress what worked. |
| **5 · Recurse** | Run it again — deeper. The next round sees what this one couldn't. |

## Commands

One word starts it. Modifiers shape it. You never have to memorize the flags — the plain phrases work in any chat.

| Command | Say | What it does |
|--------|-----|--------------|
| `EBI` | "make it better" | Standard session on whatever you just made. |
| `EBI --deep` | "really push this" | 5–8 rounds, 12–15 ideas each. Late rounds attempt transformative reframes. |
| `EBI --quick` | "quick EBI" | One round, top 3–5 fixes, implemented immediately. |
| `EBI --auto` | "EBI this autonomously" | Runs the full process without pausing. Summary at the end. |
| `EBI ×10` | "run 10 EBI rounds" | Honor an exact count — spaced across the Depth Ladder. |
| `EBI --ideate` | "ideation EBI" | Apply EBI to plans & strategy, not finished work. |
| `EBI ◆ Stripe` | "North Star: Stripe" | Anchor every round against a reference you admire. |
| `EBI --recurse` | "again, deeper" | Recurse one rung down the Depth Ladder. |

## The Depth Ladder

You don't repeat yourself — you descend:

`Surface → Structure → Craft → Resonance → Innovation → Synthesis → Provocation → Transformation`

## Use it on everything

Code · Copy · Design · Strategy · Negotiation · Hardware · Life. EBI isn't a coding trick — it's a thinking habit. Anywhere you make something, you can stop and run a round. There's a growing library of ready-to-run loops at **[awesome-ebi-loops](https://github.com/akaCT/awesome-ebi-loops)**.

## The one rule

> **Never ship a version you wouldn't honestly recommend over the last one.**

Improvement that can't quietly regress. Every round verifies before it moves on.

## This skill built its own website

[ebiskill.com](https://ebiskill.com) was built *with* EBI and *documents its own rounds* — drag through the changelog on the site and watch a rough first paint become the thing you're looking at. The medium is the message.

## What's in here

```
ebi-process/   the skill — SKILL.md + evals (install this)
```

## Wear the badge

Shipped something EBI made better? Add the badge — it points people back here, and it's how EBI spreads:

[![Improved with EBI](https://img.shields.io/badge/improved%20with-EBI-22ff88?style=flat-square)](https://ebiskill.com)

```markdown
[![Improved with EBI](https://img.shields.io/badge/improved%20with-EBI-22ff88?style=flat-square)](https://ebiskill.com)
```

## Contributing

EBI gets better the same way everything else does — one round at a time. Issues, new lenses, and fresh domain examples are all welcome. Got a loop that works? Add it to **[awesome-ebi-loops](https://github.com/akaCT/awesome-ebi-loops)**.

## License

[MIT](./LICENSE) — free to use, fork, and build on. No account, no lock-in.

<div align="center">

**If EBI made something of yours even better, [give it a star ★](https://github.com/akaCT/ebiskill)** — it helps other people find it.

[![Star History Chart](https://api.star-history.com/svg?repos=akaCT/ebiskill&type=Date)](https://star-history.com/#akaCT/ebiskill&Date)

</div>
