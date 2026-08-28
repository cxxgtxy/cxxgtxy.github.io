---
layout: archive
title: "News"
permalink: /news/
author_profile: true
description: "Recent updates from Xiangxiang Chu and DreamX, including papers, open-source releases, product-facing AI systems, and team opportunities."
---

{% include base_path %}

<div class="news-lead">
  <p>Recent updates from my research, open-source work, and the DreamX team. This activity log connects papers, released code, product-facing AI systems, and hiring signals to DreamX's broader spatial-intelligence mission. Public releases remain available through the <a href="https://github.com/AMAP-ML">AMAP-ML GitHub organization</a>.</p>
</div>

<div class="impact-strip">
  <div>
    <span class="impact-strip__label">Recent papers</span>
    <strong>Agents, world models, spatial AI, and generative AI</strong>
  </div>
  <div>
    <span class="impact-strip__label">Open releases</span>
    <strong>40+ reproducible DreamX projects</strong>
  </div>
  <div>
    <span class="impact-strip__label">Product reach</span>
    <strong>300M+ daily users</strong>
  </div>
</div>

Latest DreamX Updates
------

These items are curated from recent DreamX releases and paper/project updates, with the newest and most product-relevant signals first.

- **2026.08.21** — DreamX had three papers accepted to **EMNLP 2026**: [SkillForge](https://arxiv.org/abs/2608.24747), [Role-Agent](https://arxiv.org/abs/2606.10917), and [M<sup>2</sup>Note](https://arxiv.org/abs/2607.00685), advancing verifiable skill evolution, dual-role agents, and continual vision-language learning.
- **2026.08.13** — [DreamX-Phi 1.0](https://arxiv.org/abs/2608.13489) introduced a geometry-aware, action-conditioned video world model for robotic manipulation. At release, it ranked **first on WorldArena 2.0 Track 1** and tied for second on Track 2; model weights and inference code are planned after the challenge concludes. [project](https://github.com/AMAP-ML/DreamX-Phi)
- **2026.08.03** — [LongHorizon-Harness](https://github.com/AMAP-ML/LongHorizon-Harness) introduced a **Manage-Execute-Audit** loop with durable verified state for reliable long-horizon computer-use agents, improving results across WeaveBench, OSWorld 2.0, and Terminal-Bench 2.1. [paper](https://arxiv.org/abs/2608.01964)
- **2026.07.23** — [DreamX-World 1.0](https://amap-ml.github.io/DreamX_World/) went live as an interactive world model, following the release of its [technical report](https://arxiv.org/abs/2606.16993) and open-source 5B model supporting **one-minute generation**. [code](https://github.com/AMAP-ML/DreamX-World)
- **2026.07.20** — [OmniDance](https://arxiv.org/abs/2606.30019) was selected for an **oral presentation at ECCV 2026**, advancing multimodal dance-video generation driven by text, image, and music. [code](https://github.com/AMAP-ML/OmniDance)
- **2026.07.20** — DreamX added four publications: [SCALAR++](https://github.com/zengjianhao/SCALAR) in **IJCV**, [Evaluation-Verification Reward](https://arxiv.org/abs/2607.29025) at **SIGGRAPH Asia 2026**, and [MAR-GRPO](https://github.com/AMAP-ML/mar-grpo) and [Peak-End-Net](https://github.com/AMAP-ML/Peak-End-Net) at **ACM MM 2026**.
- **2026.06.18** — DreamX had **five papers accepted to ECCV 2026**, adding another strong top-venue signal to the team's recent research portfolio.
- **2026.05.18** — [MobilityBench](https://github.com/AMAP-ML/MobilityBench) accepted as an **oral paper at KDD 2026**, providing a scalable benchmark for route-planning agents in real-world mobility scenarios.
- **2026.05.12** — [CoEvolve](https://github.com/AMAP-ML/CoEvolve) accepted to **ACL 2026**, training LLM agents through agent-data mutual evolution.
- **2026.05.12** — [Thinking-with-Map](https://github.com/AMAP-ML/Thinking-with-Map) accepted to **ACL 2026 Findings**, strengthening geolocalization with map-augmented reasoning.
- **2026.05.01** — [UniMRG](https://arxiv.org/abs/2601.21406) accepted to **ICML 2026**, showing that multi-representation generation strengthens unified multimodal understanding.
- **2026.05.01** — [MIGA](https://arxiv.org/abs/2605.18233) accepted to **ICML 2026**, extending pretrained video diffusion to arbitrarily long, temporally consistent videos without retraining.
- **2026.05.01** — [D<sup>2</sup>Evo](https://arxiv.org/abs/2605.17037) accepted to **ICML 2026**, improving data efficiency in reinforcement learning through dual difficulty-aware self-evolution.
- **2026.05.01** — [E<sup>2</sup>PO](https://arxiv.org/abs/2605.15803) accepted to **ICML 2026**, introducing embedding-perturbed exploration for preference optimization in flow models.
- **2026.04.22** — [DCW](https://github.com/AMAP-ML/DCW) accepted to **CVPR 2026**, mitigating SNR-t bias in diffusion probabilistic models.
- **2026.04.10** — [SkillClaw](https://github.com/AMAP-ML/SkillClaw) released an agentic evolver that turns real interaction traces into reusable skill libraries.
- **2026.04.01** — [MACE-Dance](https://github.com/AMAP-ML/MACE-Dance) accepted to **SIGGRAPH 2026**, decoupling motion generation and appearance synthesis for music-driven dance video.
- **2026.03.23** — [Omni-WorldBench](https://github.com/AMAP-ML/Omni-WorldBench) released a benchmark for interactive response capabilities of world models.
- **2026.02.06** — [GPG](https://github.com/AMAP-ML/GPG) accepted to **ICLR 2026** and adopted by ByteDance's [VERL](https://verl.readthedocs.io/en/latest/algo/gpg.html) as an official reasoning RL algorithm.
- **2026.02.06** — [Tree-GRPO](https://github.com/AMAP-ML/Tree-GRPO) accepted to **ICLR 2026**, replacing independent chain rollouts with tree-search rollouts for LLM agent reinforcement learning.

Selected GitHub Portfolio
------

The [AMAP-ML GitHub organization](https://github.com/AMAP-ML) hosts the DreamX open-source portfolio. The work is organized around three core problems — **understand and predict**, **generate and simulate**, and **plan and act** — supported by a shared foundation of spatial data, multimodal models, reinforcement learning, infrastructure, and evaluation. Selected flagship releases:

<div class="project-grid">
  <div class="project-card">
    <span class="project-card__tag project-card__tag--llm">Agents</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/SkillClaw">SkillClaw</a></div>
    <div class="project-card__desc">Agentic skill evolution from real interaction traces.</div>
    <div class="project-card__links"><a href="https://github.com/AMAP-ML/SkillClaw">GitHub</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--llm">Reasoning RL</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/GPG">GPG</a></div>
    <div class="project-card__desc">A minimalist group policy gradient baseline for model reasoning.</div>
    <div class="project-card__links"><a href="https://github.com/AMAP-ML/GPG">GitHub</a><a href="https://verl.readthedocs.io/en/latest/algo/gpg.html">VERL</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--llm">Computer-Use Agents</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/LongHorizon-Harness">LongHorizon-Harness</a></div>
    <div class="project-card__desc">Verified long-horizon computer use through durable task state and a Manage-Execute-Audit loop.</div>
    <div class="project-card__links"><a href="https://arxiv.org/abs/2608.01964">Paper</a><a href="https://github.com/AMAP-ML/LongHorizon-Harness">GitHub</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--vlm">World Models</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/DreamX-World">DreamX-World</a></div>
    <div class="project-card__desc">A general-purpose interactive world model for controllable world simulation.</div>
    <div class="project-card__links"><a href="https://amap-ml.github.io/DreamX_World/">Demo</a><a href="https://github.com/AMAP-ML/DreamX-World">GitHub</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--gen">Generative AI</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/FluxText">FluxText</a></div>
    <div class="project-card__desc">Scene-text editing for controllable visual asset generation.</div>
    <div class="project-card__links"><a href="https://github.com/AMAP-ML/FluxText">GitHub</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--detection">Spatial AI</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/MobilityBench">MobilityBench</a></div>
    <div class="project-card__desc">Route-planning agent evaluation grounded in real-world mobility scenarios.</div>
    <div class="project-card__links"><a href="https://github.com/AMAP-ML/MobilityBench">GitHub</a></div>
  </div>
</div>

<div class="highlight-box">
  <p><strong>Full release index:</strong> visit <a href="https://github.com/AMAP-ML">github.com/AMAP-ML</a> for the complete repository list, pinned releases, project pages, and hiring notes.</p>
</div>

---

2025
------

- **USP accepted to ICCV 2025**, proposing unified self-supervised pretraining for image generation and understanding. [paper](https://arxiv.org/abs/2503.06132) · [code](https://github.com/AMAP-ML/USP)
- **DreamX continued hiring** for interns, full-time researchers, and AI engineers in spatial intelligence, LLM agents, reinforcement learning, world models, multimodal learning, embodied AI, recommendation, and generative AI. [team](/team/#join-us)

---

Earlier Highlights
------

- **VisionLLaMA accepted to ECCV 2024**, a unified LLaMA-style backbone for vision tasks. [paper](https://arxiv.org/abs/2403.00522) · [code](https://github.com/Meituan-AutoML/VisionLLaMA)
- **MobileVLM released**, bringing real-time vision-language models to mobile devices. [paper](https://arxiv.org/abs/2312.16886) · [code](https://github.com/Meituan-AutoML/MobileVLM)
- **YOLOv6 open-sourced**, an industrial-grade real-time object detection framework. [code](https://github.com/meituan/YOLOv6)
- **Twins accepted to NeurIPS 2021**, revisiting spatial attention design in Vision Transformers. [paper](https://arxiv.org/abs/2104.13840) · [code](https://github.com/Meituan-AutoML/Twins)
