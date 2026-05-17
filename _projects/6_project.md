---
layout: page
title: Pancreas Multi-Task Learning
description: Joint pancreas segmentation and subtype classification on abdominal CT using modified nnUNetV2
img: assets/img/proj_pancreas.jpg
importance: 6
category: past
---

A deep learning pipeline for joint pancreas segmentation and subtype classification on abdominal CT using a modified nnUNetV2 backbone.

**Key contributions:**
- Integrated a custom classification head with multi-scale feature adapters and fusion modules to process encoder outputs alongside segmentation decoding.
- Achieved average Dice of **0.90** (pancreas) and **0.60** (lesion) and macro F1 of **0.81** on the test set.
- Reduced inference time by **24%** via an optimized prediction loop.

**Technologies:** Python · PyTorch · nnUNetV2 · Git

**Period:** Apr. 2025 – Jun. 2025
