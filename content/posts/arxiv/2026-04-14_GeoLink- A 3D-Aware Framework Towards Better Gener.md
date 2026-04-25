---
title: "GeoLink: A 3D-Aware Framework Towards Better Generalization in Cross-View Geo-Localization"
date: 2026-04-14
categories: ["cs.CV, cs.MM"]
tags: ["arxiv", "arxiv"]
draft: false
---

## 论文信息

- **标题**: GeoLink: A 3D-Aware Framework Towards Better Generalization in Cross-View Geo-Localization
- **作者**: Hongyang Zhang, Yinhao Liu, Haitao Zhang, Zhongyi Wen, Zhenyu Kuang, Shuxian Liang, Xiansheng Hua
- **发表日期**: 2026-04-14T18:06:41Z
- **更新**: N/A
- **arXiv ID**: [2604.13183v2](2604.13183v2)
- **PDF 链接**: [https://arxiv.org/pdf/2604.13183v2](https://arxiv.org/pdf/2604.13183v2)

## 分类

cs.CV, cs.MM

## 摘要

Generalizable cross-view geo-localization aims to match the same location across views in unseen regions and conditions without GPS supervision. Its core difficulty lies in severe semantic inconsistency caused by viewpoint variation and poor generalization under domain shift. Existing methods mainly rely on 2D correspondence, but they are easily distracted by redundant shared information across views, leading to less transferable representations. To address this, we propose GeoLink, a 3D-aware semantic-consistent framework for Generalizable cross-view geo-localization. Specifically, we offline reconstruct scene point clouds from multi-view drone images using VGGT, providing stable structural priors. Based on these 3D anchors, we improve 2D representation learning in two complementary ways. A Geometric-aware Semantic Refinement module mitigates potentially redundant and view-biased dependencies in 2D features under 3D guidance. In addition, a Unified View Relation Distillation module transfers 3D structural relations to 2D features, improving cross-view alignment while preserving a 2D-only inference pipeline. Extensive experiments on multiple benchmarks show that GeoLink consistently outperforms state-of-the-art methods and achieves superior generalization across unseen domains and diverse weather environments.

## 相关推荐

- 更多论文：https://arxiv.org/
- arXiv API: http://export.arxiv.org/api/
