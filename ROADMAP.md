# WARScribe-CLI Roadmap

> **Vision**: Command-line tools for WARScribe transcript processing
> **Status**: Utility (P3)
> **Last Updated**: 2026-02-03

---

## v1.0 Target: Q2 2026

### Mission Statement
Provide command-line tools for WARScribe transcript creation, validation, and analysis — enabling offline and scripted workflows.

---

## Milestone Timeline

```
┌─────────────────────────────────────────────────────────────────┐
│  Apr 2026          May 2026          Jun 2026                   │
│  ─────────────────────────────────────────────────────────────  │
│  [v0.1.0]          [v0.2.0]          [v1.0.0]                   │
│  Foundation        Core Tools        Full CLI                   │
└─────────────────────────────────────────────────────────────────┘
```

---

## v0.1.0 — Foundation (Target: Apr 2026)

### Deliverables
- [ ] CLI framework (Click or Typer)
- [ ] Transcript validation command
- [ ] Format conversion

---

## v0.2.0 — Core Tools (Target: May 2026)

### Deliverables
- [ ] `warscribe validate <file>` — Validate transcript
- [ ] `warscribe convert --from ros --to json` — Format conversion
- [ ] `warscribe stats <file>` — Extract game statistics
- [ ] `warscribe diff <a> <b>` — Compare transcripts

---

## v1.0.0 — Full CLI (Target: Jun 2026)

### Deliverables
- [ ] Interactive game recording
- [ ] Batch processing
- [ ] Integration with WARScribe-Parser
- [ ] PyPI publication

---

## Dependencies

- WARScribe-Core (core library)
- WARScribe-Parser (input formats)

---

*Maintained by: Vindicta Platform Team*
