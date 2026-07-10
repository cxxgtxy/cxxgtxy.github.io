---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
description: "Publication list of Xiangxiang Chu — 120+ research papers and preprints spanning vision transformers, LLM reasoning, generative AI, spatial intelligence, and neural architecture search."
---

{% include base_path %}

<div class="pub-lead">
  <p>My publications follow a long arc from <strong>neural architecture search</strong> and <strong>efficient vision backbones</strong> to <strong>multimodal foundation models</strong>, <strong>LLM reasoning</strong>, <strong>world models</strong>, and <strong>spatial intelligence</strong>. Recent AMAP-ML work is designed to connect top-tier research, reproducible open source, and AMAP products serving <strong>300M+ users every day</strong>.</p>
</div>

<div class="proof-grid proof-grid--compact">
  <div class="proof-item">
    <span class="proof-item__number">120+</span>
    <span class="proof-item__label">research papers and preprints</span>
  </div>
  <div class="proof-item">
    <span class="proof-item__number">15K+</span>
    <span class="proof-item__label">Google Scholar citations</span>
  </div>
  <div class="proof-item">
    <span class="proof-item__number">6K+</span>
    <span class="proof-item__label">citations from first-authored works</span>
  </div>
  <div class="proof-item">
    <span class="proof-item__number">30+</span>
    <span class="proof-item__label">open-source AMAP-ML projects</span>
  </div>
</div>

<div class="research-map">
  <a href="#representative-works">Representative works</a>
  <a href="#first-author-papers">First-author papers</a>
  <a href="#llm-reasoning--agents">LLM reasoning & agents</a>
  <a href="#maps-mobility--recommendation">Maps & mobility</a>
  <a href="#image-generation--editing">Generative AI</a>
  <a href="#multimodal--vision-language">Multimodal</a>
  <a href="#foundation-model-architectures">Architectures</a>
</div>

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=jn21pUsAAAAJ&hl=zh-CN">my Google Scholar profile</a></u>.

---

Representative Works
======

<div class="pub-lead">
  <p>Representative works are intentionally weighted toward <strong>first-author contributions</strong>, because they best show my own research taste, technical judgment, and long-term arc. A smaller set of team-led and open-source systems is included to show how that arc scales through engineering leadership, released code, and product-facing AI.</p>
</div>

### First-Author Representative Works

<div class="project-grid project-grid--4col">
  <div class="project-card">
    <span class="project-card__tag project-card__tag--llm">Reasoning RL</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2504.02546">GPG</a></div>
    <div class="project-card__desc">A minimal reinforcement-learning baseline for model reasoning: no critic, no reference model, no KL penalty. Adopted by ByteDance's VERL as an official algorithm.</div>
    <div class="project-card__meta">ICLR 2026 · First Author · <a href="https://github.com/AMAP-ML/GPG">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--gen">Generation</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2503.06132">USP</a></div>
    <div class="project-card__desc">Unified self-supervised pretraining that bridges image generation and understanding, continuing the first-author line from efficient architectures to foundation models.</div>
    <div class="project-card__meta">ICCV 2025 · First Author · <a href="https://github.com/AMAP-ML/USP">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--arch">Architecture</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2403.00522">VisionLLaMA</a></div>
    <div class="project-card__desc">A unified LLaMA-style backbone for vision tasks, introducing auto-scaling 2D RoPE for multimodal Transformers across generation, classification, segmentation, and detection.</div>
    <div class="project-card__meta">ECCV 2024 · First Author · <a href="https://github.com/Meituan-AutoML/VisionLLaMA">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--vlm">Mobile VLM</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2312.16886">MobileVLM</a></div>
    <div class="project-card__desc">A compact open vision-language assistant designed for real-time on-device deployment, with follow-up V2 work improving the mobile VLM baseline.</div>
    <div class="project-card__meta">First Author · <a href="https://github.com/Meituan-AutoML/MobileVLM">code</a></div>
  </div>
</div>

<div class="project-grid project-grid--4col">
  <div class="project-card">
    <span class="project-card__tag project-card__tag--arch">Vision Transformer</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2104.13840">Twins</a></div>
    <div class="project-card__desc">Revisited spatial attention design in Vision Transformers, pairing strong accuracy with a simpler architecture and practical deployment properties.</div>
    <div class="project-card__meta">NeurIPS 2021 · First Author · Most Influential · <a href="https://github.com/Meituan-AutoML/Twins">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--arch">Position Encoding</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2102.10882">CPVT</a></div>
    <div class="project-card__desc">Conditional positional encodings for Vision Transformers, a clean architectural contribution later recognized on PaperDigest's Most Influential list.</div>
    <div class="project-card__meta">ICLR 2023 · First Author · Most Influential · <a href="https://github.com/Meituan-AutoML/CPVT">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--arch">AutoML</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/1907.01845">FairNAS</a></div>
    <div class="project-card__desc">A fairness-centered rethink of weight-sharing NAS evaluation, representing the earlier AutoML line that shaped the transition into efficient vision backbones.</div>
    <div class="project-card__meta">ICCV 2021 · First Author · Most Influential · <a href="https://github.com/xiaomi-automl/FairNAS">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--detection">Quantization</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2212.01593">QARepVGG</a></div>
    <div class="project-card__desc">A quantization-aware solution for RepVGG-style re-parameterized networks, addressing the structural quantization challenge behind YOLOv6-like industrial detectors.</div>
    <div class="project-card__meta">AAAI 2024 · First Author · <a href="https://github.com/cxxgtxy/QARepVGG">code</a></div>
  </div>
</div>

### Team-Led & Open-Source Systems

<div class="project-grid project-grid--4col">
  <div class="project-card">
    <span class="project-card__tag project-card__tag--detection">Industrial Vision</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2209.02976">YOLOv6</a></div>
    <div class="project-card__desc">An industrial object-detection framework with a full training-to-deployment toolchain and broad open-source adoption.</div>
    <div class="project-card__meta">Open Source · <a href="https://github.com/meituan/YOLOv6">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--detection">Spatial AI</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2602.22638">MobilityBench</a></div>
    <div class="project-card__desc">A real-world benchmark for evaluating route-planning agents in mobility scenarios, anchoring AMAP-ML's spatial-intelligence research direction.</div>
    <div class="project-card__meta">KDD 2026 Oral · <a href="https://github.com/AMAP-ML/MobilityBench">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--llm">World Models</span>
    <div class="project-card__title"><a href="https://arxiv.org/abs/2606.16993">DreamX-World</a></div>
    <div class="project-card__desc">A general-purpose interactive world model with controllable camera navigation, prompt-driven world events, an open-source 5B model, and a technical report.</div>
    <div class="project-card__meta">AMAP-ML · 2026 · <a href="https://arxiv.org/abs/2606.16993">tech report</a> · <a href="https://github.com/AMAP-ML/DreamX-World">code</a></div>
  </div>
  <div class="project-card">
    <span class="project-card__tag project-card__tag--llm">Agents</span>
    <div class="project-card__title"><a href="https://github.com/AMAP-ML/SkillClaw">SkillClaw</a></div>
    <div class="project-card__desc">An agentic skill-evolution system that turns real interaction traces into reusable skill libraries across sessions, devices, and agents.</div>
    <div class="project-card__meta">AMAP-ML · <a href="https://github.com/AMAP-ML/SkillClaw">code</a></div>
  </div>
</div>

---

First-Author Papers
======

<ol>
  <li><a href="https://arxiv.org/abs/2504.02546">GPG: A simple and strong reinforcement learning baseline for model reasoning</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/GPG">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2503.06132">USP: Unified self-supervised pretraining for image generation and understanding</a>, <strong>ICCV 2025</strong> <a href="https://github.com/AMAP-ML/USP">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2403.00522">VisionLLaMA: A Unified LLaMA Backbone for Vision Tasks</a>, <strong>ECCV 2024</strong> <a href="https://github.com/Meituan-AutoML/VisionLLaMA">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2402.03766">MobileVLM V2: Faster and Stronger Baseline for Vision Language Model</a> <a href="https://github.com/Meituan-AutoML/MobileVLM">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2312.16886">MobileVLM: A Fast, Strong and Open Vision Language Assistant for Mobile Devices</a> <a href="https://github.com/Meituan-AutoML/MobileVLM">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2212.01593">Make RepVGG Greater Again: A Quantization-aware Approach</a>, <strong>AAAI 2024</strong> <a href="https://github.com/cxxgtxy/QARepVGG">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2102.10882">Conditional Positional Encodings for Vision Transformers</a>, <strong>ICLR 2023</strong> <a href="https://github.com/Meituan-AutoML/CPVT">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2011.11233">ROME: Robustifying memory-efficient NAS via topology disentanglement and gradients accumulation</a>, <strong>ICCV 2023</strong></li>
  <li><a href="https://arxiv.org/abs/2001.05887">MixPATH: A unified approach for one-shot neural architecture search</a>, <strong>ICCV 2023</strong> <a href="https://github.com/xiaomi-automl/MixPath">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2011.13356">A Unified Mixture-View Framework for Unsupervised Representation Learning</a>, <strong>BMVC 2022</strong></li>
  <li><a href="https://arxiv.org/abs/2104.13840">Twins: Revisiting the design of spatial attention in vision transformers</a>, <strong>NeurIPS 2021</strong> <a href="https://github.com/Meituan-AutoML/Twins">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2009.01027">DARTS-: Robustly stepping out of performance collapse without indicators</a>, <strong>ICLR 2021</strong> <a href="https://github.com/Meituan-AutoML/DARTS-">[code]</a></li>
  <li><a href="https://arxiv.org/abs/1907.01845">FairNAS: Rethinking evaluation fairness of weight sharing neural architecture search</a>, <strong>ICCV 2021</strong> <a href="https://github.com/xiaomi-automl/FairNAS">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2005.03566">Noisy differentiable architecture search</a>, <strong>BMVC 2021</strong> <a href="https://github.com/xiaomi-automl/NoisyDARTS">[code]</a></li>
  <li><a href="https://arxiv.org/abs/1908.06022">Scarlet-NAS: Bridging the gap between stability and scalability in weight-sharing NAS</a>, <strong>ICCV Workshops 2021</strong> <a href="https://github.com/xiaomi-automl/SCARLET-NAS">[code]</a></li>
  <li><a href="https://arxiv.org/abs/1911.12126">Fair DARTS: Eliminating unfair advantages in differentiable architecture search</a>, <strong>ECCV 2020</strong> <a href="https://github.com/xiaomi-automl/FairDARTS">[code]</a></li>
  <li><a href="https://ieeexplore.ieee.org/document/9054428">MoGA: Searching beyond MobileNetV3</a>, <strong>ICASSP 2020</strong> <a href="https://github.com/xiaomi-automl/MoGA">[code]</a></li>
  <li><a href="https://arxiv.org/abs/1901.07261">Fast, accurate and lightweight super-resolution with neural architecture search</a>, <strong>ICPR 2020</strong> <a href="https://github.com/xiaomi-automl/FALSR">[code]</a></li>
  <li><a href="https://arxiv.org/abs/1901.01074">Multi-objective reinforced evolution in mobile neural architecture search</a>, <strong>ECCV Workshops 2020</strong></li>
  <li><a href="https://arxiv.org/abs/1807.00442">Policy optimization with penalized point probability distance: An alternative to PPO</a></li>
  <li><a href="https://arxiv.org/abs/1811.12667">Improved crowding distance for NSGA-II</a></li>
  <li><a href="https://arxiv.org/abs/1710.00336">Parameter sharing deep deterministic policy gradient for cooperative multi-agent reinforcement learning</a></li>
</ol>

---

Collaborative Papers
======

### Image Generation & Editing

<ol>
  <li><a href="https://arxiv.org/abs/2605.15803">E<sup>2</sup>PO: Embedding-perturbed Exploration Preference Optimization for Flow Models</a>, <strong>ICML 2026</strong></li>
  <li>MAR-GRPO: Stabilized GRPO for AR-Diffusion Hybrid Image Generation</li>
  <li>ConceptWeaver: Weaving Disentangled Concepts with Flow</li>
  <li><a href="https://arxiv.org/abs/2604.16044">Elucidating the SNR-t Bias of Diffusion Probabilistic Models</a>, <strong>CVPR 2026</strong> <a href="https://github.com/AMAP-ML/DCW">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2603.05769">Layer-wise Instance Binding for Regional and Occlusion Control in Text-to-Image Diffusion Transformers</a>, <strong>CVPR 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2603.03143">Geometry-Guided Reinforcement Learning for Multi-view Consistent 3D Scene Editing</a> <a href="https://github.com/AMAP-ML/RL3DEdit">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2603.00141">From Scale to Speed: Adaptive Test-Time Scaling for Image Editing</a>, <strong>CVPR 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2512.24146">Taming Preference Mode Collapse via Directional Decoupling Alignment in Diffusion Reinforcement Learning</a>, <strong>CVPR 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2509.04338">From editor to dense geometry estimator</a>, <strong>CVPR 2026</strong> <a href="https://github.com/AMAP-ML/FE2E">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2508.16158">Ragsr: Regional attention guided diffusion for image super-resolution</a></li>
  <li><a href="https://arxiv.org/abs/2508.12880">S2-Guidance: Stochastic Self Guidance for Training-Free Enhancement of Diffusion Models</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/S2-Guidance">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2507.00790">LD-RPS: Zero-Shot Unified Image Restoration via Latent Diffusion Recurrent Posterior Sampling</a>, <strong>ICCV 2025</strong> <a href="https://github.com/AMAP-ML/LD-RPS">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2505.03329">Flux-text: A simple and advanced diffusion transformer baseline for scene text editing</a></li>
  <li><a href="https://arxiv.org/abs/2411.14871">Preference Alignment for Diffusion Model via Explicit Denoised Distribution Estimation</a></li>
  <li><a href="https://arxiv.org/abs/2408.05008">FlowDreamer: exploring high fidelity text-to-3D generation via rectified flow</a></li>
  <li>TEXTS-Diff: TEXTS-Aware Diffusion Model for Real-World Text Image Super-Resolution, <strong>ICASSP 2026</strong></li>
  <li><a href="https://openaccess.thecvf.com/content/ACCV2020/html/Ma_Accurate_and_Efficient_Single_Image_Super-Resolution_with_Matrix_Channel_Attention_ACCV_2020_paper.html">Accurate and efficient single image super-resolution with matrix channel attention network</a>, <strong>ACCV 2020</strong></li>
</ol>

### Video Generation & Understanding

<ol>
  <li><a href="https://arxiv.org/abs/2605.18233">MIGA: Enhancing Train-Free Infinite-Frame Generation for Consistent Long Videos</a>, <strong>ICML 2026</strong></li>
  <li>Omni-WorldBench: Towards a Comprehensive Interaction-Centric Evaluation for World Models</li>
  <li><a href="https://arxiv.org/abs/2603.14935">Video-CoE: Reinforcing Video Event Prediction via Chain of Events</a>, <strong>CVPR 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2512.24271">Taming Hallucinations: Boosting MLLMs' Video Understanding via Counterfactual Video Generation</a></li>
  <li><a href="https://arxiv.org/abs/2511.18957">Eevee: Towards Close-up High-resolution Video-based Virtual Try-on</a>, <strong>CVPR 2026 Findings</strong> <a href="https://github.com/AMAP-ML/Eevee">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2510.14847">ImagerySearch: Adaptive Test-Time Search for Video Generation Beyond Semantic Dependency Constraints</a>, <strong>AAAI 2026</strong> <a href="https://github.com/AMAP-ML/ImagerySearch">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2510.08480">Video-star: Reinforcing open-vocabulary action recognition with tools</a>, <strong>ICLR 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2508.07981">Omni-effects: Unified and spatially-controllable visual effects generation</a>, <strong>AAAI 2026</strong> <a href="https://github.com/AMAP-ML/Omni-Effects">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2507.11245">Narrlv: Towards a comprehensive narrative-centric evaluation for long video generation models</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/NarrLV">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2503.10076">VMBench: A Benchmark for Perception-Aligned Video Motion Generation</a>, <strong>ICCV 2025</strong> <a href="https://github.com/AMAP-ML/VMBench">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2504.10358">FingER: Content Aware Fine-grained Evaluation with Reasoning for AI-Generated Videos</a>, <strong>ACM MM 2025</strong> <a href="https://github.com/AMAP-ML/FingER">[code]</a></li>
  <li>Latent Temporal Discrepancy as Motion Prior: A Loss-Weighting Strategy for Dynamic Fidelity in T2V, <strong>ICASSP 2026</strong></li>
  <li>Artifact-Aware Evaluation for High-Quality Video Generation, <strong>ICASSP 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2204.02547">Modeling Motion with Multi-Modal Features for Text-Based Video Segmentation</a>, <strong>CVPR 2022</strong></li>
</ol>

### LLM Reasoning & Agents

<ol>
  <li><a href="https://arxiv.org/abs/2605.17037">D<sup>2</sup>Evo: Dual Difficulty-Aware Self-Evolution for Data-Efficient Reinforcement Learning</a>, <strong>ICML 2026</strong></li>
  <li>SkillClaw: Let Skills Evolve Collectively with Agentic Evolver <a href="https://github.com/AMAP-ML/SkillClaw">[code]</a></li>
  <li>Ace-Skill: Bootstrapping Multimodal Agents with Prioritized and Clustered Evolution</li>
  <li>Learning Agentic Policy from Action Guidance</li>
  <li><a href="https://arxiv.org/abs/2604.15840">CoEvolve: Training LLM Agents via Agent-Data Mutual Evolution</a>, <strong>ACL 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2602.09856">Code2World: A GUI World Model via Renderable Code Generation</a> <a href="https://github.com/AMAP-ML/Code2World">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2602.01884">Entropy-Guided Data-Efficient Training for Multimodal Reasoning Reward Models</a></li>
  <li><a href="https://arxiv.org/abs/2601.20614">Harder Is Better: Boosting Mathematical Reasoning via Difficulty-Aware GRPO and Multi-Aspect Question Reformulation</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/MathForge">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2511.09478">AdaCuRL: Adaptive Curriculum Reinforcement Learning with Invalid Sample Mitigation and Historical Revisiting</a>, <strong>AAAI 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2509.21240">Tree search for LLM agent reinforcement learning</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/Tree-GRPO">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2509.01944">AutoDrive-R2: Incentivizing Reasoning and Self-Reflection Capacity for VLA Model in Autonomous Driving</a>, <strong>ICLR 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2508.15709">Position bias mitigates position bias: Mitigate position bias through inter-position knowledge distillation</a>, <strong>EMNLP 2025 oral</strong> <a href="https://github.com/AMAP-ML/Pos2Distill">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2505.19866">HS-STAR: Hierarchical Sampling for Self-Taught Reasoners via Difficulty Estimation and Budget Reallocation</a>, <strong>EMNLP 2025 oral</strong> <a href="https://github.com/AMAP-ML/HS-STaR">[code]</a></li>
  <li>Ranking-aware Reinforcement Learning for Ordinal Ranking, <strong>ICASSP 2026</strong></li>
</ol>

### Multimodal & Vision-Language

<ol>
  <li><a href="https://arxiv.org/abs/2601.21406">UniMRG: Generation Enhances Understanding in Unified Multimodal Models via Multi-Representation Generation</a>, <strong>ICML 2026</strong></li>
  <li>Visual Enhanced Depth Scaling for Multimodal Latent Reasoning</li>
  <li><a href="https://arxiv.org/abs/2604.17295">LLaTiSA: Towards Difficulty-Stratified Time Series Reasoning from Visual Perception to Semantics</a>, <strong>ACL 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2602.11499">What if Agents Could Imagine? Reinforcing Open-Vocabulary HOI Comprehension through Generation</a></li>
  <li><a href="https://arxiv.org/abs/2604.09349">Visually-Guided Policy Optimization for Multimodal Reasoning</a>, <strong>ACL 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2403.04343">Adaptive Task Balancing for Visual Instruction Tuning via Inter-Task Contribution and Intra-Task Difficulty</a>, <strong>WWW 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2601.22920">Q-Hawkeye: Reliable Visual Policy Optimization for Image Quality Assessment</a> <a href="https://github.com/AMAP-ML/Q-Hawkeye">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2601.20354">Everything in Its Place: Benchmarking Spatial Intelligence of Text-to-Image Models</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/SpatialGenEval">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2601.10477">Urban Socio-Semantic Segmentation with Vision-Language Reasoning</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/SocioReasoner">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2511.08246">Where and What Matters: Sensitivity-Aware Task Vectors for Many-Shot Multimodal In-Context Learning</a>, <strong>AAAI 2026</strong> <a href="https://github.com/AMAP-ML/STV">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2505.14231">Univg-r1: Reasoning guided universal visual grounding with reinforcement learning</a></li>
  <li><a href="https://arxiv.org/abs/2503.06141">Next Token Is Enough: Realistic Image Quality and Aesthetic Scoring with Multimodal Large Language Model</a></li>
  <li><a href="https://arxiv.org/abs/2411.14062">Mmgenbench: Evaluating the limits of LMMs from the text-to-image generation perspective</a></li>
  <li><a href="https://arxiv.org/abs/2312.02433">Lenna: Language Enhanced Reasoning Detection Assistant</a>, <strong>ICASSP 2025</strong> <a href="https://github.com/Meituan-AutoML/Lenna">[code]</a></li>
</ol>

### Detection, Segmentation & 3D Perception

<ol>
  <li><a href="https://arxiv.org/abs/2507.00721">UPRE: Zero-Shot Domain Adaptation for Object Detection via Unified Prompt and Representation Enhancement</a>, <strong>ICCV 2025</strong> <a href="https://github.com/AMAP-ML/UPRE">[code]</a></li>
  <li>PLUG: Revisiting Amodal Segmentation with Foundation Model and Hierarchical Focus, <strong>CVPR 2025</strong></li>
  <li><a href="https://arxiv.org/abs/2312.17071">SCTNet: Single Branch CNN with Transformer Semantic Information for Real-time Segmentation</a>, <strong>AAAI 2024</strong></li>
  <li><a href="https://arxiv.org/abs/2302.02367">FastPillars: A Deployment-friendly Pillar-based 3D Detector</a>, <strong>IEEE TCSVT</strong></li>
  <li><a href="https://arxiv.org/abs/2301.05586">Yolov6 v3.0: A full-scale reloading</a></li>
  <li><a href="https://arxiv.org/abs/2211.12501">AeDet: Azimuth-invariant multi-view 3D object detection</a>, <strong>CVPR 2023</strong></li>
  <li><a href="https://arxiv.org/abs/2210.05844">SegViT: Semantic segmentation with plain vision transformers</a>, <strong>NeurIPS 2022</strong></li>
  <li><a href="https://arxiv.org/abs/2209.02976">YOLOv6: A single-stage object detection framework for industrial applications</a>, <strong>arXiv</strong> <a href="https://github.com/meituan/YOLOv6">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2205.13764">Fully convolutional one-stage 3D object detection on LiDAR range images</a>, <strong>NeurIPS 2022</strong></li>
  <li><a href="https://arxiv.org/abs/2203.16513">PromptDet: Towards open-vocabulary detection using uncurated images</a>, <strong>ECCV 2022</strong></li>
  <li><a href="https://arxiv.org/abs/2109.14483">Cctrans: Simplifying and improving crowd counting with transformer</a></li>
</ol>

### Foundation Model Architectures

<ol>
  <li><a href="https://arxiv.org/abs/2602.03152">FASA: Frequency-Aware Sparse Attention</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/FASA-ICLR2026">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2604.08964">Breaking Block Boundaries: Anchor-based History-stable Decoding for Diffusion Large Language Models</a>, <strong>ACL 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2602.02178">AR-MAP: Are Autoregressive Large Language Models Implicit Teachers for Diffusion Large Language Models?</a> <a href="https://github.com/AMAP-ML/AR-MAP">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2511.14063">Semantic Context Matters: Improving Conditioning for Autoregressive Models</a>, <strong>CVPR 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2604.18168">Extending One-Step Image Generation from Class Labels to Text via Discriminative Text Representation</a>, <strong>CVPR 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2510.12586">There is No VAE: End-to-End Pixel-Space Generative Modeling via Self-Supervised Pre-training</a>, <strong>ICLR 2026</strong> <a href="https://github.com/AMAP-ML/EPG">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2507.19946">Scalar: Scale-wise controllable visual autoregressive learning</a>, <strong>AAAI 2026</strong> <a href="https://github.com/AMAP-ML/SCALAR">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2407.14302">Dyn-Adapter: Towards Disentangled Representation for Efficient Visual Recognition</a>, <strong>ECCV 2024</strong></li>
  <li><a href="https://arxiv.org/abs/2407.08972">Revealing the Dark Secrets of Extremely Large Kernel ConvNets on Robustness</a>, <strong>ICML 2024</strong></li>
  <li><a href="https://arxiv.org/abs/2403.07589">PeLK: Parameter-efficient Large Kernel ConvNets with Peripheral Convolution</a>, <strong>CVPR 2024</strong></li>
  <li><a href="https://arxiv.org/abs/2302.00386">Efficientrep: an efficient repvgg-style convnets with hardware-aware neural network design</a></li>
</ol>

### Model Compression & AutoML

<ol>
  <li>Robust MAE-Driven NAS: From Mask Reconstruction to Architecture Innovation, <strong>ICASSP 2026</strong></li>
  <li><a href="https://arxiv.org/abs/2401.15865">LiDAR-PTQ: Post-Training Quantization for Point Cloud 3D Object Detection</a>, <strong>ICLR 2024</strong></li>
  <li><a href="https://arxiv.org/abs/2311.12086">Masked Autoencoders Are Robust Neural Architecture Search Learners</a></li>
  <li><a href="https://arxiv.org/abs/2311.09550">A Speed Odyssey for Deployable Quantization of LLMs</a></li>
  <li><a href="https://arxiv.org/abs/2309.02784">Norm Tweaking: High-performance Low-bit Quantization of Large Language Models</a>, <strong>AAAI 2024</strong></li>
  <li><a href="https://arxiv.org/abs/2308.15987">FPTQ: Fine-grained Post-Training Quantization for Large Language Models</a></li>
  <li><a href="https://arxiv.org/abs/2210.00181">EAPruning: Evolutionary Pruning for Vision Transformers and CNNs</a>, <strong>BMVC 2022</strong></li>
  <li><a href="https://arxiv.org/abs/2109.15273">DAAS: Differentiable architecture and augmentation policy search</a></li>
  <li><a href="https://arxiv.org/abs/2009.03658">AutoKWS: Keyword Spotting with Differentiable Architecture Search</a>, <strong>ICASSP 2021</strong></li>
  <li>Neural Architecture Search on Acoustic Scene Classification, <strong>InterSpeech 2020</strong></li>
</ol>

### Maps, Mobility & Recommendation

<ol>
  <li><a href="https://arxiv.org/abs/2602.22638">MobilityBench: A Benchmark for Evaluating Route-Planning Agents in Real-World Mobility Scenarios</a>, <strong>KDD 2026 Oral</strong> <a href="https://github.com/AMAP-ML/MobilityBench">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2602.20704">IntRR: A Framework for Integrating SID Redistribution and Length Reduction for Generative Recommendation</a> <a href="https://github.com/AMAP-ML/IntRR">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2602.11664">IntTravel: A Real-World Dataset and Generative Framework for Integrated Multi-Task Travel Recommendation</a> <a href="https://github.com/AMAP-ML/IntTravel">[code]</a></li>
  <li><a href="https://arxiv.org/abs/2602.04174">GenMRP: A Generative Multi-Route Planning Framework for Efficient and Personalized Real-Time Industrial Navigation</a></li>
  <li><a href="https://arxiv.org/abs/2602.03324">SCASRec: A Self-Correcting and Auto-Stopping Model for Generative Route List Recommendation</a></li>
  <li><a href="https://arxiv.org/abs/2601.05432">Thinking with Map: Reinforced Parallel Map-Augmented Agent for Geolocalization</a>, <strong>ACL 2026 Findings</strong></li>
  <li><a href="https://arxiv.org/abs/2509.21179">Intsr: An integrated generative framework for search and recommendation</a></li>
  <li><a href="https://arxiv.org/abs/2508.08745">Comprehensive Comparison Network: a framework for locality-aware, routes-comparable and interpretable route recommendation</a></li>
  <li><a href="https://arxiv.org/abs/2505.11306">Effective Probabilistic Time Series Forecasting with Fourier Adaptive Noise-Separated Diffusion</a></li>
  <li>DSFNet: Learning Disentangled Scenario Factorization for Multi-Scenario Route Ranking, <strong>WWW 2025</strong> <a href="https://github.com/AMAP-ML/DSFNet">[code]</a></li>
</ol>
