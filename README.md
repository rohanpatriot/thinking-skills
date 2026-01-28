# Thinking Skills

Agent skills for better judgment and decision-making.

Skills that help you think better. Turn books into tools your agent can use. Catch cognitive biases before they derail decisions. Plan your year with systems that actually stick.

## Installation

Install all skills:

```bash
npx skills add rohanpatriot/thinking-skills
```

Install specific skills:

```bash
npx skills add rohanpatriot/thinking-skills --skill book-to-skill decision-auditor habits-and-goals
```

Test locally:

```bash
npx skills add ./path/to/thinking-skills
```

## Skills Overview

| Skill | Description |
|-------|-------------|
| [book-to-skill](#book-to-skill) | Turn any book into a reusable skill with frameworks and workflows |
| [decision-auditor](#decision-auditor) | Catch blind spots in your decisions before you commit |
| [habits-and-goals](#habits-and-goals) | Plan your year and build habits that stick |

---

## book-to-skill

Turn any book into a skill your agent can use. Extract the frameworks, techniques, and mental models into structured workflows.

```bash
npx skills add rohanpatriot/thinking-skills --skill book-to-skill
```

**Use when:**
- You've read a book with useful frameworks and want to use them consistently
- You want to extract actionable techniques from written material
- You're building a library of thinking tools from books you trust

**What you get:**
- Complete skill directory with SKILL.md, workflows, and references
- Extracted frameworks organized by type (mental models, techniques, checklists)
- Ready-to-use workflows that apply the book's ideas

**Workflows:**
- **Convert Book** - Full conversion from .txt to complete skill
- **Analyze Book** - Extract frameworks without generating skill files
- **Generate Skill** - Create skill from prior analysis
- **Convert Formats** - Convert epub, pdf, mobi, docx to .txt (requires Calibre/Poppler)

---

## decision-auditor

Catch blind spots in your decisions before you commit. Based on *Thinking, Fast and Slow* by Daniel Kahneman.

```bash
npx skills add rohanpatriot/thinking-skills --skill decision-auditor
```

**Use when:**
- You're about to make a big decision and want a sanity check
- A plan feels solid but something seems off
- You're stuck between options and can't see clearly
- You want to stress-test a plan before committing

**What you get:**
- Bias Check: Systematic scan identifying cognitive biases affecting your judgment
- Premortem: Failure scenarios with mitigations before you start
- Reframe: Your decision restated to reveal hidden assumptions

**Workflows:**
- **Bias Check** - Systematic scan for common cognitive biases
- **Premortem** - Imagine failure to identify threats before they materialize
- **Reframe** - Change how a decision is framed to reveal hidden assumptions

---

## habits-and-goals

Plan your year and build habits that stick. Based on Sahil Bloom's Annual Planning Guide.

```bash
npx skills add rohanpatriot/thinking-skills --skill habits-and-goals
```

**Use when:**
- Starting a new year and want a system for your goals
- A big goal feels overwhelming and needs breaking down
- You want monthly check-ins to stay on track
- You keep setting goals but struggle to maintain habits

**What you get:**
- Annual Plan: Big Goals, Checkpoints, Daily Systems, and Anti-Goals
- Goal Decomposition: Any goal broken into daily actions with ABC flexibility
- Monthly Check-in: Three questions to catch drift before it compounds

**Workflows:**
- **Annual Planning** - Full year planning session with Big Goals, Checkpoints, Daily Systems, Anti-Goals
- **Goal Decomposition** - Break down a single Big Goal into actionable components
- **Monthly Check-in** - Three-question review to catch drift early

---

## License

MIT License - See [LICENSE](LICENSE) for details.
