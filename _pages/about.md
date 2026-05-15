---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Xiangxiang Chu（初祥祥）
======

Senior Director & Head of AMAP-ML, Alibaba Group

<div class="vision-statement" markdown="1">
My research traces an arc from **efficient neural architecture design** to **multimodal large models and generative AI**. Starting with neural architecture search at Xiaomi, I moved to Vision Transformer design (Twins, CPVT) and multimodal foundation models (VisionLLaMA, MobileVLM) at Meituan, and now lead a 100+ member team at Alibaba AMAP building **LLM reasoning, generative models, and intelligent mobility systems**. The thread that connects all of it: making AI systems more efficient, more intelligent, and more broadly useful.
</div>

<div class="stats-grid">
  <div class="stat-item">
    <span class="stat-number">110+</span>
    <span class="stat-label">Publications</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">14,000+</span>
    <span class="stat-label">Citations</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">100+</span>
    <span class="stat-label">Team Members</span>
  </div>
  <div class="stat-item">
    <span class="stat-number">10,000+</span>
    <span class="stat-label">GitHub Stars</span>
  </div>
</div>

---

Featured Projects
------

<div class="project-grid project-grid--4col">
  <div class="project-card">
    <span class="project-card__tag project-card__tag--llm">LLM Reasoning</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2504.02546">GPG</a></div>
    <div class="project-card__desc">A simple and strong reinforcement learning baseline for model reasoning — no critic, no reference model, no KL penalty. Adopted by ByteDance's <a href="https://verl.readthedocs.io/en/latest/algo/gpg.html">VERL</a> framework as an official algorithm.</div>
    <div class="project-card__meta">ICLR 2026 · First Author · <a href="https://github.com/AMAP-ML/GPG"><img src="https://img.shields.io/github/stars/AMAP-ML/GPG?style=social" alt="GitHub stars"></a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--gen">World Model</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/DreamX-World">DreamX-World</a></div>
    <div class="project-card__desc">A general-purpose interactive world model that creates diverse, high-fidelity virtual environments with camera-controlled navigation and prompt-driven world events.</div>
    <div class="project-card__meta"><a href="https://github.com/AMAP-ML/DreamX-World"><img src="https://img.shields.io/github/stars/AMAP-ML/DreamX-World?style=social" alt="GitHub stars"></a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--gen">Generation</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2503.06132">USP</a></div>
    <div class="project-card__desc">Unified self-supervised pretraining that bridges image generation and understanding within a single framework.</div>
    <div class="project-card__meta">ICCV 2025 · First Author · <a href="https://github.com/AMAP-ML/USP"><img src="https://img.shields.io/github/stars/AMAP-ML/USP?style=social" alt="GitHub stars"></a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--llm">Agent</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/SkillClaw">SkillClaw</a></div>
    <div class="project-card__desc">Open-source framework that lets AI agent skills automatically evolve from real interactions across sessions, devices, and users. Compatible with Claude Code, Codex, and more.</div>
    <div class="project-card__meta">1,300+ Stars · <a href="https://github.com/AMAP-ML/SkillClaw"><img src="https://img.shields.io/github/stars/AMAP-ML/SkillClaw?style=social" alt="GitHub stars"></a></div>
  </div>
</div>

<div class="project-grid project-grid--4col">
  <div class="project-card">
    <span class="project-card__tag project-card__tag--detection">Detection</span>
    <div class="project-card__title"><a href="https://github.com/meituan/YOLOv6">YOLOv6</a></div>
    <div class="project-card__desc">Industrial-grade real-time object detection framework. Widely deployed in production across the industry, with a full training-to-deployment toolchain.</div>
    <div class="project-card__meta">5,700+ Stars · <a href="https://github.com/meituan/YOLOv6"><img src="https://img.shields.io/github/stars/meituan/YOLOv6?style=social" alt="GitHub stars"></a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--vlm">Vision-Language</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2312.16886">MobileVLM</a></div>
    <div class="project-card__desc">The first vision language assistant that runs in real-time on mobile devices (Snapdragon 888). The 1B/3B models benchmark against Gemini Nano.</div>
    <div class="project-card__meta">First Author · <a href="https://github.com/Meituan-AutoML/MobileVLM"><img src="https://img.shields.io/github/stars/Meituan-AutoML/MobileVLM?style=social" alt="GitHub stars"></a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--arch">Architecture</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2104.13840">Twins</a></div>
    <div class="project-card__desc">Revisiting spatial attention in Vision Transformers. Outperforms Swin Transformer with simpler design and better deployment properties.</div>
    <div class="project-card__meta">NeurIPS 2021 · First Author · Most Influential Paper · <a href="https://github.com/Meituan-AutoML/Twins"><img src="https://img.shields.io/github/stars/Meituan-AutoML/Twins?style=social" alt="GitHub stars"></a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--arch">Foundation</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2403.00522">VisionLLaMA</a></div>
    <div class="project-card__desc">A unified LLaMA-style backbone for vision tasks. Pioneered auto-scaling 2D RoPE for multimodal Transformers — the approach was later adopted by Qwen-VL and others. Surpasses ViT across generation, classification, segmentation, and detection.</div>
    <div class="project-card__meta">ECCV 2024 · First Author · <a href="https://github.com/Meituan-AutoML/VisionLLaMA"><img src="https://img.shields.io/github/stars/Meituan-AutoML/VisionLLaMA?style=social" alt="GitHub stars"></a></div>
  </div>
</div>

---

Research Journey
------

<div class="journey-timeline">
  <div class="journey-item journey-item--current">
    <div class="journey-item__period">2024 – Present · Alibaba AMAP</div>
    <div class="journey-item__title">LLM Reasoning, Generative AI & Intelligent Mobility</div>
    <div class="journey-item__desc">Leading a 100+ member team building LLM reasoning systems (GPG — adopted by ByteDance's VERL framework, Tree-GRPO, CoEvolve), image/video generation (DCW, S-Guidance, Eevee), foundation architectures (FASA, EPG), and AI-powered navigation (MobilityBench, GenMRP). Our multimodal understanding and generation technology powers AMAP's Saojie Bang (扫街榜) pipeline, and our large-scale industrial Agent system drives AMAP's newly launched AI Companion (AI 伴行) feature. 45+ top-venue papers.</div>
  </div>
  <div class="journey-item">
    <div class="journey-item__period">2020 – 2024 · Meituan</div>
    <div class="journey-item__title">Vision Transformers, Multimodal Models & Industrial AI</div>
    <div class="journey-item__desc">Built the Visual Intelligence team from scratch. Created Twins (NeurIPS'21), CPVT (ICLR'23), VisionLLaMA (ECCV'24); reproduced LLaMA 7B and built MobileVLM for on-device deployment; open-sourced YOLOv6 (5,700+ Stars); shipped autonomous delivery and drone perception systems.</div>
  </div>
  <div class="journey-item">
    <div class="journey-item__period">2017 – 2020 · Xiaomi</div>
    <div class="journey-item__title">Neural Architecture Search & AutoML</div>
    <div class="journey-item__desc">Founded Xiaomi's AutoML team. Produced a series of influential NAS works — FairNAS (ICCV'21), FairDARTS (ECCV'20), DARTS- (ICLR'21), FALSR — establishing new standards for fair and robust architecture search. Featured by Lei Jun and major AI media.</div>
  </div>
  <div class="journey-item">
    <div class="journey-item__period">2013 – 2017 · KingStar</div>
    <div class="journey-item__title">Power Grid AI & Reinforcement Learning</div>
    <div class="journey-item__desc">Core contributor to the "Complex Power Grid Autonomous-Collaborative Automatic Voltage Control" project. Contributed 20 invention patents. Awarded the <strong>National Science and Technology Progress First Prize (2018)</strong>.</div>
  </div>
  <div class="journey-item">
    <div class="journey-item__period">2012 – 2013 · IBM Research China</div>
    <div class="journey-item__title">Large-Scale Data Analytics</div>
    <div class="journey-item__desc">Research scientist working on large-scale data analytics and machine learning solutions.</div>
  </div>
</div>

---

Recognition
------

<ul class="awards-list">
  <li><strong>Top 100 AI Scholars</strong>, AMiner 2023 — selected from hundreds of thousands of AI researchers worldwide</li>
  <li><strong>National Science and Technology Progress First Prize</strong>, 2018 — contributed 20 invention patents</li>
  <li><strong>3 first-authored papers</strong> on PaperDigest's Most Influential Paper List: <em>FairNAS</em>, <em>Twins</em>, <em>CPVT</em></li>
  <li><strong>Area Chair</strong>: ICLR, NeurIPS &nbsp;|&nbsp; <strong>Senior Program Committee</strong>: AAAI, IJCAI</li>
  <li><strong>40+ domestic</strong> and <strong>7 international</strong> invention patents</li>
</ul>

---

Current Research Directions
------

<div class="two-col">
<div markdown="1">

**LLM Reasoning & Agents** — Reinforcement learning for LLM reasoning (GPG, MathForge), tree search for agent training (Tree-GRPO), agent-data co-evolution (CoEvolve), autonomous driving VLA (AutoDrive-R)

**Image & Video Generation** — Diffusion model optimization (DCW, S-Guidance), video virtual try-on (Eevee), long video narrative (NarrLV), motion generation benchmarks (VMBench)

</div>
<div markdown="1">

**Foundation Architectures** — Frequency-aware sparse attention (FASA), unified pretraining for generation and understanding (USP), end-to-end pixel generation without VAE (EPG), diffusion LLMs (AR-MAP)

**Intelligent Mobility** — Route-planning agent benchmarks (MobilityBench), generative multi-route navigation (GenMRP), map-augmented geolocalization reasoning, integrated search-recommendation

</div>
</div>

---

Team & Opportunities
------

<div class="team-section" markdown="1">

I lead the AMAP-ML team at Alibaba Group, a 100+ member research team with over half recruited from top AI labs globally, including multiple Google PhD Fellowship recipients.

**Our philosophy**: We believe in the tight coupling of academic research and industrial impact. Every core paper ships with reproducible open-source code, and our research directly powers products serving hundreds of millions of users.

<div class="team-section__grid">
<div class="team-section__item" markdown="1">

#### Open Source
We maintain [20+ projects on GitHub](https://github.com/AMAP-ML) spanning LLM reasoning, generative models, and intelligent mobility, with 10,000+ cumulative stars.

</div>
<div class="team-section__item" markdown="1">

#### Hiring
We are always looking for talented **interns and full-time researchers** in LLM reasoning, multimodal models, generative AI, and intelligent mobility. Drop me an [email](mailto:cxxgtxy@gmail.com) if interested.

</div>
</div>
</div>

---

Education
------

- **M.S. in Electrical Engineering**, Tsinghua University, 2012
- **B.S. in Electrical Engineering**, Southeast University, 2010
