# Hi, I'm Zhang Jing Bin 👋

🎓 **M.S. student,School of Data Science & Engineering, East China Normal University**
🔬 Research interests: **NLP · LLM hallucination mitigation · Agent engineering**
---
## 🌟 Open Source · Windows-MCP (11.3k★)

<a href="https://github.com/CursorTouch/Windows-MCP">
  <img src="https://img.shields.io/github/stars/CursorTouch/Windows-MCP?style=flat&logo=github&label=Windows-MCP&color=yellow" alt="Windows-MCP stars">
</a>
<a href="https://github.com/CursorTouch/Windows-MCP/pull/585">
  <img src="https://img.shields.io/badge/PR%20%23585-merged-brightgreen?logo=github" alt="PR #585 merged">
</a>
<a href="https://github.com/CursorTouch/Windows-MCP/issues/583">
  <img src="https://img.shields.io/badge/fixed%20issue-%23583-blue?logo=github" alt="Issue #583">
</a>


An open-source MCP server that lets LLM agents directly automate the Windows desktop. As a contributor ,I fix **merged the same day the issue was filed** ([PR #585](https://github.com/CursorTouch/Windows-MCP/pull/585), closes [#583](https://github.com/CursorTouch/Windows-MCP/issues/583)):

- 📦 **Large output no longer vanishes** — commands printing hundreds of KB lost their entire result to MCP client token limits; the response now keeps the head and the tail with an actionable truncation marker
- ⏱ **Timeouts are distinguishable** — a timeout no longer shares its exit code with real failures, and the output produced before it ended is surfaced so agents can pick the right retry strategy
- ✅ **Layered design + 11 regression tests** — capping lives at the tool layer, leaving 10+ internal structured-output call sites untouched; full suite green

## 🏆 Competitions

- 🥉 **Ali Tianchi × CCKS 2026 — Multimodal Knowledge Graph Construction for Cultural Tourism** — Third Prize · [competition page](https://tianchi.aliyun.com/competition/entrance/532477)
- **Kaggle × NVIDIA Nemotron Model Reasoning Challenge** — **Top 20%** (831 / 4185, Mar – Jun 2026) · [competition](https://www.kaggle.com/competitions/nvidia-nemotron-model-reasoning-challenge)

## 🛠 Tech Stack

**LLM training**: SFT / LoRA fine-tuning · RLHF (GRPO / PPO) · multi-GPU training & inference · on-policy distillation (OPD)

**Application engineering**: agent development · MCP / skill design · Context Engineering

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗_Transformers-FFD21E)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-black?logo=anthropic&logoColor=white)
