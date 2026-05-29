# SAE — Survivability-Aware Execution

## Execution Is the New Attack Surface: Survivability-Aware Agentic Crypto Trading with OpenClaw-Style Local Executors

[![arXiv](https://img.shields.io/badge/arXiv-2603.10092-b31b1b.svg)](https://arxiv.org/abs/2603.10092)
[![Code](https://img.shields.io/badge/Code-SAE_Policy_Guard-blue)](https://github.com/true-ai-labs/sae-policy-guard)
[![License](https://img.shields.io/badge/License-Apache_2.0-green)](https://github.com/true-ai-labs/sae-policy-guard/blob/main/LICENSE)

**Authors:** Ailiya Borjigin, Igor Stadnyk, Ben Bilski, Serhii Hovorov, Sofiia Pidturkina

**Published:** March 2026 | **Categories:** Cryptography and Security (cs.CR), Artificial Intelligence (cs.AI)

---

## Abstract

Autonomous AI agents increasingly execute financial transactions — yet most safety research focuses on reasoning and planning, overlooking the execution layer where untrusted prompts, compromised skills, or narrative manipulation can trigger real trades.

SAE (Survivability-Aware Execution) is a middleware layer for agent-based cryptocurrency trading systems that enforces execution safeguards including exposure budgets, rate limits, and slippage bounds.

**Key results** (tested on Binance perpetual data, September–December 2025):
- Maximum drawdown reduced by **93.1%**
- Delegation gap loss reduced by **~97%**

---

## Code

The reference implementation is available as an open-source skill:

**[SAE Policy Guard](https://github.com/true-ai-labs/sae-policy-guard)** — pre-trade risk assessment evaluating trader behavior, market conditions, and policy constraints.

Install:
```bash
npx skills add True-AI-Labs/sae-policy-guard
```

---

## Links

- **Paper:** [arxiv.org/abs/2603.10092](https://arxiv.org/abs/2603.10092)
- **PDF:** [arxiv.org/pdf/2603.10092](https://arxiv.org/pdf/2603.10092)
- **DOI:** [10.48550/arXiv.2603.10092](https://doi.org/10.48550/arXiv.2603.10092)
- **Code:** [github.com/true-ai-labs/sae-policy-guard](https://github.com/true-ai-labs/sae-policy-guard)

---

## Citation

```bibtex
@article{borjigin2026execution,
  title={Execution Is the New Attack Surface: Survivability-Aware Agentic Crypto Trading with OpenClaw-Style Local Executors},
  author={Borjigin, Ailiya and Stadnyk, Igor and Bilski, Ben and Hovorov, Serhii and Pidturkina, Sofiia},
  journal={arXiv preprint arXiv:2603.10092},
  year={2026},
  doi={10.48550/arXiv.2603.10092}
}
```

---

Built by [INC4](https://inc4.net) — House of Tech for AI & Web3
