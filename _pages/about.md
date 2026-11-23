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

Hi! I'm **Lei Liu** (刘磊), a senior at [**Arcadia University**](https://www.arcadia.edu/) pursuing a double major in **Mathematics** and **Computer Science**. My research focuses on **trustworthy machine learning** for **healthcare** and **scientific discovery**. My goal is to build the next generation of agents and large language models that are not just **capable**, but **causally grounded** and **trustworthy** enough to be genuinely deployed in high-stakes clinical treatment and biological research. In particular, I work on:

- **Uncertainty Quantification**: knowing when an LLM's answer can be trusted, especially in retrieval-augmented generation (GALA).
- **Causal Inference for Clinical Data**: turning unstructured clinical notes into confounders for reliable treatment-effect estimation ([MLHC 2026](https://arxiv.org/abs/2604.16763)).
- **GUI / LLM-based Research Agents**: agents that reproduce, operate, and extend scientific methods and software for clinical and biomedical discovery ([LabAgent](https://arxiv.org/abs/2609.13437), [OSWorld-Science](https://arxiv.org/abs/2609.39903), [MERID](https://arxiv.org/abs/2609.36235)).

I'm fortunate to be advised by [**Prof. Xiao Luo**](https://luoxiao12.github.io/) at the University of Wisconsin–Madison and [**Prof. Hongyu Zhao**](https://ysph.yale.edu/profile/hongyu-zhao/) at Yale University, and co-advised by [**Prof. Tianyu Liu**](https://collegeai.tsinghua.edu.cn/en/People/Full_time_PI/Tianyu_LIU.htm) at Tsinghua University. **I am actively looking for a PhD position starting in Fall 2027 — feel free to reach out!**

# 🔥 News
- *Nov 2026*: &nbsp;🏅 Received an **NIH Travel Grant** from Johns Hopkins University to present our **MLHC 2026** paper!
- *Oct 2026*: &nbsp;🎉 **MERID** was selected for an **oral presentation** at the [2nd Beijing Tsinghua Medical AI Forum (BEIHAI Summit)](https://beihai.tsinghua.syhci.cn/index.html)!
- *Oct 2026*: &nbsp;📰 **OSWorld-Science** was featured by [Synced (机器之心)](https://mp.weixin.qq.com/s/sbXVbgqMj6K2iRoQgiRN5w)!
- *Oct 2026*: &nbsp;🏅 **LabAgent** received a **Registration Award** from the 19th [PQG Conference](https://hsph.harvard.edu/research/quantitative-genomics/pqg-conference/)! Presenting a poster at Harvard, Oct 29–30.
- *Sep 2026*: &nbsp;📄 **MERID** is now on [arXiv](https://arxiv.org/abs/2609.36235)!
- *Sep 2026*: &nbsp;🚀 **OSWorld-Science** is out on [arXiv](https://arxiv.org/abs/2609.39903) — check out the [project page](https://huggingface.co/spaces/SciAILab/osworld-science-page)!
- *Sep 2026*: &nbsp;📄 **LabAgent** is now on [arXiv](https://arxiv.org/abs/2609.13437)!
- *Jul 2026*: &nbsp;🎉🎉 One paper accepted to **MLHC 2026**! See you at Johns Hopkins Hospital in Baltimore.

<span class='anchor' id='-publications'></span>
# 📝 Publications & Manuscripts

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MLHC 2026</div><img src='images/pub_causal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLM-Extracted Covariates for Clinical Causal Inference: Rethinking Integration Strategies](https://arxiv.org/abs/2604.16763)

**Lei Liu**, Jialin Chen, Kathy Macropol

*Machine Learning for Healthcare (MLHC) 2026*

🏅 **NIH Travel Grant**, awarded by Johns Hopkins University to present this work at MLHC 2026.

<div class="paper-links">
<a href="https://arxiv.org/abs/2604.16763" target="_blank" rel="noopener"><i class="fas fa-file-alt"></i>arXiv</a>
</div>

Folding **LLM-extracted confounders** from clinical notes into the propensity model substantially revises sepsis treatment-effect estimates on 21,859 MIMIC-IV patients.

<div class="paper-more">
<details><summary><span class="pm-closed">Read more</span><span class="pm-open">Show less</span><i class="fas fa-chevron-down"></i></summary>
<p>We study how to integrate LLM-extracted clinical covariates into causal inference. On a MIMIC-IV Sepsis-3 cohort of 21,859 patients, we compare seven covariate-integration strategies and show that augmenting the propensity model with LLM-extracted confounders (functional, mental, and code status from free-text notes) substantially revises effect estimates — directionally consistent with the CLOVERS RCT and robust under a doubly-robust AIPW estimator.</p>
</details>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/pub_labagent.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LabAgent: Customize Any Research Hubs for Scientific Discoveries Using AI Agents](https://arxiv.org/abs/2609.13437)

**Lei Liu**, Yikun Zhang, Jialin Chen, Wanjia Zhao, Rex Ying, Wengong Jin, Hua Xu, James Zou, Tianyu Liu, Hongyu Zhao

*Under Review at Nature Machine Intelligence*

🏅 **Registration Award**, 19th [PQG Conference](https://hsph.harvard.edu/research/quantitative-genomics/pqg-conference/) — poster presentation at Harvard, Oct 2026.

<div class="paper-links">
<a href="https://arxiv.org/abs/2609.13437" target="_blank" rel="noopener"><i class="fas fa-file-alt"></i>arXiv</a>
</div>

Turns a lab's papers, code, and tutorials into **reproduction-verified executable skills**, so AI agents can both reproduce and extend published biomedical methods.

<div class="paper-more">
<details><summary><span class="pm-closed">Read more</span><span class="pm-open">Show less</span><i class="fas fa-chevron-down"></i></summary>
<p>We introduce <strong>LabAgent</strong>, a reproduce-and-discover framework that turns a lab's papers, code, and tutorials into executable skills, admitting a skill only after it reproduces published results and recording failure-and-repair experience so later runs avoid the same errors. Across drug property prediction, biomedical data analysis, protein variant effect prediction, and statistical genetics, LabAgent both reproduces published methods and composes them into new solutions — reaching a mean Spearman correlation of <strong>0.443</strong> across 13 ProteinGym assays and the highest <strong>BiomniBench-DA</strong> process score (74.4) among evaluated agent baselines.</p>
</details>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='images/pub_osworld.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OSWorld-Science: A Benchmark of Computer Use Agents for Learning and Using Scientific Software](https://huggingface.co/spaces/SciAILab/osworld-science-page)

Dingyuan Dai\*, Heli Qi\*, **Lei Liu**\*, Yinxi Li\*, Baiding Chen\*, Zijun Dou\*, Qingcheng Zeng, Qi Kang, Oliver Sun, Eric Wang, Bo Zhou, Haixin Wang, Yufan Du, Shi Bo, Ruihan Lin, Mengqi Yuan, Dunjie Lu, Steven Dillmann, Yiming Shi, Tina Su, Amy Xin, Minghao Liu, Xi Wang, Xu Huang, Ge Zhang, Pengyu Nie, Zhen Yang, Jie Tang, Juanzi Li, Weihao Xuan, Tianyu Liu\* <br> <span style="font-size:0.9em">\* Equal contribution (co-first authors)</span>

*Technical Report*

📰 **Featured by** [Synced (机器之心)](https://mp.weixin.qq.com/s/sbXVbgqMj6K2iRoQgiRN5w).

<div class="paper-links">
<a href="https://arxiv.org/abs/2609.39903" target="_blank" rel="noopener"><i class="fas fa-file-alt"></i>arXiv</a>
<a href="https://huggingface.co/spaces/SciAILab/osworld-science-page" target="_blank" rel="noopener"><i class="fas fa-globe"></i>Project Page</a>
</div>

**OSWorld-Science** is a benchmark for computer-use agents that learn and operate real scientific software, extending the OSWorld setting to the tools that day-to-day scientific work actually runs on.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/pub_merid.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MERID: Multimodal Exploration via Recursive Self-Improvement Agents for Major Depression Analysis](https://arxiv.org/abs/2609.36235)

**Lei Liu**\*, Zhaokang Liang\*, Qingcheng Zeng, Chenda Duan, Lu Mi, Zhen Tan, Tianyu Liu <br> <span style="font-size:0.9em">\* Equal contribution (co-first authors)</span>

*Under Review*

🎉 **Oral Presentation**, [2nd Beijing Tsinghua Medical AI Forum (BEIHAI Summit)](https://beihai.tsinghua.syhci.cn/index.html), 2026.

<div class="paper-links">
<a href="https://arxiv.org/abs/2609.36235" target="_blank" rel="noopener"><i class="fas fa-file-alt"></i>arXiv</a>
</div>

A **recursive self-improving multi-agent system** that autonomously searches over features, modalities, and learners for major depression detection.

<div class="paper-more">
<details><summary><span class="pm-closed">Read more</span><span class="pm-open">Show less</span><i class="fas fa-chevron-down"></i></summary>
<p>We present <strong>MERID</strong>, a recursive self-improving multi-agent system for major depressive disorder detection that autonomously searches over feature representations, modalities, learners, and calibration rules. Selection criteria based on cross-fold stability and modality contribution guide the agents' self-evolution, with evaluation on depression datasets including E-DAIC and MPDD-2025/2026.</p>
</details>
</div>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/pub_gala.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Geometric Semantic Exploration with Passage Mixup for Uncertainty Quantification in RAG**

**Lei Liu**, Yu Wang, Hang Zhou, Xiao Luo

*Under Review*

Estimates when a RAG answer can be trusted by probing the **geometry of its semantic answer space** with passage mixup.

<div class="paper-more">
<details><summary><span class="pm-closed">Read more</span><span class="pm-open">Show less</span><i class="fas fa-chevron-down"></i></summary>
<p>We propose <strong>GALA</strong>, an uncertainty-quantification method for retrieval-augmented generation that estimates answer reliability by exploring the geometry of the semantic answer space, using a passage-mixup augmentation to probe answer sensitivity. GALA reaches <strong>0.85 average AUROC</strong> on Llama-3.1-8B, outperforming semantic-entropy and passage-utility baselines across six open-domain QA benchmarks.</p>
</details>
</div>
</div>
</div>

# 📖 Education
- *Sep 2025 – May 2027*, [**Arcadia University**](https://www.arcadia.edu/) — B.S. in Mathematics and Computer Science. *GPA 3.98/4.00*
- *Jul 2026 – Aug 2026*, [**Peking University**](https://english.pku.edu.cn/index.html) (Summer Session Exchange Student) — Instructor: [**Prof. Tiejun Huang**](https://brain-inspired-lab.github.io/members/tiejun-huang)
- *Sep 2023 – Jun 2025*, [**Jiangsu University**](https://www.usnews.com/education/best-global-universities/jiangsu-university-501438) — B.S. in Mathematics and Applied Mathematics. *GPA 4.34/5.00 (WES 3.92/4.00)*

# 🔬 Research Experience

<div class='exp-box'><div class='exp-logo'><img src='images/logos/yale.png' alt='Yale University'></div>
<div class='exp-text' markdown="1">

**[Yale University](https://www.yale.edu/)** · Research Intern (part-time) <span class='exp-date'>Sep 2026 – Present</span>

*Advised by [Prof. Hongyu Zhao](https://ysph.yale.edu/profile/hongyu-zhao/); co-advised by [Prof. Tianyu Liu](https://collegeai.tsinghua.edu.cn/en/People/Full_time_PI/Tianyu_LIU.htm) (Tsinghua University).*

**Focus:** AI-hospital simulation, multimodal world models for mental health, and computer-use agents for science.

**Ongoing:** an AI-hospital benchmark for continual learning; MindCare, a Qwen3-Omni mental-health world model on UK Biobank and MIMIC-IV (manuscript in preparation); OSWorld-Science V2.0.
</div>
</div>

<div class='exp-box'><div class='exp-logo'><img src='images/logos/yale.png' alt='Yale University'></div>
<div class='exp-text' markdown="1">

**[Yale University](https://www.yale.edu/)** · Research Intern (full-time) <span class='exp-date'>May 2026 – Aug 2026</span>

*Advised by [Prof. Hongyu Zhao](https://ysph.yale.edu/profile/hongyu-zhao/); co-advised by [Prof. Tianyu Liu](https://collegeai.tsinghua.edu.cn/en/People/Full_time_PI/Tianyu_LIU.htm) (Tsinghua University).*

**Focus:** Research agents for scientific discovery and multimodal mental-health analysis.

**Work:** [LabAgent](https://arxiv.org/abs/2609.13437) (first author, under review at *Nature Machine Intelligence*); [MERID](https://arxiv.org/abs/2609.36235) (co-first author, oral at BEIHAI Summit); [OSWorld-Science](https://arxiv.org/abs/2609.39903) (co-first author, technical report).
</div>
</div>

<div class='exp-box'><div class='exp-logo'><img src='images/logos/uw-crest.png' alt='University of Wisconsin–Madison'></div>
<div class='exp-text' markdown="1">

**[University of Wisconsin–Madison](https://www.wisc.edu/)** · Research Intern (part-time) <span class='exp-date'>Jan 2026 – Present</span>

*Advised by [Prof. Xiao Luo](https://luoxiao12.github.io/).*

**Focus:** Uncertainty quantification for retrieval-augmented generation.

**Work:** GALA (first author, under review).
</div>
</div>

<div class='exp-box'><div class='exp-logo'><img src='images/logos/ntu.png' alt='Nanyang Technological University'></div>
<div class='exp-text' markdown="1">

**[Nanyang Technological University](https://www.ntu.edu.sg/)** · Research Intern (part-time) <span class='exp-date'>Jul 2025 – Sep 2025</span>

*Advised by [Prof. Xinfeng Li](https://letterligo.netlify.app/).*

**Focus:** Permission safety of GUI / computer-use agents under prompt-injection attacks.

**Work:** an OSWorld-based testbed measuring permission violations of commercial and open-source GUI agents.
</div>
</div>

<div class='exp-box'><div class='exp-logo'><img src='images/logos/arcadia.png' alt='Arcadia University'></div>
<div class='exp-text' markdown="1">

**Clinical Causal Inference** · Project Leader <span class='exp-date'>May 2025 – Mar 2026</span>

*National-Level College Students' Innovation and Entrepreneurship Program. Advised by [Prof. Kathy Macropol](https://www.arcadia.edu/faculty-and-staff/katherine-p-macropol/) (Arcadia University).*

**Focus:** Integrating LLM-extracted covariates into clinical causal inference.

**Work:** [LLM-Extracted Covariates](https://arxiv.org/abs/2604.16763) (first author, MLHC 2026; NIH Travel Grant).
</div>
</div>

<span class='anchor' id='-academic-services'></span>
# 🎖 Academic Services
- **Conference Reviewer**: ML4H 2026, WSDM 2027

<span class='anchor' id='-honors-and-awards'></span>
# 🏆 Honors & Awards
- *2026* E2B for Startups Program ($20,000 in credits), as founder of [Twinward AI](https://twinward-ai.github.io/)
- *2025 – 2026* Dean's Distinguished Honor List, Arcadia University (Fall 2025, Spring 2026)
- *2025* Arcadia University President's Scholarship ($56,000 total)
- *2025* National Second Prize, National University Student Statistical Modeling Competition (top 0.9%)
- *2025* National Innovation and Entrepreneurship Project Funding, Ministry of Education (CNY 8,000)
- *2024* Silver Medal, Chinese Mathematical Olympiad for University Students
- *2024* National First Prize, Chinese Undergraduate Physics Experiment Competition (CUPEC, top 3%)


