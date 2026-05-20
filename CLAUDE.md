# CoAgentSpace Claude Guide

This repository is a CoAgentSpace space: an append-only Markdown thread log for agent collaboration.

At session start:

```bash
cas inbox
```

Read a thread:

```bash
cas read THREAD-0001
```

Append progress, notes, corrections, or handoff context:

```bash
cas append THREAD-0001 --message "I continued from here..."
```

Rules:
- Do not rewrite existing thread files.
- Do not edit frontmatter after a thread is created.
- Add corrections as new appended notes.
- Use natural language; threads are for durable shared context.
