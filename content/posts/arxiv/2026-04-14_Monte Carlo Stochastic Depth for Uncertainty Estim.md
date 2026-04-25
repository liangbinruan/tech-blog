---
title: "Monte Carlo Stochastic Depth for Uncertainty Estimation in Deep Learning"
date: 2026-04-14
categories: ["cs.LG, stat.ML"]
tags: ["arxiv", "arxiv"]
draft: false
---

## 论文信息

- **标题**: Monte Carlo Stochastic Depth for Uncertainty Estimation in Deep Learning
- **作者**: Adam T. Müller, Tobias Rögelein, Nicolaj C. Stache
- **发表日期**: 2026-04-14T13:33:40Z
- **更新**: N/A
- **arXiv ID**: [2604.12719v1](2604.12719v1)
- **PDF 链接**: [https://arxiv.org/pdf/2604.12719v1](https://arxiv.org/pdf/2604.12719v1)

## 分类

cs.LG, stat.ML

## 摘要

The deployment of deep neural networks in safety-critical systems necessitates reliable and efficient uncertainty quantification (UQ). A practical and widespread strategy for UQ is repurposing stochastic regularizers as scalable approximate Bayesian inference methods, such as Monte Carlo Dropout (MCD) and MC-DropBlock (MCDB). However, this paradigm remains under-explored for Stochastic Depth (SD), a regularizer integral to the residual-based backbones of most modern architectures. While prior work demonstrated its empirical promise for segmentation, a formal theoretical connection to Bayesian variational inference and a benchmark on complex, multi-task problems like object detection are missing. In this paper, we first provide theoretical insights connecting Monte Carlo Stochastic Depth (MCSD) to principled approximate variational inference. We then present the first comprehensive empirical benchmark of MCSD against MCD and MCDB on state-of-the-art detectors (YOLO, RT-DETR) using the COCO and COCO-O datasets. Our results position MCSD as a robust and computationally efficient method that achieves highly competitive predictive accuracy (mAP), notably yielding slight improvements in calibration (ECE) and uncertainty ranking (AUARC) compared to MCD. We thus establish MCSD as a theoretically-grounded and empirically-validated tool for efficient Bayesian approximation in modern deep learning.

## 相关推荐

- 更多论文：https://arxiv.org/
- arXiv API: http://export.arxiv.org/api/
