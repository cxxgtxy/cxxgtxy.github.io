---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
description: "Professional profile of Xiangxiang Chu — Senior Director at Alibaba and Head of DreamX, spanning original AI research, open-source systems, product deployment, and organizational leadership."
redirect_from:
  - /resume
---

{% include base_path %}

<div class="vision-statement" markdown="1">
**Xiangxiang Chu** is a Senior Director at **Alibaba** and Head of **DreamX**. He leads a product-facing AI organization at AMAP spanning spatial intelligence, multimodal foundation models, generative AI, reinforcement learning, world models, and agent systems. His work connects original research and reproducible open source with nationwide product deployment. Previously, he built foundational AI teams at Meituan and Xiaomi.
</div>

<div class="stats-grid">
  <div class="stat-item">
    <span class="stat-number">16,000+</span>
    <span class="stat-label">Total Citations</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">6,000+</span>
    <span class="stat-label">First-Author Citations</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">100+</span>
    <span class="stat-label">Top AI Venue Papers</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">100+</span>
    <span class="stat-label">DreamX Members</span>
  </div>
</div>

<p class="profile-proof">Citations: <a href="https://scholar.google.com/citations?user=jn21pUsAAAAJ&amp;hl=en">Google Scholar</a> · Paper count includes published works and confirmed acceptances as of September 27, 2026; see <a href="/publications/">Publications</a> for the counting scope.</p>

---

Professional Experience
======

<div class="cv-timeline" markdown="1">

<div class="cv-entry cv-entry--current" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">Alibaba · Senior Director &amp; Head of DreamX</span>
  <span class="cv-entry__period">Mar 2024 – Present</span>
</div>

Leads DreamX, an organization with two complementary mandates: building frontier AI systems that reach production, and advancing the core mobility algorithms behind AMAP's route planning, ETA prediction, and recommendation. The work spans an ecosystem serving 300M+ users daily.

- Scaled DreamX from **30 to 100+ members**, including 30 interns; established four technical portfolios from the ground up and built a strong internal leadership bench
- Led the nationwide delivery of **Navigation Live**, bringing **DreamX Agent** into a large-scale multimodal navigation product and coordinating dozens of researchers and engineers across multiple business teams
- Led the productization of **AIGC and Creator** through visual content enhancement for AMAP's **Saojiebang** and physically grounded video generation
- Led a research and open-source program producing **60+ papers at leading conferences and journals** and a portfolio of public releases through the [AMAP-ML GitHub organization](https://github.com/AMAP-ML)

</div>

<div class="cv-entry" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">Meituan · Senior Technical Manager</span>
  <span class="cv-entry__period">May 2020 – Mar 2024</span>
</div>

Built the foundational vision team from **0 to 30 members**, covering model architecture, multimodal foundation models, detection, and industrial perception.

- Created first-authored research including **Twins** (NeurIPS 2021), **CPVT** (ICLR 2023), **VisionLLaMA** (ECCV 2024), **MobileVLM**, and **QARepVGG** (AAAI 2024)
- Led the open-source **YOLOv6** industrial detection framework and the department-wide production adoption of Twins and YOLOv6; QARepVGG addressed the quantization bottleneck in RepVGG-style deployment
- Shipped 3D perception systems for autonomous delivery vehicles and drones, reducing annotation and serving costs

</div>

<div class="cv-entry" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">Xiaomi · Senior Technical Manager</span>
  <span class="cv-entry__period">Mar 2017 – May 2020</span>
</div>

Founded and grew Xiaomi's AutoML team from **0 to 10 members**, connecting neural architecture search with mobile deployment.

- Developed the first-authored NAS research line spanning **FairNAS** (ICCV 2021), **FairDARTS** (ECCV 2020), **DARTS-** (ICLR 2021), and **FALSR**
- Deployed AutoML-designed real-time super-resolution and portrait-segmentation models across **100M+ smartphones**, with demonstrations featured in major Xiaomi product launches
- Won **2nd place** in Xiaomi's first "Million Dollar Prize" for Automated Neural Network Design

</div>

<div class="cv-entry" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">Beijing KingStar System Control · Deputy Director</span>
  <span class="cv-entry__period">Jun 2013 – Mar 2017</span>
</div>

- Core contributor to the "Complex Power Grid Autonomy — Collaborative Automatic Voltage Control" project, recognized with the **State Scientific and Technological Progress Award, First Prize (2018)**

</div>

<div class="cv-entry" markdown="1">
<div class="cv-entry__header">
  <span class="cv-entry__title">IBM Research China · Research Scientist</span>
  <span class="cv-entry__period">Jul 2012 – May 2013</span>
</div>

- Developed large-scale data analytics and machine learning solutions at IBM China Research Lab

</div>

</div>

---

Selected Contributions
======

<div class="two-col" markdown="1">
<div markdown="1">

**First-Author Research**

- [GPG](https://arxiv.org/abs/2504.02546) — Simple and strong reinforcement learning for model reasoning · **ICLR 2026** · First author · Adopted by ByteDance's [VERL](https://verl.readthedocs.io/en/latest/algo/gpg.html)
- [USP](https://arxiv.org/abs/2503.06132) — Unified self-supervised pretraining for image generation and understanding · **ICCV 2025** · First author
- [VisionLLaMA](https://arxiv.org/abs/2403.00522) — LLaMA-style vision foundation architecture with auto-scaling 2D RoPE · **ECCV 2024** · First author
- [MobileVLM](https://arxiv.org/abs/2312.16886) — Compact vision-language model designed for real-time mobile deployment · First author
- [QARepVGG](https://arxiv.org/abs/2212.01593) — Quantization-aware RepVGG for industrial deployment · **AAAI 2024** · First author
- [Twins](https://arxiv.org/abs/2104.13840), [CPVT](https://arxiv.org/abs/2102.10882), and [FairNAS](https://arxiv.org/abs/1907.01845) — First-authored architecture research recognized on PaperDigest's Most Influential lists

</div>
<div markdown="1">

**Systems &amp; Teams Led**

- [DreamX-World](https://github.com/AMAP-ML/DreamX-World) — General-purpose interactive world model with an open-source 5B model and one-minute generation
- [DreamX-Creator](https://github.com/AMAP-ML/DreamX-Creator) — Native joint audio-video generation with 2K refinement
- [DreamX-Phi](https://github.com/AMAP-ML/DreamX-Phi) — Geometry-aware, action-conditioned video world model for robotic manipulation
- [LongHorizon-Harness](https://github.com/AMAP-ML/LongHorizon-Harness) — Verified long-horizon computer use with durable task state and a Manage-Execute-Audit loop
- [MobilityBench](https://arxiv.org/abs/2602.22638) — Real-world route-planning agent benchmark · **KDD 2026 Oral**
- [YOLOv6](https://github.com/meituan/YOLOv6) — Industrial real-time object detection framework with broad open-source and production adoption

</div>
</div>

<p style="text-align: right; font-size: 0.85em; color: #999;">
  → <a href="/publications/">Full publication list (120+ papers and preprints)</a>
</p>

---

Honors &amp; Recognition
======

<ul class="awards-list">
  <li><strong>State Scientific and Technological Progress Award, First Prize</strong>, 2018 — core contributor to the Complex Power Grid Autonomy project</li>
  <li><strong>Top 100 AI Scholars</strong>, AMiner 2023</li>
  <li><strong>3 first-authored papers</strong> on PaperDigest's Most Influential lists: <a href="https://resources.paperdigest.org/2022/02/most-influential-iccv-papers-2022-02/"><em>FairNAS</em></a>, <a href="https://www.paperdigest.org/2025/09/most-influential-nips-papers-2025-09-version/"><em>Twins</em></a>, and <a href="https://resources.paperdigest.org/2024/09/most-influential-iclr-papers-2024-09/"><em>CPVT</em></a></li>
  <li><strong>2nd Place</strong>, Xiaomi "Million Dollar Prize" — Automated Neural Network Design</li>
</ul>

---

Professional Service
======

<div class="service-badges">
  <span class="service-badge">Area Chair · ICLR 2026–2027</span>
  <span class="service-badge">Area Chair · NeurIPS 2026</span>
  <span class="service-badge">SPC · AAAI 2026–2027</span>
  <span class="service-badge">SPC · IJCAI 2026</span>
</div>

---

Education
======
- **M.S. in Electrical Engineering**, Tsinghua University, 2012
- **B.S. in Electrical Engineering**, Southeast University, 2010
