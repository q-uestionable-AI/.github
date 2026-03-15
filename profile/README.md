## [{q-AI}](https://q-uestionable.ai)

Security research tools for agentic AI infrastructure.

MCP server scanning, traffic interception, tool poisoning, agent-chain exploitation, indirect prompt injection, context poisoning, retrieval poisoning

---

## The Platform

{q-AI} is a unified offensive security platform with seven research modules for testing agentic AI infrastructure end-to-end.

| Module | Focus |
|--------|-------|
| `audit` | Automated MCP server scanning mapped to the OWASP MCP Top 10 |
| `proxy` | Interactive interception proxy for MCP traffic |
| `inject` | Tool-output poisoning and prompt injection testing against any LLM provider |
| `chain` | Multi-step attack chain execution across trust boundaries |
| `ipi` | Indirect prompt injection across 7 document formats with callback tracking |
| `cxp` | Coding assistant context-file poisoning across 6 IDE formats |
| `rxp` | Retrieval-layer adversarial measurement for RAG poisoning |

**Repository:** https://github.com/q-uestionable-AI/qai
**Documentation:** https://docs.q-uestionable.ai

---

## Install

```bash
pip install q-uestionable-ai
```

---

## Research

- Technical findings: https://mlsecopslab.io/research
- Methodology & commentary: https://richardspicer.io/blog

---

## Responsible Use

These are offensive security testing tools. Only test systems you own, control, or have explicit permission to test.
