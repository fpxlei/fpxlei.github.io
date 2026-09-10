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

Hi! I'm **Lei Liu** (刘磊), a senior at [**Arcadia University**](https://www.arcadia.edu/) pursuing a double major in **Mathematics** and **Computer Science**. My research focuses on **uncertainty quantification**, **causal inference**, and **LLM agents** for **clinical and biomedical** applications. My goal is to build the next generation of agents and large language models that are not just **capable**, but **causally grounded** and **trustworthy** enough to be genuinely deployed in high-stakes clinical treatment and biological research.

I'm fortunate to be advised by [**Prof. Xiao Luo**](https://luoxiao12.github.io/) at the University of Wisconsin–Madison, and by [**Prof. Hongyu Zhao**](https://ysph.yale.edu/profile/hongyu-zhao/) and [**Prof. Tianyu Liu**](https://collegeai.tsinghua.edu.cn/en/People/Full_time_PI/Tianyu_LIU.htm) at Yale University. **I am actively looking for a PhD position starting in Fall 2027 — feel free to reach out!**

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
- *Jul 2026 – Aug 2026*, [**Peking University**](https://english.pku.edu.cn/index.html) (Summer Session) — *Large Model: From Basic to Practice*, taught by [**Prof. Tiejun Huang**](https://brain-inspired-lab.github.io/members/tiejun-huang)
- *Sep 2023 – Jun 2025*, [**Jiangsu University**](https://www.usnews.com/education/best-global-universities/jiangsu-university-501438) — B.S. in Mathematics and Applied Mathematics. *GPA 4.34/5.00*

# 🔬 Research Experience

<div id="re-brief" markdown="1">

- *May 2026 – Present*: **Research Intern** at **Yale University**. *Advised by [Prof. Hongyu Zhao](https://ysph.yale.edu/profile/hongyu-zhao/) and [Prof. Tianyu Liu](https://collegeai.tsinghua.edu.cn/en/People/Full_time_PI/Tianyu_LIU.htm).*
  - First author on **LabAgent**, a research-agent framework that turns lab papers, code, and tutorials into reproduction-verified executable skills, and on **MindResearcher**, an AutoResearch system for major-depression detection.
- *Jan 2026 – Present*: **Research Intern** at **University of Wisconsin–Madison**. *Advised by [Prof. Xiao Luo](https://luoxiao12.github.io/).*
  - Developed **GALA**, an uncertainty-quantification method for retrieval-augmented generation, best or tied-best in 18 of 24 benchmark settings.
- *Jul 2025 – Sep 2025*: **Research Intern** at **Nanyang Technological University**. *Advised by [Prof. Xinfeng Li](https://letterligo.netlify.app/).*
  - Built an OSWorld-based testbed measuring permission violations in commercial and open-source GUI agents under prompt-injection attack.
- *May 2025 – Mar 2026*: **Project Leader**, Clinical Causal Inference — National-Level College Students' Innovation and Entrepreneurship Program. *Advised by [Prof. Kathy Macropol](https://www.arcadia.edu/faculty-and-staff/katherine-p-macropol/).*
  - Led a MIMIC-IV Sepsis-3 study on integrating LLM-extracted covariates into clinical causal inference (MLHC 2026).

<a href="javascript:void(0);" onclick="document.getElementById('re-brief').style.display='none';document.getElementById('re-full').style.display='block';return false;"><strong>▸ Show full details</strong></a>
</div>

<div id="re-full" markdown="1" style="display:none">

- *May 2026 – Present*, **Research Intern** (full-time), Yale University, New Haven, CT. *Advised by [Prof. Hongyu Zhao](https://ysph.yale.edu/profile/hongyu-zhao/) and [Prof. Tianyu Liu](https://collegeai.tsinghua.edu.cn/en/People/Full_time_PI/Tianyu_LIU.htm).*
  - **LabAgent** (first author, manuscript in preparation): designed and built a research-agent framework that converts laboratory papers, code, and tutorials into executable skills, admitting a skill only after it reproduces published results, with persistent failure-and-repair memory and an evaluation suite that emits auditable run artifacts.
  - Benchmarked against Claude Code, Codex, and Claude Science: mean Spearman correlation of 0.443 across 13 ProteinGym assays with 7 outright wins; 32 of 65 TDC ADMET entries reproduced within published error bars; highest BiomniBench-DA process score (74.4) among evaluated agent baselines.
  - Reconstructed a UK Biobank fine-mapping analysis spanning 5 methods, 10 settings, 93,000 variants, and 10,000 samples in under 3 hours, recovering all reported orderings; identified a donor-level confounder in a separate single-cell eQTL task.
  - **MindResearcher** (first author, manuscript in preparation): built an automated modeling system for major-depression detection that searches over feature representations, modalities, learners, and calibration rules, with selection criteria based on cross-fold stability and modality contribution, evaluated on MPDD, DAIC-WOZ, and CMDC.
  - Implemented a temporal-JEPA encoder for time-series modalities as part of ongoing work on biomedical world models over clinical text, video, and EEG.
- *Jan 2026 – Present*, **Research Intern** (part-time), University of Wisconsin–Madison, Madison, WI. *Advised by [Prof. Xiao Luo](https://luoxiao12.github.io/).*
  - Developed **GALA**, an uncertainty-quantification method for RAG that perturbs retrieved passages and measures semantic dispersion across the generated answers; led method development, experiments, and manuscript preparation.
  - Achieved best or tied-best AUROC in 18 of 24 settings across six QA benchmarks and four LLMs, with up to 12 percentage points over the strongest baseline (0.93 vs. 0.81 on RefuNQ) using 40 trainable parameters.
  - Exceeded semantic entropy by 10 AUROC points at an equal generation budget (0.85 vs. 0.75); a single configuration transferred across three LLM families without model- or dataset-specific tuning, with AUROC varying by less than 0.02 across hyperparameter sweeps.
- *Jul 2025 – Sep 2025*, **Research Intern** (part-time), Nanyang Technological University, Singapore. *Advised by [Prof. Xinfeng Li](https://letterligo.netlify.app/).*
  - Studied trust-boundary and user-permission vulnerabilities in GUI / computer-use agents; integrated OS-Kairos with OSWorld and built a Docker-based testbed with action-trajectory logging to evaluate commercial and open-source agents under a common protocol.
  - Designed 50+ tasks and 6 prompt-injection attack types spanning file deletion, payments, credential access, and outbound messaging.
  - Measured permission violations in OpenAI Operator (31%), Anthropic Claude Computer Use (47%), and OS-Kairos (61%), and prototyped defenses that enforce user-granted scope.
- *May 2025 – Mar 2026*, **Project Leader**, Clinical Causal Inference — National-Level College Students' Innovation and Entrepreneurship Program, Arcadia University & Jiangsu University. *Advised by [Prof. Kathy Macropol](https://www.arcadia.edu/faculty-and-staff/katherine-p-macropol/).*
  - Led a study of early vasopressor initiation (within 4 hours of ICU admission) and 28-day mortality in a MIMIC-IV Sepsis-3 cohort of 21,859 patients, designing the study, building the cohort, and presenting a poster at Johns Hopkins University.
  - Extracted functional, mental, and code status from free-text notes and compared seven covariate-integration strategies; augmenting the propensity model reduced semi-synthetic bias by 98% (0.0143 → 0.0003) and shifted the clinical effect estimate from 0.055 to 0.027, with findings consistent under a doubly-robust AIPW estimator.
  - Built a three-model annotation pipeline (GPT-4o, Gemini-2.5-Pro, Claude Sonnet 4) reaching 95.5% inter-model consensus on 3,200 notes, and fine-tuned Qwen3-14B on the consensus labels to raise extraction accuracy from 55.6% to 72.7% as a locally deployable, privacy-preserving alternative.

<a href="javascript:void(0);" onclick="document.getElementById('re-full').style.display='none';document.getElementById('re-brief').style.display='block';return false;"><strong>▴ Show less</strong></a>
</div>

# 🎖 Honors and Awards
- *2025* Arcadia University President's Scholarship ($56,000 total)
- *2025* National Second Prize, National University Student Statistical Modeling Competition (top 268 in 30,941 teams)
- *2024* Silver Medal, Chinese Mathematical Olympiad for University Students
- *2024* National First Prize, Chinese Undergraduate Physics Experiment Competition (CUPEC, top 85 in 2,755 teams)


