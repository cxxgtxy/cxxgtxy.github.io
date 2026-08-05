---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
description: "Curriculum Vitae of Xiangxiang Chu — Senior Director at Alibaba AMAP, Tsinghua M.S., and author of 120+ research papers and preprints, including 70+ papers at top-tier AI conferences."
redirect_from:
  - /resume
---

{% include base_path %}

<div class="vision-statement" markdown="1">
I lead **DreamX**, a 100+ member product-facing AI team at Alibaba AMAP building spatial intelligence models and systems that understand and predict, generate and simulate, plan and act in the real world. My research traces an arc from neural architecture search through Vision Transformer design and multimodal foundation models to LLM reasoning, world models, agent systems, and large-scale AMAP products serving **300M+ users every day**. I have authored **120+ research papers and preprints**, including **70+ papers at top-tier AI conferences**, with **15,000+ citations (6,000+ from first-authored works)** across open-source projects.
</div>

<div class="stats-grid">
  <div class="stat-item">
    <span class="stat-number">15,000+</span>
    <span class="stat-label">Citations</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">6,000+</span>
    <span class="stat-label">First-Author Citations</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">120+</span>
    <span class="stat-label">Publications</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">100+</span>
    <span class="stat-label">Team Members</span>
  </div>
</div>

---

Awards & Recognition
======

<ul class="awards-list">
  <li><strong>Top 100 AI Scholars</strong>, AMiner 2023 — selected from hundreds of thousands of AI researchers worldwide</li>
  <li><strong>3 first-authored papers</strong> on PaperDigest's Most Influential lists: <a href="https://resources.paperdigest.org/2022/02/most-influential-iccv-papers-2022-02/"><em>FairNAS</em></a>, <a href="https://www.paperdigest.org/2025/09/most-influential-nips-papers-2025-09-version/"><em>Twins</em></a>, <a href="https://resources.paperdigest.org/2024/09/most-influential-iclr-papers-2024-09/"><em>CPVT</em></a></li>
  <li><strong>2nd Place</strong>, Xiaomi "Million Dollar Prize" — Automated Neural Network Design</li>
</ul>

---

Professional Experience
======

<div class="cv-timeline" markdown="1">

<div class="cv-entry cv-entry--current" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">Alibaba Group — AMAP</span>
  <span class="cv-entry__period">Mar 2024 – Present</span>
</div>
<div class="cv-entry__role">Senior Director & Head of DreamX</div>

Leading AMAP's 100+ member spatial-intelligence team across understanding and prediction, generation and simulation, planning and action, and shared model, data, infrastructure, and evaluation foundations.

- Led DreamX research resulting in **50+ team papers** at top venues (ICLR, CVPR, ICML, ACL, KDD, ICCV, ECCV, NeurIPS, AAAI, EMNLP, SIGGRAPH) and **30+ open-source projects** hosted through the [AMAP-ML GitHub organization](https://github.com/AMAP-ML)
- Key first-author works: GPG (ICLR 2026, adopted by ByteDance's [VERL](https://verl.readthedocs.io/en/latest/algo/gpg.html) framework), USP (ICCV 2025); key team works: SkillClaw, DreamX-World, Tree-GRPO, FASA, CoEvolve
- Multimodal technology supports AMAP's **Saojie Bang (扫街榜)** pipeline; large-scale industrial Agent work contributes to **AI Companion (AI 伴行)** — alongside AMAP products serving 300M+ users every day

</div>

<div class="cv-entry" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">Meituan — Visual Intelligence Department</span>
  <span class="cv-entry__period">May 2020 – Mar 2024</span>
</div>
<div class="cv-entry__role">Senior Technical Manager</div>

Built the Visual Intelligence team from scratch. Directed research in Vision Transformers, multimodal large models, and industrial AI systems.

- Created **Twins** (NeurIPS 2021), **CPVT** (ICLR 2023), **VisionLLaMA** (ECCV 2024) — influential Vision Transformer architectures; VisionLLaMA introduced auto-scaling 2D RoPE for LLaMA-style vision backbones
- Built **MobileVLM**, a compact VLM designed for real-time on-device deployment; reproduced LLaMA 7B from scratch
- Open-sourced **YOLOv6**, a widely used industrial object detection framework; developed **QARepVGG** to address quantization challenges in RepVGG-style deployment
- Shipped 3D perception for autonomous delivery vehicles and drones, reducing annotation and serving costs

</div>

<div class="cv-entry" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">Xiaomi — Artificial Intelligence Department</span>
  <span class="cv-entry__period">Mar 2017 – May 2020</span>
</div>
<div class="cv-entry__role">Senior Technical Manager</div>

Founded Xiaomi's AutoML team and produced a series of influential neural architecture search works.

- **FairNAS** (ICCV 2021), **FairDARTS** (ECCV 2020), **DARTS-** (ICLR 2021), **FALSR** — establishing new standards for fair and robust architecture search
- Won **2nd place** in Xiaomi's first "Million Dollar Prize" (Automated Neural Network Design)
- FALSR super-resolution algorithm personally endorsed by CEO Lei Jun

</div>

<div class="cv-entry" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">Beijing KingStar System Control Co., Ltd.</span>
  <span class="cv-entry__period">Jun 2013 – Mar 2017</span>
</div>
<div class="cv-entry__role">Deputy Director</div>

- Core contributor to "Complex Power Grid Autonomy — Collaborative Automatic Voltage Control" project
- Contributed 20 invention patents; awarded **National Science and Technology Progress First Prize (2018)**

</div>

<div class="cv-entry" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">IBM Research China (CRL)</span>
  <span class="cv-entry__period">Jul 2012 – May 2013</span>
</div>
<div class="cv-entry__role">Research Scientist</div>

- Large-scale data analytics and machine learning solutions at IBM China Research Lab

</div>

</div>

---

Selected Publications
======

<div class="two-col" markdown="1">
<div markdown="1">

**LLM Reasoning**
- [GPG](https://arxiv.org/abs/2504.02546): Simple & Strong RL for Reasoning — **ICLR 2026** · 1st Author · 100+ citations
- [Tree-GRPO](https://arxiv.org/abs/2509.21240): Tree Search for Agent RL — **ICLR 2026**
- [CoEvolve](https://arxiv.org/abs/2604.15840): Agent-Data Co-Evolution — **ACL 2026**
- [MathForge](https://arxiv.org/abs/2601.20614): Difficulty-Aware GRPO — **ICLR 2026**
- [AutoDrive-R2](https://arxiv.org/abs/2509.01944): Reasoning VLA for Driving — **ICLR 2026**

**Generative AI & World Models**
- [USP](https://arxiv.org/abs/2503.06132): Unified Pretraining for Gen & Understanding — **ICCV 2025** · 1st Author
- [DCW](https://arxiv.org/abs/2604.16044): SNR-t Bias of Diffusion Models — **CVPR 2026**
- [S2-Guidance](https://arxiv.org/abs/2508.12880): Training-Free Diffusion Enhancement — **ICLR 2026**
- [EPG](https://arxiv.org/abs/2510.12586): End-to-End Pixel Generation without VAE — **ICLR 2026**
- [DreamX-World](https://arxiv.org/abs/2606.16993): Interactive World Model · 2026 Technical Report · [code](https://github.com/AMAP-ML/DreamX-World)

**AI Agents & Intelligent Mobility**
- [SkillClaw](https://github.com/AMAP-ML/SkillClaw): Collective Skill Evolution
- [Code2World](https://arxiv.org/abs/2602.09856): GUI World Model via Renderable Code
- [MobilityBench](https://arxiv.org/abs/2602.22638): Route-Planning Agent Benchmark — **KDD 2026 Oral**

</div>
<div markdown="1">

**Foundation Architectures**
- [VisionLLaMA](https://arxiv.org/abs/2403.00522): Unified LLaMA for Vision — **ECCV 2024** · 1st Author
- [Twins](https://arxiv.org/abs/2104.13840): Spatial Attention in ViTs — **NeurIPS 2021** · 1st Author · [PaperDigest Most Influential](https://www.paperdigest.org/2025/09/most-influential-nips-papers-2025-09-version/)
- [CPVT](https://arxiv.org/abs/2102.10882): Conditional Positional Encodings — **ICLR 2023** · 1st Author · [PaperDigest Most Influential](https://resources.paperdigest.org/2024/09/most-influential-iclr-papers-2024-09/)
- [FASA](https://arxiv.org/abs/2602.03152): Frequency-Aware Sparse Attention — **ICLR 2026**
- [QARepVGG](https://arxiv.org/abs/2212.01593): Quantization-Aware RepVGG — **AAAI 2024** · 1st Author

**Vision-Language & Detection**
- [MobileVLM](https://arxiv.org/abs/2312.16886): Real-Time Mobile Vision-Language Model · 1st Author
- [YOLOv6](https://arxiv.org/abs/2209.02976): Industrial Object Detection
- [SpatialGenEval](https://arxiv.org/abs/2601.20354): Spatial Intelligence Benchmark — **ICLR 2026**
- [PromptDet](https://arxiv.org/abs/2203.16513): Open-Vocabulary Detection — **ECCV 2022**

**AutoML & Neural Architecture Search**
- [FairNAS](https://arxiv.org/abs/1907.01845): Rethinking NAS Fairness — **ICCV 2021** · 1st Author · [PaperDigest Most Influential](https://resources.paperdigest.org/2022/02/most-influential-iccv-papers-2022-02/)
- [FairDARTS](https://arxiv.org/abs/1911.12126): Fair Differentiable NAS — **ECCV 2020** · 1st Author
- [DARTS-](https://arxiv.org/abs/2009.01027): Robustly Out of Collapse — **ICLR 2021** · 1st Author

</div>
</div>

<p style="text-align: right; font-size: 0.85em; color: #999;">
  → <a href="/publications/">Full publication list (120+ papers)</a>
</p>

---

Professional Service
======

<div class="service-badges">
  <span class="service-badge">Area Chair: ICLR</span>
  <span class="service-badge">Area Chair: NeurIPS</span>
  <span class="service-badge">SPC: AAAI</span>
  <span class="service-badge">SPC: IJCAI</span>
</div>

---

Education
======
- **M.S. in Electrical Engineering**, Tsinghua University, 2012
- **B.S. in Electrical Engineering**, Southeast University, 2010

---

Patents
======
- **40+** domestic invention patents
- **7** international invention patents
