# Thinking Skills

Claude Code skills for better judgment and decision-making.

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
| [book-to-skill](#book-to-skill) | Convert books and articles into Claude Code skills |
| [decision-auditor](#decision-auditor) | Audit decisions for cognitive biases and run premortems |
| [habits-and-goals](#habits-and-goals) | Annual goal-setting and daily habit systems |

---

## book-to-skill

Convert .txt book files into leverageable Claude Code skills.

```bash
npx skills add rohanpatriot/thinking-skills --skill book-to-skill
```

**Use when:**
- Transforming books, articles, or written expertise into structured skills
- Extracting frameworks, principles, and techniques from written material
- Creating reusable skills with workflows and reference material

**Workflows:**
- **Convert Book** - Full conversion from .txt to complete skill
- **Analyze Book** - Extract frameworks without generating skill files
- **Generate Skill** - Create skill from prior analysis
- **Convert Formats** - Convert epub, pdf, mobi, docx to .txt (requires Calibre/Poppler)

---

## decision-auditor

Audits decisions for cognitive biases, runs premortems on plans, and reframes choices to reveal hidden assumptions.

```bash
npx skills add rohanpatriot/thinking-skills --skill decision-auditor
```

**Use when:**
- Evaluating decisions under uncertainty
- Reviewing plans for cognitive biases
- Assessing probability and risk
- Running premortems
- Checking for anchoring or availability bias

**Workflows:**
- **Bias Check** - Systematic scan for common cognitive biases
- **Premortem** - Imagine failure to identify threats before they materialize
- **Reframe** - Change how a decision is framed to reveal hidden assumptions

---

## habits-and-goals

Systematic framework for annual goal-setting and execution based on Sahil Bloom's Annual Planning Guide.

```bash
npx skills add rohanpatriot/thinking-skills --skill habits-and-goals
```

**Use when:**
- Planning your year (Professional and Personal goals)
- Breaking down ambitious goals into daily systems
- Running monthly check-ins to course-correct
- Building sustainable habits with ABC levels

**Workflows:**
- **Annual Planning** - Full year planning session with Big Goals, Checkpoints, Daily Systems, Anti-Goals
- **Goal Decomposition** - Break down a single Big Goal into actionable components
- **Monthly Check-in** - Three-question review to catch drift early

---

## License

MIT License - See [LICENSE](LICENSE) for details.
