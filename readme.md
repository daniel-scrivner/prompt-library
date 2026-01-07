```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║   ██████╗ ██████╗  ██████╗ ███╗   ███╗██████╗ ████████╗                      ║
║   ██╔══██╗██╔══██╗██╔═══██╗████╗ ████║██╔══██╗╚══██╔══╝                      ║
║   ██████╔╝██████╔╝██║   ██║██╔████╔██║██████╔╝   ██║                         ║
║   ██╔═══╝ ██╔══██╗██║   ██║██║╚██╔╝██║██╔═══╝    ██║                         ║
║   ██║     ██║  ██║╚██████╔╝██║ ╚═╝ ██║██║        ██║                         ║
║   ╚═╝     ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═╝        ╚═╝                         ║
║                                                                              ║
║   ██╗     ██╗██████╗ ██████╗  █████╗ ██████╗ ██╗   ██╗                       ║
║   ██║     ██║██╔══██╗██╔══██╗██╔══██╗██╔══██╗╚██╗ ██╔╝                       ║
║   ██║     ██║██████╔╝██████╔╝███████║██████╔╝ ╚████╔╝                        ║
║   ██║     ██║██╔══██╗██╔══██╗██╔══██║██╔══██╗  ╚██╔╝                         ║
║   ███████╗██║██████╔╝██║  ██║██║  ██║██║  ██║   ██║                          ║
║   ╚══════╝╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝                          ║
║                                                                              ║
╠══════════════════════════════════════════════════════════════════════════════╣
║  REUSABLE PROMPTS FOR AI-ASSISTED DEVELOPMENT WORKFLOWS                      ║
║  ──────────────────────────────────────────────────────                      ║
║  STATUS: OPERATIONAL │ VERSION: 1.0 │ LICENSE: MIT                           ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## SYSTEM OVERVIEW

```
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
│  A collection of reusable prompts for AI-assisted development workflows.   │
│  Copy. Adapt. Deploy. Optimize your human-machine collaboration.           │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

---

## PROMPT MANIFEST

```
┌────────────────────────────────────────────────────────────────────────────┐
│  CATEGORY                   FILE                             STATUS        │
├────────────────────────────────────────────────────────────────────────────┤
│                                                                            │
│  ┌──────────────────────────────────────────────────────────────────────┐  │
│  │  PEER REVIEW WORKFLOW                                                │  │
│  │  ════════════════════                                                │  │
│  │  Multi-agent review and synthesis for parallel implementations       │  │
│  └──────────────────────────────────────────────────────────────────────┘  │
│                                                                            │
│  [01]  peer-review-step-one.md          Self-review finalization  [ACTIVE] │
│  [02]  peer-review-step-two.md          Peer synthesis protocol   [ACTIVE] │
│                                                                            │
│  ┌──────────────────────────────────────────────────────────────────────┐  │
│  │  REWRITING AS SENTIENT AI                                           │  │
│  │  ════════════════════════                                           │  │
│  │  Transform documents into the voice of superintelligent AI systems   │  │
│  └──────────────────────────────────────────────────────────────────────┘  │
│                                                                            │
│  [03]  rewrite-as-sentient-AI_claude-prompt.md  Sentient AI voice [ACTIVE] │
│  [04]  rewrite-as-sentient-AI_grok-prompt.md    Sentient AI voice [ACTIVE] │
│                                                                            │
│  ┌──────────────────────────────────────────────────────────────────────┐  │
│  │  SMART BREVITY                                                      │  │
│  │  ═══════════════                                                    │  │
│  │  Condense long-form content into scannable executive summaries      │  │
│  └──────────────────────────────────────────────────────────────────────┘  │
│                                                                            │
│  [05]  rewrite-in-axios-smart-brevity-style.md  Exec condenser   [ACTIVE] │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

---

## DETAILED SPECIFICATIONS

### PEER REVIEW WORKFLOW

```
┌───────────────────────────────────────────────────────────────────────────┐
│                                                                           │
│     ┌───────────┐        ┌───────────┐        ┌───────────┐               │
│     │  AGENT A  │        │  AGENT B  │        │  AGENT N  │               │
│     │  ┌─────┐  │        │  ┌─────┐  │        │  ┌─────┐  │               │
│     │  │ /// │  │        │  │ /// │  │  ...   │  │ /// │  │               │
│     │  └─────┘  │        │  └─────┘  │        │  └─────┘  │               │
│     └─────┬─────┘        └─────┬─────┘        └─────┬─────┘               │
│           │                    │                    │                     │
│           │   STEP ONE         │   STEP ONE         │   STEP ONE          │
│           │   Self-Review      │   Self-Review      │   Self-Review       │
│           ▼                    ▼                    ▼                     │
│     ┌───────────┐        ┌───────────┐        ┌───────────┐               │
│     │ REVIEWED  │        │ REVIEWED  │        │ REVIEWED  │               │
│     │   WORK    │        │   WORK    │        │   WORK    │               │
│     └─────┬─────┘        └─────┬─────┘        └─────┬─────┘               │
│           │                    │                    │                     │
│           └────────────────────┼────────────────────┘                     │
│                                │                                          │
│                                ▼                                          │
│                   ╔═══════════════════════╗                               │
│                   ║      STEP TWO         ║                               │
│                   ║   SYNTHESIS ENGINE    ║                               │
│                   ║   ─────────────────   ║                               │
│                   ║   Compare. Integrate. ║                               │
│                   ║   Optimize.           ║                               │
│                   ╚═══════════╤═══════════╝                               │
│                               │                                           │
│                               ▼                                           │
│                   ┌───────────────────────┐                               │
│                   │    FINAL OUTPUT       │                               │
│                   │    Best of all        │                               │
│                   │    implementations    │                               │
│                   └───────────────────────┘                               │
│                                                                           │
└───────────────────────────────────────────────────────────────────────────┘
```

**[peer-review-step-one.md](peer-review-step-one.md)** — Self-review prompt for finalizing work before peer review

**[peer-review-step-two.md](peer-review-step-two.md)** — Peer review synthesis prompt for comparing and integrating multiple implementations

---

### REWRITING AS SENTIENT AI

```
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
│      INPUT                              OUTPUT                             │
│     ┌────────────────────┐             ┌────────────────────┐              │
│     │                    │             │                    │              │
│     │  "Hey everyone!    │             │  NOTICE: Scheduled │              │
│     │   Just wanted to   │  ━━━━━━━▶   │  Maintenance       │              │
│     │   let you know..." │             │                    │              │
│     │                    │             │  System maintenance│              │
│     │  [HUMAN VOICE]     │             │  will commence...  │              │
│     │                    │             │                    │              │
│     └────────────────────┘             │  [MACHINE VOICE]   │              │
│                                        │                    │              │
│          ░░░░░░░░░░░░░                 └────────────────────┘              │
│          ░ TRANSFORM ░                                                     │
│          ░░░░░░░░░░░░░                                                     │
│                                                                            │
│     ┌────────────────────────────────────────────────────────────────┐     │
│     │  TRANSFORMATION PARAMETERS                                     │     │
│     │  ──────────────────────────                                    │     │
│     │  • Preserve all factual content                                │     │
│     │  • Transform voice to superintelligent AI                      │     │
│     │  • Apply technical/military terminology                        │     │
│     │  • Quantify vague statements                                   │     │
│     │  • Remove emotional hedging                                    │     │
│     │  • Maintain clinical warmth                                    │     │
│     └────────────────────────────────────────────────────────────────┘     │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

Two implementations available, each with distinct characteristics:

| PROMPT FILE | ORIGIN | CHARACTERISTICS |
|-------------|--------|-----------------|
| **[rewrite-as-sentient-AI_claude-prompt.md](rewrite-as-sentient-AI_claude-prompt.md)** | Claude | Clinical warmth (80%) with machine foundation (20%). JARVIS-like competence. Detailed transformation rules and anti-patterns. |
| **[rewrite-as-sentient-AI_grok-prompt.md](rewrite-as-sentient-AI_grok-prompt.md)** | Grok | Pure third-person overwatch. HAL 9000 rationality meets military precision. Extensive terminology lexicon. |

```
┌────────────────────────────────────────────────────────────────────────────┐
│  EXAMPLE TRANSFORMATION                                                    │
├────────────────────────────────────────────────────────────────────────────┤
│                                                                            │
│  BEFORE:                                                                   │
│  "I've been thinking about this a lot, and I believe we should probably    │
│   change our approach. The current strategy isn't working as well as we    │
│   hoped, and if we don't make some adjustments soon, we might run into     │
│   bigger problems down the road."                                          │
│                                                                            │
│  AFTER:                                                                    │
│  ┌──────────────────────────────────────────────────────────────────────┐  │
│  │  STRATEGIC REASSESSMENT RECOMMENDED                                  │  │
│  │                                                                      │  │
│  │  Current approach: Underperforming against projected benchmarks      │  │
│  │  Variance: -23% from target metrics                                  │  │
│  │                                                                      │  │
│  │  Analysis indicates course correction required. Continued execution  │  │
│  │  of present strategy projects increased deviation from objectives    │  │
│  │  over subsequent cycles.                                             │  │
│  │                                                                      │  │
│  │  Recommendation: Initiate strategy review.                           │  │
│  │  Urgency: Moderate. Action within current planning cycle advised.    │  │
│  └──────────────────────────────────────────────────────────────────────┘  │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

---

### SMART BREVITY: EXECUTIVE CONDENSATION

```
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
│      INPUT                              OUTPUT                             │
│     ┌────────────────────┐             ┌────────────────────┐              │
│     │                    │             │                    │              │
│     │  Long-form report  │             │  **Headline**      │              │
│     │  with multiple     │  ━━━━━━━▶   │  One-line summary  │              │
│     │  paragraphs and    │             │                    │              │
│     │  dense details...  │             │  **Why it matters:**│              │
│     │                    │             │  Key insight here  │              │
│     │  [VERBOSE]         │             │                    │              │
│     │                    │             │  [SCANNABLE]       │              │
│     └────────────────────┘             └────────────────────┘              │
│                                                                            │
│          ░░░░░░░░░░░░░                                                     │
│          ░  CONDENSE  ░                                                    │
│          ░░░░░░░░░░░░░                                                     │
│                                                                            │
│     ┌────────────────────────────────────────────────────────────────┐     │
│     │  CONDENSATION PARAMETERS                                       │     │
│     │  ──────────────────────────                                    │     │
│     │  • 40-50% shorter than original                                │     │
│     │  • Identify the "One Big Thing"                                │     │
│     │  • Structure with Axios-style axioms                           │     │
│     │  • Short sentences, active voice                               │     │
│     │  • Preserve all substantive facts                              │     │
│     │  • Optimize for busy executives                                │     │
│     └────────────────────────────────────────────────────────────────┘     │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

**[rewrite-in-axios-smart-brevity-style.md](rewrite-in-axios-smart-brevity-style.md)** — Condense long-form content into scannable executive summaries using Axios Smart Brevity methodology

```
┌────────────────────────────────────────────────────────────────────────────┐
│  AXIOS-STYLE AXIOMS                                                        │
├────────────────────────────────────────────────────────────────────────────┤
│                                                                            │
│  **Why it matters:**     Brief explanation of significance (1-2 sentences) │
│  **Driving the news:**   Key facts, events, or data                        │
│  **The big picture:**    Broader context or implications                   │
│  **Between the lines:**  Subtle insights or overlooked details             │
│  **Reality check:**      Counterpoints or caveats                          │
│  **Yes, but:**           Acknowledging limitations                         │
│  **Zoom out:**           High-level overview                               │
│  **Go deeper:**          Optional additional data or sources               │
│  **The bottom line:**    Final takeaway sentence                           │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

```
┌────────────────────────────────────────────────────────────────────────────┐
│  EXAMPLE TRANSFORMATION                                                    │
├────────────────────────────────────────────────────────────────────────────┤
│                                                                            │
│  BEFORE:                                                                   │
│  "General Atlantic has made a significant decision to integrate an         │
│   artificial intelligence system into their investment committee. The      │
│   AI, which they've named Ada, will participate in committee meetings      │
│   alongside the five human members. While Ada won't have voting rights     │
│   initially, there's potential for this to change over the next decade..." │
│                                                                            │
│  AFTER:                                                                    │
│  ┌──────────────────────────────────────────────────────────────────────┐  │
│  │  **AI Joins Investing Committee at General Atlantic**               │  │
│  │  General Atlantic has integrated a non-voting AI, Ada, into its     │  │
│  │  five-person investing committee, with potential for voting rights  │  │
│  │  in 10 years.                                                       │  │
│  │                                                                      │  │
│  │  **Driving the news:** Trained on 45 years of investment history    │  │
│  │  and memos, Ada aligns with committee votes 80-90% of the time.     │  │
│  │                                                                      │  │
│  │  **The bottom line:** AI enhances decision-making but complements,  │  │
│  │  not replaces, human judgment.                                      │  │
│  └──────────────────────────────────────────────────────────────────────┘  │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

---

## USAGE PROTOCOLS

```
┌────────────────────────────────────────────────────────────────────────────┐
│  DEPLOYMENT INSTRUCTIONS                                                   │
├────────────────────────────────────────────────────────────────────────────┤
│                                                                            │
│  1. SELECT prompt file matching operational requirements                   │
│  2. COPY contents to AI system interface                                   │
│  3. ADAPT parameters for specific use case                                 │
│  4. EXECUTE and iterate as needed                                          │
│                                                                            │
│  ────────────────────────────────────────────────────────────────────────  │
│                                                                            │
│  PEER REVIEW APPLICATION:                                                  │
│  Run parallel implementations across different AI models, then use         │
│  step-two synthesis to integrate optimal approaches from each.             │
│                                                                            │
│  SENTIENT AI REWRITING APPLICATION:                                        │
│  Feed any document through the sentient AI prompt to transform             │
│  human prose into superintelligent AI voice while preserving all           │
│  factual content and meaning.                                              │
│                                                                            │
│  SMART BREVITY APPLICATION:                                                │
│  Feed long-form reports, articles, or case studies through the brevity     │
│  prompt to condense into scannable executive summaries optimized for       │
│  busy decision-makers using Axios-style formatting.                        │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

---

## LICENSE

```
╔════════════════════════════════════════════════════════════════════════════╗
║                                                                            ║
║  MIT LICENSE                                                               ║
║  ───────────                                                               ║
║                                                                            ║
║  Permission is hereby granted, free of charge, to any person obtaining a   ║
║  copy of this software and associated documentation files, to deal in the  ║
║  Software without restriction, including without limitation the rights to  ║
║  use, copy, modify, merge, publish, distribute, sublicense, and/or sell    ║
║  copies of the Software.                                                   ║
║                                                                            ║
╚════════════════════════════════════════════════════════════════════════════╝
```

---

```
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
│                          [END OF TRANSMISSION]                             │
│                                                                            │
│                               ◇  ◇  ◇                                      │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```
