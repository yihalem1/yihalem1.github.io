---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

My research focuses on **3D human avatar reconstruction**, **3D Gaussian splatting**, and **vision–language reasoning** for human and hand understanding. I am especially interested in approaches that remain robust under **partial observations** — for example, monocular video where the body is only partially visible — by combining geometric priors (SMPL-X / FLAME), differentiable rendering, and diffusion-based generative completion.

Research interests
======
* **3D Gaussian Splatting & Neural Rendering** — visibility-aware optimization, real-time rendering, memory-efficient avatars.
* **3D Human Avatar Reconstruction & Animation** — animatable avatars from monocular video across full-body, upper-body, and head-only settings.
* **Diffusion Models for 3D Generation** — diffusion-based texture completion and view synthesis for unobserved regions.
* **Parametric Body Models** — occlusion-robust SMPL-X tracking and FLAME-based facial initialization.
* **Hand Pose Estimation & 3D Hand–Object Interaction** — real-time two-hand manipulation, text-conditioned hand–object mesh generation.
* **Vision–Language Models for Spatial Reasoning** — large-scale benchmarks for diagnosing fine-grained spatial reasoning failures.
* **Continual Learning** — generative replay for class-incremental object detection.

Selected research projects
======

Visibility-Aware 3D Gaussian Human Avatar Reconstruction
------
*Vision & Learning Lab, UNIST · Jan 2025 – Present*
*First-author work submitted to ECCV 2026 (under review).*

* Designed a unified 3D Gaussian splatting pipeline for animatable avatar reconstruction from monocular video across **full-body, upper-body, and head-only** inputs.
* Developed **visibility-aware optimization** using Otsu's method to prune unobserved Gaussians, **reducing memory by up to 50%** and improving rendering speed by **~34%**.
* Implemented **occlusion-robust SMPL-X co-registration** with FLAME-based facial initialization and **part-specific residual MLPs** for high-frequency face and hand refinement.
* Integrated **diffusion-based video generation** to synthesize auxiliary 360° views for texture completion of unobserved regions.
* Code: [GitHub](https://github.com/yihalem1)

Accelerating Inference Speed for 3D Face Reconstruction
------
*Vision & Learning Lab, UNIST · Aug 2023 – Aug 2024*

* Implemented **post-training sparsity-aware quantization** for a 3D face reconstruction model to reduce inference overhead.
* Adopted and optimized a **Vision Transformer** backbone for the face reconstruction task.
* Designed lightweight **student CNN networks via knowledge distillation** to compress model complexity while preserving accuracy.
* Optimized **MobileNetV3-Small** for 3D face reconstruction, achieving **50% faster inference** and **25% accuracy improvement**.
* Code: [GitHub](https://github.com/yihalem1)

Advanced Mesh Reconstruction & Visualization on the ARCTIC Dataset
------
*Vision & Learning Lab, UNIST · Feb 2023 – Jul 2023*

* Implemented the **FastInst** architecture on the ARCTIC dataset for efficient hand–object mesh visualization.
* Deployed rendering pipelines to enable precise model evaluation on hand–object manipulation sequences.
* Code: [GitHub](https://github.com/yihalem1)

Earlier research experience
======

Machine Learning, Vision & Language Lab, UNIST — *Research Assistant (Sep 2022 – Dec 2022)*
------
*Mentor: [Prof. Taehwan Kim](https://sites.google.com/view/taehwankim).*

* Led a computer vision research initiative on **astronomical image clarity enhancement using GANs**, improving image detail by 60%.
* Evaluated deep learning models using standard metrics including accuracy, sensitivity, specificity, and precision.

Bio-Optics & Computational Imaging Lab, UNIST — *Research Assistant (Sep 2021 – Dec 2021)*
------
*Mentor: [Prof. Jung-Hoon Park](https://scholar.google.com/citations?user=lDIQkOwAAAAJ&hl=en).*

* Conducted research on **non-line-of-sight imaging using Ghost Imaging** techniques.
* Applied machine learning algorithms to extract scattering resistance modes, achieving 95% accuracy.

Selected research highlights
======
* **First author**, *ECCV 2026* (under review): Visibility-aware 3D Gaussian avatar framework — state-of-the-art across full-body, upper-body, and head-only settings (~3% PSNR gain, up to 50% memory reduction).
* **Co-author**, *CVPR 2026*: HandVQA — 1.6M-scale benchmark for diagnosing spatial reasoning failures in vision–language models.
* **Co-author**, *CVPR 2026 Findings*: THOM — text-conditioned generative framework for physically plausible hand–object meshes.
* **Co-author**, *AAAI 2025*: QORT-Former — real-time 3D two-hand manipulation modeling (53.5 FPS; +27.2% H2O; +10.4% FPHA).
* **Co-author**, *CVPR 2024 Highlight (top 2.8%)*: SDDGR — Stable-Diffusion-based generative replay for class-incremental object detection.

A complete publication list is available on the [Publications page](/publications/).
