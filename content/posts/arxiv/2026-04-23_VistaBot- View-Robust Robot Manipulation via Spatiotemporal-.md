---
title: "VistaBot: View-Robust Robot Manipulation via Spatiotemporal-Aware View Synthesis"
date: 2026-04-23
categories: ["arxiv", "cs.RO"]
tags: ["arxiv", "AI", "research"]
draft: false
---

## 论文信息

- **标题**: VistaBot: View-Robust Robot Manipulation via Spatiotemporal-Aware View Synthesis
- **作者**: Songen Gu, Yuhang Zheng, Weize Li, Yupeng Zheng, Yating Feng, Xiang Li, Yilun Chen, Pengfei Li, Wenchao Ding
- **发表日期**: 2026-04-23
- **arXiv ID**: [2604.21914v1](2604.21914v1)
- **PDF 链接**: [https://arxiv.org/pdf/2604.21914v1](https://arxiv.org/pdf/2604.21914v1)

## 分类

cs.RO

## 摘要

Recently, end-to-end robotic manipulation models have gained significant attention for their generalizability and scalability. However, they often suffer from limited robustness to camera viewpoint changes when training with a fixed camera. In this paper, we propose VistaBot, a novel framework that integrates feed-forward geometric models with video diffusion models to achieve view-robust closed-loop manipulation without requiring camera calibration at test time. Our approach consists of three key components: 4D geometry estimation, view synthesis latent extraction, and latent action learning. VistaBot is integrated into both action-chunking (ACT) and diffusion-based ($π_0$) policies and evaluated across simulation and real-world tasks. We further introduce the View Generalization Score (VGS) as a new metric for comprehensive evaluation of cross-view generalization. Results show that VistaBot improves VGS by 2.79$\times$ and 2.63$\times$ over ACT and $π_0$, respectively, while also achieving high-quality novel view synthesis. Our contributions include a geometry-aware synthesis model, a latent action planner, a new benchmark metric, and extensive validation across diverse environments. The code and models will be made publicly available.

---

*本文来源于 arXiv 论文追踪系统，通过 Hermes Agent 自动化发布*
