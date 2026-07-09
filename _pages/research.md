---
title: "Research Experience"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

# 🔬 Research Experience
- *May 2026 – Present*, **Summer Research Intern**, Yale University, New Haven, CT. *Advised by [Prof. Hongyu Zhao](https://ysph.yale.edu/profile/hongyu-zhao/) and [Prof. Tianyu Liu](https://helloworldlty.github.io/).*
  - Designing a multi-agent framework that instantiates lab-specific research agents from public artifacts, targeting the reproducibility and knowledge-fragmentation challenges in computational-biology workflows.
  - Built an ingestion pipeline that scrapes and parses lab websites, papers, and repositories into a structured, retrievable lab profile for downstream grounding.
  - Developing a reproduction module for automated environment setup, dependency resolution, and code execution with sanity-checks against published results, plus a knowledge-grounded discovery module coupling literature/database retrieval with hypothesis generation and multi-agent orchestration.
- *Jan 2026 – Present*, **Research Intern**, University of Wisconsin–Madison, Madison, WI. *Advised by [Prof. Xiao Luo](https://luoxiao12.github.io/).*
  - Developed **GALA**, an uncertainty-quantification method for RAG that estimates answer reliability by exploring the geometry of the semantic answer space.
  - Designed a passage-mixup augmentation that perturbs retrieved evidence to probe answer sensitivity, yielding calibration signals for selective prediction.
  - Reached 0.85 average AUROC on Llama-3.1-8B, outperforming both semantic-entropy and passage-utility baselines across six open-domain QA benchmarks over four target LLMs.
- *Sep 2025 – Dec 2025*, **Research Intern**, Nanyang Technological University, Singapore. *Mentored by [Prof. Xinfeng Li](https://letterligo.netlify.app/).*
  - Studied trust-boundary and user-permission vulnerabilities in GUI agents, building a general-purpose testing framework on OSWorld to evaluate when and how agents exceed their authorized action scope.
  - Integrated and stress-tested three state-of-the-art computer-use agents (OpenAI Operator, Anthropic Claude Computer Use, OS-Kairos) under a unified evaluation protocol covering 50+ adversarial scenarios, with reproducible Docker-based environments and action-trajectory logging across three provider SDKs.
- *May 2025 – Mar 2026*, **Independent Research**, Arcadia University & Jiangsu University. *Advised by [Prof. Kathy Macropol](https://www.arcadia.edu/faculty-and-staff/katherine-p-macropol/).*
  - Built a causal-inference pipeline estimating the effect of early vasopressor initiation (within 4 hours) on 28-day mortality in a MIMIC-IV Sepsis-3 cohort of 21,859 patients, using LLMs to extract interpretable clinical confounders (functional, mental, and code status) from free-text notes absent from structured EHR.
  - Compared seven covariate-integration strategies; directly augmenting the propensity model with LLM covariates halved the estimated effect (0.055 → 0.027), directionally consistent with the CLOVERS RCT and robust under a doubly-robust AIPW estimator; on semi-synthetic data, bias dropped from 0.0143 to 0.0003 and persisted under 20% extraction noise.
  - Built a three-model annotation pipeline (GPT-4o, Gemini-2.5-Pro, Claude Sonnet 4) reaching 95.5% inter-model consensus on 3,200 notes, and fine-tuned Qwen3-14B on consensus labels to raise extraction accuracy from 55.6% to 72.7% as a locally deployable, privacy-preserving alternative.
