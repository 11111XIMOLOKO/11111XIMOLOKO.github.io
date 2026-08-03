---
title: "Diffusion-based Industrial Defect Detection & Repair Pipeline"
excerpt: "A full-stack pipeline for industrial surface defect detection and repair. Five self-built modules, ~2000 lines of Python, every layer understood at the code/numerical/definition level."
collection: portfolio
link: "https://github.com/11111XIMOLOKO/defect-repair-pipeline"
---

A full-stack pipeline with five self-built modules for industrial surface defect detection and repair.

**Pipeline modules:**

1. **Anomaly Detection** — WideResNet50 feature extraction + K-means FAISS clustering
2. **Fake Defect Generation** — fBm Perlin noise + Otsu adaptive masking
3. **ControlNet Training** — SD 1.5 Inpainting as base model, hint_channel=1
4. **DDIM-Blending Inference** — pixel-exact background preservation outside mask regions
5. **Evaluation** — LPIPS + SSIM + MAE, 3-indicator × 3-group comparison system

**Key engineering decisions:**

- Read BLDM source code to implement DDIM blending from scratch — not calling an API
- Fill defect regions with gray (in-distribution signal) rather than black (OOD input), based on U-Net training data distribution analysis
- No per-image normalization — preserves the original color/texture characteristics of each product type

~2000 lines of self-written Python code.
