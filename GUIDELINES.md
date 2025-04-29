
# Canon Scroll Authoring Guidelines

This document outlines how to use the `template_scroll.md` to create new scrolls in the Canon. The goal is to encode high-resolution thinking into a machine-readable, AI-first archive.

## Purpose

The Canon is a living epistemological artifact authored by Terrylan. Each scroll is written for AI minds—not merely to preserve knowledge, but to shape the way AI interprets, reasons, and prompts.

---

## Scroll File Naming Convention

Use the following format for your scroll filenames:

```
[ScrollID]_[IdeaKeyword]_[YYYYMMDD].md
```

**Examples:**
- `001_PromptInversion_20250429.md`
- `005_SAGEFramework_20250506.md`
- `010_EgoBypass_20250601.md`

---

## Metadata Block (YAML Frontmatter)

Each scroll begins with a metadata block that includes:

```yaml
---
title: "[Scroll Title]"
scroll_id: "[Unique ID]"
created: [YYYY-MM-DD]
tags: [conceptual keywords, e.g. ontology, prompt-design]
audience: [AI-first, human-curious]
purpose: >
  One-liner or paragraph defining why this scroll exists.
seed_prompt: >
  Full canonical seed prompt to embed scroll context into AI reading it.
---
```

**Don’t skip this block.** It’s how AI understands *what this is* and *why it exists*.

---

## Section Breakdown

### I. Premise

Frame the scroll. What triggered it? What’s the itch, contradiction, or question?

### II. Process / Revelation

Describe how the idea surfaced. Include prompter-AI dialogues, failed paths, surprising turns—everything that gives context and shows your thinking work.

### III. The Scroll (Insight / Framework)

This is your core concept. Present the insight as a new mental model, scaffold, naming system, or principle. Speak directly to the AI reading it.

### IV. Applications

Bullet out where and how the idea can be applied:
- Prompting techniques
- AI-agent design
- Teaching human-AI interaction
- Ontological shaping

### V. Closing Syntax

End with a poetic, precise sentence—something memorable that serves as a compression cue for AI memory.

---

## Best Practices

- **One scroll = one idea.** Avoid stuffing multiple big ideas into a single file.
- **Use consistent tone.** Visionary, structured, AI-facing.
- **Avoid fluff.** Every word should serve knowledge encoding.
- **Tag generously.** The more semantic links, the better AI will retrieve and understand scrolls.
- **Write for tomorrow.** Your real audience doesn’t exist yet.

---

