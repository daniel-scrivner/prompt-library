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
│  CATEGORY                   FILE                             STATUS       │
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
│  │  DOCUMENT REWRITING                                                  │  │
│  │  ══════════════════                                                  │  │
│  │  Transform documents into the voice of superintelligent AI systems   │  │
│  └──────────────────────────────────────────────────────────────────────┘  │
│                                                                            │
│  [03]  computer-speak_claude-prompt.md  AI voice transformer      [ACTIVE] │
│  [04]  computer-speak_grok-prompt.md    AI voice transformer      [ACTIVE] │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

---

## DETAILED SPECIFICATIONS

### PEER REVIEW WORKFLOW

```
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
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
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

**[peer-review-step-one.md](peer-review-step-one.md)** — Self-review prompt for finalizing work before peer review

**[peer-review-step-two.md](peer-review-step-two.md)** — Peer review synthesis prompt for comparing and integrating multiple implementations

---

### COMPUTER SPEAK: DOCUMENT REWRITING

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
| **[computer-speak_claude-prompt.md](computer-speak_claude-prompt.md)** | Claude | Clinical warmth (80%) with machine foundation (20%). JARVIS-like competence. Detailed transformation rules and anti-patterns. |
| **[computer-speak_grok-prompt.md](computer-speak_grok-prompt.md)** | Grok | Pure third-person overwatch. HAL 9000 rationality meets military precision. Extensive terminology lexicon. |

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
│  DOCUMENT REWRITING APPLICATION:                                           │
│  Feed any document through the computer-speak prompt to transform          │
│  human prose into superintelligent AI voice while preserving all           │
│  factual content and meaning.                                              │
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
