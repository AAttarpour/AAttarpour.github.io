---
layout: about
title: About
permalink: /
subtitle: "AI Scientist | Foundation Models · Agentic AI · Large Biomedical Data"

profile:
  align: right
  image: prof_pic.png
  image_circular: false

selected_papers: false
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I build **end-to-end AI-based pipelines**, **foundation models**, and **agentic AI systems** for large-scale biomedical data analysis, with the goal of translating cutting-edge ML research into real-world healthcare impact.

I am an AI Scientist at the [University Health Network (UHN)](https://www.uhn.ca/) and [Peter Munk Cardiac Centre AI Team](https://pmcc.ai/), Toronto, Canada. I completed my **Ph.D. in Medical Biophysics** at the [University of Toronto](https://www.utoronto.ca/) and [Sunnybrook Research Institute](https://sunnybrook.ca/research/), specializing in deep learning for 3D whole-brain analysis of tera-voxel light sheet microscopy data.

My work spans the full ML development lifecycle — from self-supervised pretraining of foundation models on millions of 3D biomedical image patches, to building **agentic reasoning pipelines** and **multimodal vision-language systems** for biomedical data analysis. I have experience across a diverse range of modalities including **light sheet microscopy**, **CryoET/CryoEM**, **histopathology (WSI)**, **echocardiography**, **MRI/CT**, and **ECG/biosignals**. I have co-authored [**10+ peer-reviewed publications**](https://scholar.google.com/citations?user=6m7xbK4AAAAJ) including two first-author papers in [*Nature Methods*](https://doi.org/10.1038/s41592-024-02583-1) (one published, one under review), filed **2 patents**, and presented at **10+ international conferences**.

I am particularly passionate about developing **robust, uncertainty-aware, and deployable AI** — systems that generalize reliably under distribution shift and real-world noisy conditions.

---

## Featured Work

<div class="feat-list">

  <!-- ACE -->
  <div class="feat-item">
    <div class="feat-img-wrap">
      <img src="/assets/img/proj_ace.png" alt="ACE pipeline visualization">
    </div>
    <div class="feat-content">
      <div class="feat-badges">
        <span class="feat-badge published">Nature Methods · Jan 2025</span>
        <span class="feat-badge first-author">First Author</span>
      </div>
      <h3 class="feat-title">
        <a href="https://doi.org/10.1038/s41592-024-02583-1" target="_blank">
          ACE — AI-based Cartography of Ensembles
        </a>
      </h3>
      <p class="feat-desc">
        End-to-end 3D deep learning pipeline for brain-wide mapping of local neuronal ensembles in tera-voxel (~1TB/sample) light sheet microscopy data. Integrates a CNN/ViT ensemble with Monte Carlo dropout for probabilistic uncertainty estimation and cluster-wise permutation statistical analysis. Adopted internationally — used in a <a href="https://www.cell.com/cell/fulltext/S0092-8674(25)01365-0" target="_blank" style="color:inherit;font-weight:600;text-decoration:underline;">Cell (2025)</a> study.
      </p>
      <div class="feat-links">
        <a href="https://doi.org/10.1038/s41592-024-02583-1" target="_blank" class="feat-btn">Paper</a>
        <a href="https://miracl.readthedocs.io/en/latest/tutorials/workflows/ace_flow/ace_flow.html" target="_blank" class="feat-btn">Docs</a>
      </div>
    </div>
  </div>

  <!-- MAPL3 -->
  <div class="feat-item feat-alt">
    <div class="feat-img-wrap">
      <img src="/assets/img/proj_mapl3.png" alt="MAPL3 axonal projection mapping">
    </div>
    <div class="feat-content">
      <div class="feat-badges">
        <span class="feat-badge review">Under Review · Nature Methods · 2025</span>
        <span class="feat-badge first-author">First Author</span>
      </div>
      <h3 class="feat-title">
        MAPL3 — Mapping Axonal Projection in Light Sheet Microscopy in 3D
      </h3>
      <p class="feat-desc">
        3D computational pipeline for brain-wide axonal projection mapping at single-fiber resolution. Combines a novel CNN+ViT architecture with self-supervised learning to quantitatively profile whole-brain connectomes using high-resolution light sheet microscopy.
      </p>
      <div class="feat-links">
        <a href="https://www.biorxiv.org/content/10.1101/2025.11.14.688340v1.abstract" target="_blank" class="feat-btn">Preprint</a>
        <a href="https://github.com/AAttarpour/microscopy-image-analysis" target="_blank" class="feat-btn">Code</a>
      </div>
    </div>
  </div>

  <!-- EchoJEPA -->
  <div class="feat-item">
    <div class="feat-img-wrap">
      <img src="/assets/img/proj_echojepa.png" alt="EchoJEPA echocardiography foundation model">
    </div>
    <div class="feat-content">
      <div class="feat-badges">
        <span class="feat-badge published">Foundation Model · Echocardiography</span>
      </div>
      <h3 class="feat-title">
        <a href="https://echojepa.com/" target="_blank">
          EchoJEPA: A Latent Predictive Foundation Model for Echocardiography
        </a>
      </h3>
      <p class="feat-desc">
        State-of-the-art foundation model for echocardiography pretrained on 18 million videos across 300K patients — the largest pretraining corpus for cardiac imaging to date. Achieves ~20% improvement in LVEF estimation and 78.6% view classification accuracy using only 1% of labeled data.
      </p>
      <div class="feat-links">
        <a href="https://echojepa.com/" target="_blank" class="feat-btn">Website</a>
      </div>
    </div>
  </div>

</div>

<style>
  .feat-list {
    margin-top: 1.5rem;
  }

  .feat-item {
    display: flex;
    flex-direction: row;
    gap: 2rem;
    align-items: center;
    padding: 2rem 0;
    border-bottom: 1px solid var(--global-divider-color, #e8e8e8);
  }

  .feat-item:last-child {
    border-bottom: none;
  }

  .feat-item.feat-alt {
    flex-direction: row-reverse;
  }

  .feat-img-wrap {
    flex: 0 0 280px;
    max-width: 280px;
  }

  .feat-img-wrap img {
    width: 100%;
    border-radius: 8px;
    object-fit: cover;
    box-shadow: 0 2px 12px rgba(0, 0, 0, 0.1);
  }

  .feat-content {
    flex: 1;
  }

  .feat-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-bottom: 0.6rem;
  }

  .feat-badge {
    display: inline-block;
    padding: 0.2rem 0.6rem;
    border-radius: 4px;
    font-size: 0.72rem;
    font-weight: 600;
    letter-spacing: 0.02em;
  }

  .feat-badge.published {
    background-color: #eaf4ea;
    color: #2a7a2a;
    border: 1px solid #b5ddb5;
  }

  .feat-badge.review {
    background-color: #fff8e1;
    color: #a07000;
    border: 1px solid #ffe082;
  }

  .feat-badge.first-author {
    background-color: #e8f0fd;
    color: #1a4fad;
    border: 1px solid #b3c8f5;
  }

  .feat-title {
    font-size: 1.05rem;
    font-weight: 700;
    margin: 0.4rem 0 0.6rem;
    line-height: 1.4;
  }

  .feat-title a {
    color: var(--global-text-color, #212529);
    text-decoration: none;
  }

  .feat-title a:hover {
    color: #4a90d9;
  }

  .feat-desc {
    font-size: 0.89rem;
    color: var(--global-text-color, #444);
    line-height: 1.65;
    margin-bottom: 0.8rem;
  }

  .feat-links {
    display: flex;
    gap: 0.5rem;
    flex-wrap: wrap;
  }

  .feat-btn {
    display: inline-block;
    padding: 0.3rem 0.85rem;
    border-radius: 5px;
    font-size: 0.8rem;
    font-weight: 600;
    background-color: var(--global-bg-color, #fff);
    color: #4a90d9;
    border: 1.5px solid #4a90d9;
    text-decoration: none;
    transition: all 0.18s ease;
  }

  .feat-btn:hover {
    background-color: #4a90d9;
    color: #fff;
    text-decoration: none;
  }

  @media (max-width: 680px) {
    .feat-item,
    .feat-item.feat-alt {
      flex-direction: column;
    }

    .feat-img-wrap {
      flex: unset;
      max-width: 100%;
    }
  }
</style>
