---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<div class="home-page">
  <section class="home-hero">
    <p class="home-eyebrow">PhD Candidate, HKUST ECE / ACCESS</p>
    <h1>Kunming SHAO <span>邵堃明</span></h1>
    <p class="home-lede">
      I am a PhD candidate at The Hong Kong University of Science and Technology (HKUST) and the AI Chip Center for Emerging Smart Systems (ACCESS), supervised by
      <strong>Prof. Chi-Ying TSUI</strong> and <strong>Prof. Tim Kwang-Ting CHENG</strong>.
      My research connects digital compute-in-memory circuits, AI accelerator architecture, compiler automation, efficient ML systems, edge LLM agents, and quantization.
    </p>
    <p class="home-lede home-lede--secondary">
      I expect to graduate in Summer 2027 and am actively exploring postdoctoral opportunities in AI hardware, computing-in-memory, and efficient intelligence systems.
    </p>
    <div class="home-actions" aria-label="Profile links">
      <a href="{{ base_path }}/publications/">Publications</a>
      <a href="https://scholar.google.com/citations?user=JU6McLoAAAAJ&hl=zh-CN">Google Scholar</a>
      <a href="mailto:kshaoaa@connect.ust.hk">Email</a>
    </div>
  </section>

  <section class="home-stats" aria-label="Profile highlights">
    <div>
      <span>Current role</span>
      <strong>PhD Candidate</strong>
      <p>HKUST ECE / ACCESS</p>
    </div>
    <div>
      <span>Previous degree</span>
      <strong>BEng, SCUT</strong>
      <p>Excellent graduation thesis</p>
    </div>
    <div>
      <span>Recognition</span>
      <strong>HKPFS & RedBird</strong>
      <p>Fellowship and academic awards</p>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section-head">
      <p class="home-eyebrow">Research Focus</p>
      <h2>Hardware-efficient intelligence from circuit to system</h2>
    </div>
    <div class="focus-grid">
      <article class="focus-card focus-card--teal">
        <h3>Digital CIM and ReRAM</h3>
        <p>Macro architecture, robust in-memory computation, hybrid SRAM/ReRAM cells, and design automation for digital compute-in-memory.</p>
      </article>
      <article class="focus-card focus-card--amber">
        <h3>AI accelerators</h3>
        <p>Energy-efficient accelerators for DNNs, SNNs, Transformers, FlashAttention, stochastic/approximate computing, and FP8 computation.</p>
      </article>
      <article class="focus-card focus-card--blue">
        <h3>ML systems and agents</h3>
        <p>Edge RAG, wearable medical LLM agents, retrieval acceleration, quantization, and hardware-aware deployment of efficient models.</p>
      </article>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section-head">
      <p class="home-eyebrow">Selected Threads</p>
      <h2>Recent publication directions</h2>
    </div>
    <div class="thread-list">
      <a class="thread-item" href="{{ base_path }}/publication/ESSERC_26">
        <span>ESSERC'26</span>
        <strong>SwiftCIM</strong>
        <p>ReRAM-coupled digital CIM accelerator for FlashAttention dataflow.</p>
      </a>
      <a class="thread-item" href="{{ base_path }}/publication/TVLSI_26">
        <span>IEEE TVLSI</span>
        <strong>FP8 DCIM</strong>
        <p>Shift-aware aligned-mantissa bitwidth prediction for efficient FP8 computation on digital CIM.</p>
      </a>
      <a class="thread-item" href="{{ base_path }}/publication/DATE_26">
        <span>DATE'26</span>
        <strong>DS-CIM</strong>
        <p>Digital stochastic CIM with accurate OR-accumulation for edge AI models.</p>
      </a>
      <a class="thread-item" href="{{ base_path }}/publication/BioCAS_25">
        <span>BioCAS'25</span>
        <strong>Wearable Medical RAG</strong>
        <p>Memory-efficient retrieval architecture for RAG-enabled wearable medical LLM agents.</p>
      </a>
      <a class="thread-item" href="{{ base_path }}/publication/ISLPED_25">
        <span>ISLPED'25</span>
        <strong>DIRC-RAG</strong>
        <p>High-density digital In-ReRAM computation for edge RAG retrieval.</p>
      </a>
      <a class="thread-item" href="{{ base_path }}/publication/DATE_25">
        <span>DATE'25</span>
        <strong>SynDCIM</strong>
        <p>Performance-aware DCIM compiler with multi-spec subcircuit synthesis.</p>
      </a>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section-head">
      <p class="home-eyebrow">News</p>
      <h2>Latest updates</h2>
    </div>
    <div class="news-timeline">
      <article>
        <time datetime="2026-05-18">May 18, 2026</time>
        <p><strong>RedBird Award:</strong> I received the HKUST RedBird Academic Excellence Award.</p>
      </article>
      <article>
        <time datetime="2026-05-14">May 14, 2026</time>
        <p><strong>ESSERC'26:</strong> My first-authored paper <em>SwiftCIM: a 55nm 23.2&mu;J/Token L-0.5 ReRAM Coupled Digital CIM Accelerator with Fully-Fused Multi-Head Attention Dataflow for FlashAttention</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2026-05-13">May 13, 2026</time>
        <p><strong>TVLSI:</strong> The paper I led and co-first-authored, <em>Balancing FP8 Computation Accuracy and Efficiency on Digital CIM via Shift-Aware On-the-fly Aligned-Mantissa Bitwidth Prediction</em>, was accepted.</p>
      </article>
      <article>
        <time datetime="2026-05-11">May 11, 2026</time>
        <p><strong>US Patent:</strong> Our co-authored patent on a hybrid computing-in-memory device and multi-level sensing method was approved and published.</p>
      </article>
      <article>
        <time datetime="2026-05-04">May 4, 2026</time>
        <p><strong>Chinese Patent:</strong> Our co-authored patent on a hybrid CIM device and multi-level data-bit sensing method was approved and published.</p>
      </article>
      <article>
        <time datetime="2025-11-05">Nov 5, 2025</time>
        <p><strong>DATE'26:</strong> My first-authored paper <em>DS-CIM: Digital Stochastic Computing-In-Memory Featuring Accurate OR-Accumulation via Sample Region Remapping for Edge AI Models</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2025-09-08">Sep 8, 2025</time>
        <p><strong>A-SSCC'25:</strong> Our co-authored paper <em>Lemem: A 179.8TFLOPS/W, 24.21TFLOPS Learning-In-Memory Processor with Layer-Fused Forward/Backward Pipeline for Edge DNN/SNN Training/Inference</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2025-08-01">Aug 1, 2025</time>
        <p><strong>BioCAS'25:</strong> The paper I led and co-first-authored, <em>A Memory-Efficient Retrieval Architecture for RAG-Enabled Wearable Medical LLMs-Agents</em>, was accepted.</p>
      </article>
      <article>
        <time datetime="2025-07-18">Jul 18, 2025</time>
        <p><strong>TCAD:</strong> Our co-authored paper <em>Configurable Dataflow and Adaptive Mapping Optimization for Hybrid ReRAM and SRAM Compute-in-Memory Accelerator</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2025-07-16">Jul 16, 2025</time>
        <p><strong>CASS Travel Grant:</strong> I received the IEEE CASS Student Travel Grant.</p>
      </article>
      <article>
        <time datetime="2025-05-19">May 19, 2025</time>
        <p><strong>ISLPED'25:</strong> My first-authored paper <em>DIRC-RAG: Accelerating Edge RAG with Robust High-Density and High-Loading-Bandwidth Digital In-ReRAM Computation</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2025-02-26">Feb 26, 2025</time>
        <p><strong>DAC'25 WIP:</strong> My work-in-progress poster on AI accelerators based on approximate computing was accepted.</p>
      </article>
      <article>
        <time datetime="2025-01-13">Jan 13, 2025</time>
        <p><strong>CICC'25:</strong> Our co-first-authored paper <em>E-NPU: A 34~126nJ/Class Event-Driven Adaptive Neural SoC with Signal-Dynamics-Aware Feature Clustering and Multi-Model In-Memory Inference/Training for Personalized Medical Wearables</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2025-01-09">Jan 9, 2025</time>
        <p><strong>ISCAS'25:</strong> Our co-first-authored paper <em>A Flexible Precision Scaling Deep Neural Network Accelerator with Efficient Weight Combination</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2024-12-06">Dec 6, 2024</time>
        <p><strong>PQE:</strong> I passed the PhD Qualification Exam and continued as a PhD candidate.</p>
      </article>
      <article>
        <time datetime="2024-11-13">Nov 13, 2024</time>
        <p><strong>DATE'25:</strong> My first-authored paper <em>SynDCIM: A Performance-Aware Digital Computing-in-Memory Compiler with Multi-Spec-Oriented Subcircuit Synthesis</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2024-07-13">Jul 13, 2024</time>
        <p><strong>ICCAD'24:</strong> Our co-authored paper <em>ReSCIM: Variation-Resilient High Weight-Loading Bandwidth In-Memory Computation Based on Fine-Grained Hybrid Integration of Multi-Level ReRAM and SRAM Cells</em> was accepted.</p>
      </article>
      <article>
        <time datetime="2023-06-19">Jun 19, 2023</time>
        <p><strong>Thesis:</strong> My BEng thesis, <em>Digital Compute-In-Memory Automatic Design Methodology</em>, was selected as an excellent graduation project at SCUT.</p>
      </article>
      <article>
        <time datetime="2023-04-12">Apr 12, 2023</time>
        <p><strong>HKPFS & RedBird:</strong> I received the Hong Kong PhD Fellowship and HKUST RedBird Award.</p>
      </article>
      <article>
        <time datetime="2023-02-14">Feb 14, 2023</time>
        <p><strong>DAC'23:</strong> Our co-authored paper <em>AutoDCIM: An Automated Digital CIM Compiler</em> was accepted.</p>
      </article>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section-head">
      <p class="home-eyebrow">Collaborations</p>
      <h2>Research group and joint projects</h2>
    </div>
    <p class="home-copy">
      I coordinate a multi-institution collaboration across HKUST, SCUT, Westlake University, SYSU, WHU, and other partners on in-memory computation, approximate computing, efficient algorithms, and emerging non-volatile memories. The projects below highlight first/co-first author and corresponding-author roles.
    </p>
    <div class="collab-grid">
      <article><span>DATE'25</span><strong>DCIM circuit design and automation</strong><p>Kunming Shao and Fengshi Tian, HKUST.</p></article>
      <article><span>ISCAS'25</span><strong>Digital PE design</strong><p>Liang Zhao, SCUT, and Kunming Shao, HKUST.</p></article>
      <article><span>CICC'25</span><strong>Medical neural SoC</strong><p>Fengshi Tian, HKUST; Jinbo Chen, Westlake; Kunming Shao, HKUST.</p></article>
      <article><span>DAC'25 WIP</span><strong>Approximate computing accelerator</strong><p>Kunming Shao, HKUST, and Liang Zhao, SCUT.</p></article>
      <article><span>ISLPED'25</span><strong>Edge LLM and RAG acceleration</strong><p>Kunming Shao, HKUST; Zhipeng Liao, Westlake; Jiangnan Yu and Xiaomeng Wang, HKUST.</p></article>
      <article><span>BioCAS'25</span><strong>Wearable edge devices</strong><p>Zhipeng Liao, Westlake, and Kunming Shao, HKUST.</p></article>
      <article><span>DATE'26</span><strong>Digital stochastic CIM</strong><p>Kunming Shao, HKUST, and Liang Zhao, SCUT.</p></article>
      <article><span>IEEE TVLSI</span><strong>FP8 computing on digital CIM</strong><p>Liang Zhao, SCUT, and Kunming Shao, HKUST.</p></article>
      <article><span>ESSERC'26</span><strong>L-0.5 memory for MHA</strong><p>Kunming Shao and Xiaomeng Wang, HKUST.</p></article>
    </div>
  </section>

  <section class="home-contact">
    <h2>Contact</h2>
    <p><a href="mailto:kshaoaa@connect.ust.hk">kshaoaa@connect.ust.hk</a> / <a href="mailto:kshaoaa@foxmail.com">kshaoaa@foxmail.com</a></p>
  </section>
</div>

<script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=dlQewDWXOFOO3ktbqFfI4LrHeaJPHclAPktKulGKfIo"></script>
