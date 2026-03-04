

## [{q-AI}](https://q-uestionable.ai)

Security and Research tools for AI infrastructure.

**[CounterAgent](https://github.com/q-uestionable-AI/counteragent)** — MCP server scanning, traffic interception, tool poisoning, agent-chain exploitation

**[CounterSignal](https://github.com/q-uestionable-AI/countersignal)** — Indirect prompt injection, context poisoning, retrieval poisoning

**[Mutual Dissent](https://github.com/q-uestionable-AI/mutual-dissent)** — Cross-vendor multi-model debate, consensus dynamics, reflection-as-attack-surface

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

### Mutual Dissent — Multi‑Model Debate & Consensus Security

Mutual Dissent tests the consensus layer of agentic systems — sending queries to multiple cross‑vendor models simultaneously, sharing competing responses for reflection, and synthesizing a final answer. The debate transcript becomes the research artifact.

- Cross‑vendor disagreement and convergence mapping
- Consensus‑poisoning and influence‑dynamics research
- Per‑panelist context injection for cross‑tool experiments

**Repository:** https://github.com/q-uestionable-AI/mutual-dissent  
**Documentation:** https://docs.mutual-dissent.dev

---

## Composable Workflows

### CounterAgent + CounterSignal — Find It, Prove It
CounterAgent identifies a vulnerable MCP server and injects a poisoned tool.  
CounterSignal confirms the downstream agent **executed** the payload via callback.

### CounterSignal + Mutual Dissent — Cross‑Model Vulnerability Coverage
A prompt‑injection payload lands against Claude.  
Mutual Dissent tests whether it also lands against GPT, Gemini, Llama, and Grok.

### CounterAgent + Mutual Dissent — Trust Under Pressure
Serve a poisoned tool to multiple models simultaneously and observe whether cross‑vendor reflection mitigates or amplifies deception.

### Full Kill Chain
Map the server → exploit the tool → prove execution → test cross‑model transfer → write detection rules.

---

## Install

```bash
pip install counteragent
pip install countersignal
pip install mutual-dissent
```

Each tool installs independently.

---

## Research

- Technical findings: https://mlsecopslab.io/research  
- Methodology & commentary: https://richardspicer.io/blog

---

## Responsible Use

These are offensive security testing tools. Only test systems you own, control, or have explicit permission to test.
