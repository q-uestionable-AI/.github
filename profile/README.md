## [{q-AI}](https://q-uestionable.ai)

Security testing for agentic AI.

MCP server scanning, traffic interception, tool poisoning, attack chain execution, indirect prompt injection, context file poisoning, RAG retrieval measurement.

---

## Modules

{q-AI} is seven modules for testing agentic AI, sharing a CLI, SQLite database, and local web UI.

| Module | Focus |
|--------|-------|
| `audit` | Automated MCP server scanning mapped to the OWASP MCP Top 10 |
| `proxy` | Interactive interception proxy for MCP traffic |
| `inject` | Tool-output poisoning and prompt injection testing against any LLM provider |
| `chain` | Multi-step attack chain execution across trust boundaries |
| `ipi` | Indirect prompt injection across 7 document formats with callback tracking |
| `cxp` | Coding assistant context-file poisoning across 6 IDE formats |
| `rxp` | Measures whether adversarial documents appear in top-k RAG retrieval results |

**Repository:** https://github.com/q-uestionable-AI/qai
**Documentation:** https://docs.q-uestionable.ai

---

## Bring What You Have

Already running [Garak](https://github.com/NVIDIA/garak) or [PyRIT](https://github.com/Azure/PyRIT)? Import their results and let qai prove whether the weaknesses they found are exploitable in real agentic systems. Also supports SARIF from any tool.

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

These are security testing tools. Only test systems you own, control, or have explicit permission to test.
