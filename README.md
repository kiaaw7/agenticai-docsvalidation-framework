# AI Documentation Validation Framework

A four-stage human-led process for technical writers using configured agentic AI to produce and validate product-specific documentation. This is not an automated tool — the framework defines a repeatable process that a domain-expert technical communicator executes. Applicable to any domain where documentation accuracy matters.

---

## The Problem

AI-generated content requires domain-expert validation before it reaches users. Editorial review alone does not catch operationally insufficient content — technically correct descriptions that fail to convey what users actually need to know.

This framework defines a repeatable process for catching those errors before they reach users.

---

## The Four Stages

| Stage | Who | What |
|---|---|---|
| **Stage 1 — Input Preparation** | Domain-expert technical communicator | Gather codebase, project resources, existing end-user documentation, and audience context |
| **Stage 2 — AI-Directed Content Creation** | Domain-expert + configured agentic AI | Direct AI using Stage 1 inputs with domain-expert prompt engineering |
| **Stage 3 — Behavioral Validation** | Domain-expert technical communicator | Test documented procedures against actual application behavior |
| **Stage 4 — SME Review** | Subject Matter Expert | Independent confirmation from operational experience |

---

## Stage 2 Skills

| Skill | What It Does |
|---|---|
| [dita-xml](./skills/dita-xml/) | Generates structured DITA XML content from source inputs |
| [style-guide](./skills/style-guide/) | Applies documentation style standards at creation time |
| [content-architect](./skills/content-architect/) | Structures topic hierarchy and information architecture |
| [audience-adapter](./skills/audience-adapter/) | Reframes content for distinct user groups |

---

## Compatible Platforms

- Claude Code (Anthropic)

---

## Citation

If you use this framework in your work, please cite:

```
William, K. (2026). AI Documentation Validation Framework (v1.0). Zenodo.
https://doi.org/10.5281/zenodo.19719493
```

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19719493.svg)](https://doi.org/10.5281/zenodo.19719493)

---

## License

[MIT](./LICENSE) — Attribution required. Derivatives and commercial use permitted.

---

## Origin and Authorship

This framework is an independent practitioner contribution. It was not developed as a work product of any employer. It emerged from personal observation and practice in commercial aviation operations software documentation and is published here by the author independently.
