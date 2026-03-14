

## [{q-AI}](https://q-uestionable.ai)

Security research tools for agentic AI infrastructure.

**[CounterAgent](https://github.com/q-uestionable-AI/counteragent)** — MCP server scanning, traffic interception, tool poisoning, agent-chain exploitation

**[CounterSignal](https://github.com/q-uestionable-AI/countersignal)** — Indirect prompt injection, context poisoning, retrieval poisoning

---

## The Suite

### CounterAgent — Protocol & System Security

CounterAgent tests the "pipes" and logic that connect agents to the real world.

| Module | Focus |
|--------|-------|
| `audit` | Automated MCP server scanning mapped to the OWASP MCP Top 10 |
| `proxy` | Interactive interception proxy for MCP traffic |
| `inject` | Tool‑output poisoning and trust‑boundary testing |
| `chain` | Multi‑agent exploitation and delegation‑chain analysis |

**Repository:** https://github.com/q-uestionable-AI/counteragent  
**Documentation:** https://docs.counteragent.dev

---

### CounterSignal — Content & Supply Chain Security

CounterSignal tests the files, contexts, and retrieval layers that feed into agents — and proves execution.

| Module | Focus |
|--------|-------|
| `IPI` | Indirect prompt injection across 7 document formats with out‑of‑band callback tracking |
| `CXP` | Coding assistant context‑file poisoning across 6 IDE formats |
| `RXP` | Retrieval‑layer adversarial optimization for RAG poisoning |

**Repository:** https://github.com/q-uestionable-AI/countersignal  
**Documentation:** https://docs.countersignal.dev

---

## Install

```bash
pip install counteragent
pip install countersignal
```

Each tool installs independently.

---

## Research

- Technical findings: https://mlsecopslab.io/research  
- Methodology & commentary: https://richardspicer.io/blog

---

## Responsible Use

These are offensive security testing tools. Only test systems you own, control, or have explicit permission to test.
