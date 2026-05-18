---
layout: page
title: Highlighted Projects
permalink: /projects/
description:
nav: true
nav_order: 4
---

<div class="proj-list">

  <!-- Foundation DL Model for CryoET -->
  <div class="proj-entry">
    <div class="proj-header">
      <div class="proj-left">
        <span class="proj-title">Foundation Deep Learning Model for CryoET</span>
        <span class="proj-tech">Python &middot; PyTorch</span>
      </div>
      <span class="proj-date">Dec. 2025 – Present</span>
    </div>
    <ul class="proj-bullets">
      <li>Working on a foundation DL model for object detection and segmentation in <strong>CryoET 3D tomograms</strong>.</li>
      <li>Gathered ~1,600 3D tomograms and generated <strong>350,000+ 3D patches</strong> for pretraining using the <strong>3DINO self-supervised learning</strong> approach.</li>
      <li>Finetuning the model on different downstream tasks and benchmarking against baseline models <em>(in progress)</em>.</li>
    </ul>
  </div>

  <!-- Agentic AI for Digital Pathology -->
  <div class="proj-entry">
    <div class="proj-header">
      <div class="proj-left">
        <span class="proj-title">Agentic AI System for Digital Pathology</span>
        <span class="proj-tech">Python &middot; PyTorch &middot; LangChain &middot; VLM</span>
      </div>
      <span class="proj-date">Nov. 2025 – Present</span>
    </div>
    <ul class="proj-bullets">
      <li>Engineered a <strong>multi-modal agentic framework</strong> orchestrating custom tools for automated WSI analysis, including Visual Question Answering (VQA), report generation, and zero-shot classification and ROI segmentation.</li>
      <li>Integrated state-of-the-art pathology foundation models (<strong>SlideChat, TITAN, CONCH, MUSK</strong>) to enable context-aware reasoning over gigapixel-scale images.</li>
      <li>Implemented a <strong>human-in-the-loop</strong> interface with a hierarchical k-means algorithm to iteratively refine model predictions, ensuring interpretability and clinical alignment.</li>
    </ul>
  </div>

  <!-- MAPL3 -->
  <div class="proj-entry">
    <div class="proj-header">
      <div class="proj-left">
        <span class="proj-title">MAPL3 — Mapping Axonal Projection in Light Sheet Microscopy in 3D</span>
        <span class="proj-tech">Python &middot; Bash</span>
      </div>
      <span class="proj-date">Jan. 2023 – May 2025</span>
    </div>
    <ul class="proj-bullets">
      <li>Developed a 3D computational pipeline for identifying <strong>individual axonal fibers</strong> and their brain-wide circuitry at single-fiber resolution.</li>
      <li>Pioneered a novel DL architecture combining <strong>convolutional neural networks and vision transformers</strong>.</li>
      <li>Deployed <strong>self-supervised</strong> approaches to improve model generalizability and reduce dependency on labeled data.</li>
      <li>Designed and implemented <strong>parallelized image processing</strong> pipelines for pre- and post-processing <a href="https://github.com/AAttarpour/microscopy-image-analysis" target="_blank">[code]</a>.</li>
    </ul>
  </div>

  <!-- ACE -->
  <div class="proj-entry">
    <div class="proj-header">
      <div class="proj-left">
        <span class="proj-title">
          <a href="https://miracl.readthedocs.io/en/latest/tutorials/workflows/ace_flow/ace_flow.html" target="_blank">ACE — AI-based Cartography of Ensembles</a>
        </span>
        <span class="proj-tech">Python &middot; Fiji &middot; Bash &middot; Docker &middot; Git</span>
      </div>
      <span class="proj-date">Jan. 2020 – Jan. 2025</span>
    </div>
    <ul class="proj-bullets">
      <li>Designed and implemented an <strong>end-to-end 3D pipeline</strong> for mapping local cell activity in <strong>tera-voxel scale (~1TB/sample)</strong> light sheet microscopy datasets.</li>
      <li>Engineered an ensemble of <strong>convolutional and vision transformer-based</strong> models for soma segmentation.</li>
      <li>Integrated <strong>Monte Carlo dropout</strong> for probabilistic model uncertainty estimation.</li>
      <li>Optimized cluster-wise permutation statistical analysis for high-dimensional whole-brain microscopy data.</li>
    </ul>
  </div>

  <!-- Foundation DL Model for Light Microscopy -->
  <div class="proj-entry">
    <div class="proj-header">
      <div class="proj-left">
        <span class="proj-title">Foundation Deep Learning Model for Light Microscopy</span>
        <span class="proj-tech">Python &middot; Bash &middot; Git</span>
      </div>
      <span class="proj-date">Jan. 2023 – Dec. 2025</span>
    </div>
    <ul class="proj-bullets">
      <li>Working on a foundation DL model for object segmentation across microscopy datasets and modalities.</li>
      <li>Gathered ~<strong>3 million 3D image patches</strong> from multiple centers and modalities for pretraining using the <strong>3DINO self-supervised</strong> approach.</li>
      <li>Finetuning for axon, soma, and vascular segmentation; benchmarking against state-of-the-art models.</li>
    </ul>
  </div>

  <!-- EchoJEPA -->
  <div class="proj-entry">
    <div class="proj-header">
      <div class="proj-left">
        <span class="proj-title">
          <a href="https://echojepa.com/" target="_blank">EchoJEPA — Latent Predictive Foundation Model for Echocardiography</a>
        </span>
        <span class="proj-tech">Python &middot; PyTorch &middot; Self-Supervised Learning</span>
      </div>
      <span class="proj-date">2024 – Present</span>
    </div>
    <ul class="proj-bullets">
      <li>Contributed significantly to the development of EchoJEPA — a <strong>latent predictive (JEPA) foundation model</strong> for echocardiography pretrained on <strong>18 million videos across 300K patients</strong> — through technical implementation, experimental design, model evaluation, and interpretation of research findings.</li>
      <li>Collaborated closely with an interdisciplinary team on methodological development, validation strategies, and scientific discussions to ensure robust and clinically meaningful outcomes.</li>
      <li>Contributed to manuscript preparation, figure generation, and scientific narrative refinement; model achieves <strong>~20% improvement in LVEF estimation</strong> and <strong>78.6% view classification accuracy</strong> using only 1% of labeled data <a href="https://echojepa.com/" target="_blank">[website]</a>.</li>
    </ul>
  </div>

  <!-- Pancreas Multi-Task Learning -->
  <div class="proj-entry">
    <div class="proj-header">
      <div class="proj-left">
        <span class="proj-title">
          <a href="https://github.com/AAttarpour/nnunetv2-pancreas-multitask" target="_blank">Pancreas Multi-Task Learning with nnUNetV2</a>
        </span>
        <span class="proj-tech">Python &middot; PyTorch &middot; Git</span>
      </div>
      <span class="proj-date">Apr. 2025 – Jun. 2025</span>
    </div>
    <ul class="proj-bullets">
      <li>Developed a DL pipeline for <strong>joint pancreas segmentation and subtype classification</strong> on abdominal CT using a modified nnUNetV2 backbone.</li>
      <li>Integrated a custom classification head with multi-scale feature adapters and fusion modules processing encoder outputs alongside segmentation decoding.</li>
      <li>Achieved average Dice of <strong>0.90 (pancreas)</strong> and <strong>0.60 (lesion)</strong>, macro F1 of <strong>0.81</strong>; reduced inference time by <strong>24%</strong> via optimized prediction loop.</li>
    </ul>
  </div>

  <!-- PPG Blood Pressure -->
  <div class="proj-entry">
    <div class="proj-header">
      <div class="proj-left">
        <span class="proj-title">System for Recording and Analyzing Pulse Signals</span>
        <span class="proj-tech">MATLAB</span>
      </div>
      <span class="proj-date">Sept. 2015 – Jun. 2016</span>
    </div>
    <ul class="proj-bullets">
      <li>Designed a system for <strong>continuous blood pressure measurement</strong> using PPG recorded from wrist and fingertip.</li>
      <li>Developed an <strong>MLP neural network</strong> to estimate SBP/DBP with mean absolute errors of 4.94 mmHg and 4.03 mmHg.</li>
      <li>Implemented feature selection algorithms including <strong>moving-backward and genetic optimization</strong> to identify the most significant signal features.</li>
    </ul>
  </div>

</div>

<style>
  .proj-list {
    max-width: 900px;
    margin: 0 auto;
  }

  .proj-entry {
    border-bottom: 1px solid var(--global-divider-color, #e0e0e0);
    padding: 1.2rem 0;
  }

  .proj-entry:last-child {
    border-bottom: none;
  }

  .proj-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-bottom: 0.6rem;
  }

  .proj-left {
    display: flex;
    flex-direction: column;
    gap: 0.25rem;
  }

  .proj-title {
    font-weight: 700;
    font-size: 1rem;
    color: var(--global-text-color, #212529);
  }

  .proj-title a {
    color: var(--global-text-color, #212529);
    text-decoration: underline;
    text-underline-offset: 3px;
  }

  .proj-title a:hover {
    color: #4a90d9;
  }

  .proj-tech {
    font-size: 0.78rem;
    font-family: monospace;
    color: var(--global-text-color-light, #6c757d);
  }

  .proj-date {
    font-size: 0.82rem;
    font-weight: 600;
    color: var(--global-text-color-light, #6c757d);
    white-space: nowrap;
    padding-top: 0.1rem;
  }

  .proj-bullets {
    margin: 0;
    padding-left: 1.2rem;
    font-size: 0.91rem;
    color: var(--global-text-color, #444);
    line-height: 1.7;
  }

  .proj-bullets li {
    margin-bottom: 0.2rem;
  }

  .proj-bullets a {
    color: #4a90d9;
    text-decoration: none;
    font-weight: 600;
  }

  .proj-bullets a:hover {
    text-decoration: underline;
  }

  @media (max-width: 600px) {
    .proj-header {
      flex-direction: column;
    }
  }
</style>
