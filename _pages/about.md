---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hi! I'm **Lei Liu** (刘磊), a senior at **Arcadia University** pursuing a double major in **Mathematics** and **Computer Science**. My research focuses on **uncertainty quantification**, **causal inference**, and **LLM agents** for **clinical and biomedical** applications. My goal is to build the next generation of agents and large language models that can be genuinely deployed in clinical treatment and biological research — systems that are not only capable, but also **interpretable** and **safe** in high-stakes settings.

I'm fortunate to be advised by [**Prof. Xiao Luo**](https://luoxiao12.github.io/) at the University of Wisconsin–Madison, and by [**Prof. Hongyu Zhao**](https://ysph.yale.edu/profile/hongyu-zhao/) and [**Prof. Tianyu Liu**](https://helloworldlty.github.io/) at Yale University. **I am actively looking for a PhD position starting in Fall 2027 — feel free to reach out!**

# 🔥 News
- *Jul 2026*: &nbsp;🎉🎉 One paper accepted to **MLHC 2026**! See you at Johns Hopkins Hospital in Baltimore.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLHC 2026</div><img src='images/pub_causal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLM-Extracted Covariates for Clinical Causal Inference: Rethinking Integration Strategies](https://arxiv.org/abs/2604.16763)

**Lei Liu**, Jialin Chen, Kathy Macropol

*Machine Learning for Healthcare (MLHC) 2026*

We study how to integrate LLM-extracted clinical covariates into causal inference. On a MIMIC-IV Sepsis-3 cohort of 21,859 patients, we compare seven covariate-integration strategies and show that augmenting the propensity model with LLM-extracted confounders (functional, mental, and code status from free-text notes) substantially revises effect estimates — directionally consistent with the CLOVERS RCT and robust under a doubly-robust AIPW estimator.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/pub_gala.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Geometric Semantic Exploration with Passage Mixup for Uncertainty Quantification in RAG](#)

**Lei Liu**, Yu Wang, Hang Zhou, Xiao Luo

*Submitted to NeurIPS 2026 (Under Review)*

We propose **GALA**, an uncertainty-quantification method for retrieval-augmented generation that estimates answer reliability by exploring the geometry of the semantic answer space, using a passage-mixup augmentation to probe answer sensitivity. GALA reaches **0.85 average AUROC** on Llama-3.1-8B, outperforming semantic-entropy and passage-utility baselines across six open-domain QA benchmarks.
</div>
</div>

# 📖 Education
- *Sep 2025 – May 2027*, [**Arcadia University**](https://www.arcadia.edu/) — B.S. in Mathematics and Computer Science. *GPA 3.98/4.00*
- *Jul 2026 – Aug 2026*, [**Peking University**](https://english.pku.edu.cn/index.html) (Summer School) — *Large Model: From Basic to Practice*, taught by Prof. Tiejun Huang
- *Sep 2023 – Jun 2025*, [**Jiangsu University**](https://www.usnews.com/education/best-global-universities/jiangsu-university-501438) — B.S. in Mathematics and Applied Mathematics. *GPA 4.34/5.00*

# 🔬 Research Experience

<div id="re-brief" markdown="1">

- *May 2026 – Present*: **Summer Research Intern** at **Yale University**. *Advised by [Prof. Hongyu Zhao](https://ysph.yale.edu/profile/hongyu-zhao/) and [Prof. Tianyu Liu](https://helloworldlty.github.io/).*
  - Building a multi-agent framework that instantiates lab-specific research agents for computational-biology workflows.
- *Jan 2026 – Present*: **Research Intern** at **University of Wisconsin–Madison**. *Advised by [Prof. Xiao Luo](https://luoxiao12.github.io/).*
  - Developed **GALA**, an uncertainty-quantification method for retrieval-augmented generation.
- *Sep 2025 – Dec 2025*: **Research Intern** at **Nanyang Technological University**. *Advised by [Prof. Xinfeng Li](https://letterligo.netlify.app/).*
  - Studied trust-boundary and user-permission vulnerabilities in GUI / computer-use agents.
- *May 2025 – Mar 2026*: **Independent Research** at **Arcadia University** & **Jiangsu University**. *Advised by [Prof. Kathy Macropol](https://www.arcadia.edu/faculty-and-staff/katherine-p-macropol/).*
  - Built a causal-inference pipeline with LLM-extracted covariates on a MIMIC-IV Sepsis-3 cohort.

<a href="javascript:void(0);" onclick="document.getElementById('re-brief').style.display='none';document.getElementById('re-full').style.display='block';return false;"><strong>▸ Show full details</strong></a>
</div>

<div id="re-full" markdown="1" style="display:none">

- *May 2026 – Present*, **Summer Research Intern**, Yale University, New Haven, CT. *Advised by [Prof. Hongyu Zhao](https://ysph.yale.edu/profile/hongyu-zhao/) and [Prof. Tianyu Liu](https://helloworldlty.github.io/).*
  - Designing a multi-agent framework that instantiates lab-specific research agents from public artifacts, targeting the reproducibility and knowledge-fragmentation challenges in computational-biology workflows.
  - Built an ingestion pipeline that scrapes and parses lab websites, papers, and repositories into a structured, retrievable lab profile for downstream grounding.
  - Developing a reproduction module for automated environment setup, dependency resolution, and code execution with sanity-checks against published results, plus a knowledge-grounded discovery module coupling literature/database retrieval with hypothesis generation and multi-agent orchestration.
- *Jan 2026 – Present*, **Research Intern**, University of Wisconsin–Madison, Madison, WI. *Advised by [Prof. Xiao Luo](https://luoxiao12.github.io/).*
  - Developed **GALA**, an uncertainty-quantification method for RAG that estimates answer reliability by exploring the geometry of the semantic answer space.
  - Designed a passage-mixup augmentation that perturbs retrieved evidence to probe answer sensitivity, yielding calibration signals for selective prediction.
  - Reached 0.85 average AUROC on Llama-3.1-8B, outperforming both semantic-entropy and passage-utility baselines across six open-domain QA benchmarks over four target LLMs.
- *Sep 2025 – Dec 2025*, **Research Intern**, Nanyang Technological University, Singapore. *Advised by [Prof. Xinfeng Li](https://letterligo.netlify.app/).*
  - Studied trust-boundary and user-permission vulnerabilities in GUI agents, building a general-purpose testing framework on OSWorld to evaluate when and how agents exceed their authorized action scope.
  - Integrated and stress-tested three state-of-the-art computer-use agents (OpenAI Operator, Anthropic Claude Computer Use, OS-Kairos) under a unified evaluation protocol covering 50+ adversarial scenarios, with reproducible Docker-based environments and action-trajectory logging across three provider SDKs.
- *May 2025 – Mar 2026*, **Independent Research**, Arcadia University & Jiangsu University. *Advised by [Prof. Kathy Macropol](https://www.arcadia.edu/faculty-and-staff/katherine-p-macropol/).*
  - Built a causal-inference pipeline estimating the effect of early vasopressor initiation (within 4 hours) on 28-day mortality in a MIMIC-IV Sepsis-3 cohort of 21,859 patients, using LLMs to extract interpretable clinical confounders (functional, mental, and code status) from free-text notes absent from structured EHR.
  - Compared seven covariate-integration strategies; directly augmenting the propensity model with LLM covariates halved the estimated effect (0.055 → 0.027), directionally consistent with the CLOVERS RCT and robust under a doubly-robust AIPW estimator; on semi-synthetic data, bias dropped from 0.0143 to 0.0003 and persisted under 20% extraction noise.
  - Built a three-model annotation pipeline (GPT-4o, Gemini-2.5-Pro, Claude Sonnet 4) reaching 95.5% inter-model consensus on 3,200 notes, and fine-tuned Qwen3-14B on consensus labels to raise extraction accuracy from 55.6% to 72.7% as a locally deployable, privacy-preserving alternative.

<a href="javascript:void(0);" onclick="document.getElementById('re-full').style.display='none';document.getElementById('re-brief').style.display='block';return false;"><strong>▴ Show less</strong></a>
</div>

# 🎖 Honors and Awards
- *2025* Arcadia University President's Scholarship ($56,000 total)
- *2025* National Second Prize, National University Student Statistical Modeling Competition (top 268 in 30,941 teams)
- *2024* Silver Medal, Chinese Mathematical Olympiad for University Students
- *2024* National First Prize, Chinese Undergraduate Physics Experiment Competition (CUPEC, top 85 in 2,755 teams)


