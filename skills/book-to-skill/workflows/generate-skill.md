# Generate Skill from Analysis

Workflow for creating skill files from prior analysis or user-provided extraction notes.

## When to Use

- User previously ran `analyze-book.md` and now wants to generate
- User has their own analysis notes they want converted
- User wants to generate from a subset of prior extraction

## Prerequisites

- Analysis data available (from prior workflow or user input)
- User has indicated what to include

## Workflow Steps

### Step 1: Gather Analysis Input

**If coming from prior analysis:**
```
"I have the analysis from {Book Title}. Ready to generate the skill.

Quick confirmation - include all extracted content or specific items?"
```

**If user providing analysis:**
```
"Please share your analysis notes. I need:

1. **Frameworks** - Named mental models with their components
2. **Principles** - Core rules or guidelines
3. **Techniques** - Step-by-step methods (optional)
4. **Anti-patterns** - What to avoid (optional)
5. **Voice notes** - How the author writes (optional)

You can paste structured notes or describe what you've identified."
```

---

### Step 2: Confirm Skill Parameters

**Ask/confirm:**

```
Skill generation parameters:

**Name:** `{proposed-name}`
(Format: author-concept, e.g., cialdini-influence)

**Description:** {Proposed one-liner}

**Structure:** {Simple/Router}

**Reference depth:**
- Essential (key frameworks only)
- Comprehensive (all frameworks + principles)
- Exhaustive (everything extracted)

Confirm or adjust?
```

---

### Step 3: Enter Plan Mode

**Present generation plan:**

```
## Generation Plan: {skill-name}

### Files to create:

{For simple skill:}
- `{skill-name}/SKILL.md` - Complete skill in single file

{For router skill:}
- `{skill-name}/SKILL.md` - Router with essential principles
- `{skill-name}/references/core-thesis.md` - Central argument
- `{skill-name}/references/frameworks.md` - {count} frameworks
- `{skill-name}/references/principles.md` - {count} principles
- `{skill-name}/references/techniques.md` - {count} techniques
- `{skill-name}/references/anti-patterns.md` - {count} anti-patterns
- `{skill-name}/references/voice.md` - Voice calibration

### Content mapping:
{Brief note on what goes where}

Ready to generate?
```

---

### Step 4: Generate Files

**Exit plan mode and create files.**

**Use templates from:**
- `references/skill-patterns.md` - Overall structure
- `references/reference-file-templates.md` - Individual file formats

**Generation sequence:**
1. Create directory structure
2. Generate SKILL.md first (router or complete)
3. Generate reference files in order:
   - core-thesis.md
   - frameworks.md
   - principles.md
   - techniques.md
   - anti-patterns.md
   - voice.md
4. Generate any workflows

**Quality during generation:**
- Use exact framework names from analysis
- Include specific examples where available
- Maintain consistent formatting
- Add cross-references between related concepts

---

### Step 5: Validate and Report

**Check:**
- All files created
- Frontmatter valid
- No empty sections

**Report:**
```
## Skill Generated: {skill-name}

**Location:** {path}

**Files:**
{List with line counts}

**Content included:**
- {X} frameworks
- {Y} principles
- {Z} techniques
- {W} anti-patterns
- Voice calibration: {Yes/No}

**To use:** Invoke with `/{skill-name}`

The skill is ready.
```

---

## Handling Incomplete Analysis

**Missing frameworks:**
```
"No frameworks in the analysis. This skill will focus on principles and techniques. Continue?"
```

**Missing voice:**
```
"No voice calibration data. The skill won't include writing guidance. Continue?"
```

**Very sparse analysis:**
```
"Limited content available. The generated skill will be minimal. Consider:
1. Proceeding with what we have
2. Adding more analysis
3. Converting to a simpler format (principles list only)"
```
