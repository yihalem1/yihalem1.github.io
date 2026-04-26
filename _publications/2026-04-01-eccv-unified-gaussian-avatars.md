---
title: "Unified 3D Gaussian Human Avatars Under Arbitrary Body Visibility"
collection: publications
category: conferences
permalink: /publication/2026-eccv-unified-gaussian-avatars
excerpt: 'Visibility-aware 3D Gaussian avatar framework that reconstructs animatable avatars from monocular video across full-body, upper-body, and head-only inputs within a single pipeline.'
date: 2026-04-01
venue: 'European Conference on Computer Vision (ECCV) — under review'
authors: '<u>Y. Y. Tiruneh</u>, S. Baek'
---

**Authors.** <u>Y. Y. Tiruneh</u>, S. Baek.

**Status.** Submitted to **ECCV 2026** (under review).

**Summary.**
- Proposed a *visibility-aware* optimization framework that restricts Gaussian splatting supervision to observed body regions, eliminating hallucinated geometry and texture drift under partial-view inputs.
- Unified pipeline supporting full-body, upper-body, and head-only avatars with occlusion-robust SMPL-X tracking, FLAME-based facial initialization, part-specific residual MLPs, and diffusion-based texture completion.
- Achieved state-of-the-art on **NeuMan**, **ZJU-MoCap**, **TalkShow**, and **INSTA**; reduced memory by **~50%** and improved FPS by **~34%** for head-only avatars; **~3% PSNR gain** overall.
