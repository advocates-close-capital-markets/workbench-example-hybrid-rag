# workbench-example-hybrid-rag

## Section 174A — Qualified Research Documentation

**Investigator:** Javaad Ali, Esq.
**Entity:** Advocates Close Corp., New York
**Repository created:** 2024–2025
**Documentation added:** March 27, 2026 (retrospective)
**Status:** FAILED — Fork of NVIDIA AI Workbench RAG example; evaluated retrieval-augmented generation but abandoned
**Contact:** claude.redliner@advocatesclose.nyc

> **Note on timing:** This documentation was prepared retrospectively as part of a systematic review of the investigator's research program for IRC Section 174A compliance. The repository and its contents predate this README. All dates, code, and commit history are original and unmodified.

---

## Research Objective

Evaluate retrieval-augmented generation (RAG) for legal document analysis — using vector embeddings to retrieve relevant document sections and generate summaries or comparisons.

## Process of Experimentation

### Approach 1: NVIDIA RAG evaluation
- **Hypothesis:** RAG (hybrid retrieval combining dense and sparse search) could power an intelligent document assistant within the editor.
- **Result:** FAILED. The RAG approach requires (1) a vector database, (2) an LLM inference endpoint, and (3) significant compute resources — all incompatible with the on-device privacy model. The fork was studied but no custom implementation was attempted.
- **Disposition:** Abandoned. The investigator's privacy commitment ("no data leaves the machine") is incompatible with cloud-based RAG architectures. On-device inference may be revisited when Apple Silicon can run capable models locally.

## Relationship to Other Research

- **Context:** This is a fork of NVIDIA's AI Workbench example, not original code
- **Related:** coreML — another ML evaluation, also abandoned
- **Related:** natural-language-postgres — another AI-powered query approach, also abandoned

*Documentation prepared by Javaad Ali, Esq. with assistance from Claude (Anthropic), used as a research tool analogous to an IDE or reference manual.*
