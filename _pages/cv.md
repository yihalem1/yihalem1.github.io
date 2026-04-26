---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p>
  📄 <a href="{{ base_path }}/files/Yihalem_Yimolal_CV.pdf"><strong>Download CV (PDF)</strong></a>
  &nbsp;|&nbsp;
  <a href="{{ site.author.googlescholar }}">Google Scholar</a>
  &nbsp;|&nbsp;
  <a href="https://github.com/{{ site.author.github }}">GitHub</a>
  &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a>
</p>

Research summary
======
Master's researcher at UNIST working on **3D human avatar reconstruction**, **3D Gaussian splatting**, and **vision–language reasoning** for hand understanding. Recent first-author work (ECCV 2026, under review) proposes a *visibility-aware* 3D Gaussian avatar framework that reconstructs animatable avatars from monocular video across full-body, upper-body, and head-only settings within a single pipeline — integrating occlusion-robust SMPL-X tracking, part-specific residual refinement, and diffusion-based texture completion. Additional contributions span hand pose benchmarking (CVPR 2026), hand–object mesh generation (CVPR Findings 2026), real-time two-hand manipulation (AAAI 2025), and generative replay for continual detection (CVPR 2024 Highlight).

Research interests
======
3D Gaussian Splatting · 3D Human Avatar Reconstruction & Animation · Visibility-Aware Optimization · Diffusion Models · SMPL-X / FLAME Parametric Body Models · Hand Pose Estimation & 3D Hand–Object Interaction · Vision–Language Models.

Education
======
* **M.S. in Computer Science and Engineering**, Ulsan National Institute of Science & Technology (UNIST), Sep 2024 – Aug 2026 (expected). GPA: **4.1 / 4.3** (98 / 100).
* **B.S. in Computer Science and Engineering**, Ulsan National Institute of Science & Technology (UNIST), Sep 2020 – Jun 2024. ***Cum Laude***.

Selected research highlights
======
* **First author, ECCV 2026** (under review): Visibility-aware 3D Gaussian avatar framework — state-of-the-art across full-body, upper-body, and head-only settings, with **~3% PSNR gain** and up to **50% memory reduction**.
* **Co-author, CVPR 2026**: HandVQA — 1.6M-scale benchmark for diagnosing spatial reasoning failures in vision–language models via hand pose question answering.
* **Co-author, CVPR 2026 Findings**: THOM — text-conditioned generative framework for physically plausible hand–object mesh interactions.
* **Co-author, AAAI 2025**: QORT-Former — real-time 3D two-hand manipulation modeling (53.5 FPS; +27.2% H2O; +10.4% FPHA).
* **Co-author, CVPR 2024 *Highlight* (top 2.8%)**: SDDGR — Stable Diffusion-based generative replay for class-incremental object detection.

Publications
======
The full list is available on the [Publications page](/publications/).

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research experience
======

**Vision & Learning Lab, UNIST** — *Graduate Research Assistant (previously Research Assistant)*
*Jan 2023 – Present · Ulsan, South Korea · Advisors: [Prof. Seungryul Baek](https://sites.google.com/site/bsrvision00), [Prof. Binod Bhattarai](https://sites.google.com/view/bbinod/home).*

* Led development of a first-author visibility-aware 3D Gaussian avatar reconstruction framework (ECCV 2026, under review).
* Contributed to HandVQA (CVPR 2026) and THOM (CVPR Findings 2026) on 3D hand understanding and hand–object interaction generation.
* Co-authored SDDGR (CVPR 2024 Highlight), a Stable-Diffusion-based generative replay method for class-incremental object detection, and QORT-Former (AAAI 2025), a real-time transformer for 3D two-hand manipulation.
* Implemented transformer-based approaches for high-fidelity 3D facial texture refinement and designed Trimesh-based pipelines for hand–object interaction visualization.
* Optimized MobileNetV3-Small for 3D face reconstruction, achieving 50% faster inference and 25% accuracy improvement.

**Machine Learning, Vision & Language Lab, UNIST** — *Research Assistant*
*Sep 2022 – Dec 2022 · Mentor: [Prof. Taehwan Kim](https://sites.google.com/view/taehwankim).*

* Led a CV research initiative on astronomical image clarity enhancement using GANs, improving image detail by 60%.
* Evaluated deep learning models using accuracy, sensitivity, specificity, and precision metrics.

**Bio-Optics & Computational Imaging Lab, UNIST** — *Research Assistant*
*Sep 2021 – Dec 2021 · Mentor: [Prof. Jung-Hoon Park](https://scholar.google.com/citations?user=lDIQkOwAAAAJ&hl=en).*

* Conducted research on non-line-of-sight imaging using Ghost Imaging techniques.
* Applied machine learning algorithms to extract scattering resistance modes, achieving 95% accuracy.

Selected research projects
======
* **Visibility-Aware 3D Gaussian Human Avatar Reconstruction** — Vision & Learning Lab, UNIST (Jan 2025 – Present). Unified Gaussian-splatting pipeline for animatable avatars across full-body, upper-body, and head-only inputs; visibility-aware optimization (–50% memory, +34% FPS); occlusion-robust SMPL-X co-registration; diffusion-based 360° view synthesis. [Code](https://github.com/yihalem1).
* **Accelerating Inference Speed for 3D Face Reconstruction** — Vision & Learning Lab, UNIST (Aug 2023 – Aug 2024). Sparsity-aware quantization, ViT backbone optimization, and CNN student networks via knowledge distillation. [Code](https://github.com/yihalem1).
* **Mesh Reconstruction & Visualization on the ARCTIC Dataset** — Vision & Learning Lab, UNIST (Feb 2023 – Jul 2023). FastInst implementation and rendering pipelines for hand–object manipulation evaluation. [Code](https://github.com/yihalem1).

Technical skills
======
* **Core:** PyTorch, CUDA, Distributed / Accelerated Training, Linux, Git, LaTeX.
* **Generative & Multimodal Models:** Diffusion Models, HuggingFace Transformers.
* **3D Vision & Rendering:** 3D Gaussian Splatting, NeRF, SMPL-X / FLAME, differentiable rendering, multi-view geometry, pose estimation, human/hand modeling.
* **Data & Tooling:** NumPy, Pandas, OpenCV, Trimesh, experiment scripting and evaluation pipelines.

Teaching experience
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors & awards
======
* **Graduate School Scholarship (Korean Government)** — full tuition + stipend for M.S.
* **UNIST Dream Scholarship (UNIST)** — full tuition + stipend for B.S.

References
======
* **Prof. Seungryul Baek** — Supervisor (M.S.). Associate Professor, Artificial Intelligence Graduate School (AIGS) and Department of Computer Science and Engineering, UNIST. [Website](https://sites.google.com/site/bsrvision00) · srbaek@unist.ac.kr
* **Prof. Binod Bhattarai** — Co-supervisor (M.S.). Lecturer, University of Aberdeen, UK; Honorary Lecturer, University College London, UK. [Website](https://sites.google.com/view/bbinod/home) · b.bhattarai@ucl.ac.uk
