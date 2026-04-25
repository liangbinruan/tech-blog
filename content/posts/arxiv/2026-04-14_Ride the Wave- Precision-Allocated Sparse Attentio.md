---
title: "Ride the Wave: Precision-Allocated Sparse Attention for Smooth Video Generation"
date: 2026-04-14
categories: ["cs.CV, cs.AI"]
tags: ["arxiv", "arxiv"]
draft: false
---

## 论文信息

- **标题**: Ride the Wave: Precision-Allocated Sparse Attention for Smooth Video Generation
- **作者**: Wentai Zhang, Ronghui Xi, Shiyao Peng, Jiayu Huang, Haoran Luo, Zichen Tang, Haihong E
- **发表日期**: 2026-04-14T02:51:52Z
- **更新**: N/A
- **arXiv ID**: [2604.12219v1](2604.12219v1)
- **PDF 链接**: [https://arxiv.org/pdf/2604.12219v1](https://arxiv.org/pdf/2604.12219v1)

## 分类

cs.CV, cs.AI

## 摘要

Video Diffusion Transformers have revolutionized high-fidelity video generation but suffer from the massive computational burden of self-attention. While sparse attention provides a promising acceleration solution, existing methods frequently provoke severe visual flickering caused by static sparsity patterns and deterministic block routing. To resolve these limitations, we propose Precision-Allocated Sparse Attention (PASA), a training-free framework designed for highly efficient and temporally smooth video generation. First, we implement a curvature-aware dynamic budgeting mechanism. By profiling the generation trajectory acceleration across timesteps, we elastically allocate the exact-computation budget to secure high-precision processing strictly during critical semantic transitions. Second, we replace global homogenizing estimations with hardware-aligned grouped approximations, successfully capturing fine-grained local variations while maintaining peak compute throughput. Finally, we incorporate a stochastic selection bias into the attention routing mechanism. This probabilistic approach softens rigid selection boundaries and eliminates selection oscillation, effectively eradicating the localized computational starvation that drives temporal flickering. Extensive evaluations on leading video diffusion models demonstrate that PASA achieves substantial inference acceleration while consistently producing remarkably fluid and structurally stable video sequences.

## 相关推荐

- 更多论文：https://arxiv.org/
- arXiv API: http://export.arxiv.org/api/
