---
title: "Evolution-Inspired Sample Competition for Deep Neural Network Optimization"
date: 2026-04-14
categories: ["cs.CV"]
tags: ["arxiv", "arxiv"]
draft: false
---

## 论文信息

- **标题**: Evolution-Inspired Sample Competition for Deep Neural Network Optimization
- **作者**: Ying Zheng, Yiyi Zhang, Yi Wang, Lap-Pui Chau
- **发表日期**: 2026-04-14T10:48:01Z
- **更新**: N/A
- **arXiv ID**: [2604.12568v1](2604.12568v1)
- **PDF 链接**: [https://arxiv.org/pdf/2604.12568v1](https://arxiv.org/pdf/2604.12568v1)

## 分类

cs.CV

## 摘要

Conventional deep network training generally optimizes all samples under a largely uniform learning paradigm, without explicitly modeling the heterogeneous competition among them. Such an oversimplified treatment can lead to several well-known issues, including bias under class imbalance, insufficient learning of hard samples, and the erroneous reinforcement of noisy samples. In this work, we present \textit{Natural Selection} (NS), a novel evolution-inspired optimization method that explicitly incorporates competitive interactions into deep network training. Unlike conventional sample reweighting strategies that rely mainly on predefined heuristics or static criteria, NS estimates the competitive status of each sample in a group-wise context and uses it to adaptively regulate its training contribution. Specifically, NS first assembles multiple samples into a composite image and rescales it to the original input size for model inference. Based on the resulting predictions, a natural selection score is computed for each sample to characterize its relative competitive variation within the constructed group. These scores are then used to dynamically reweight the sample-wise loss, thereby introducing an explicit competition-driven mechanism into the optimization process. In this way, NS provides a simple yet effective means of moving beyond uniform sample treatment and enables more adaptive and balanced model optimization. Extensive experiments on 12 public datasets across four image classification tasks demonstrate the effectiveness of the proposed method. Moreover, NS is compatible with diverse network architectures and does not depend on task-specific assumptions, indicating its strong generality and practical potential. The code will be made publicly available.

## 相关推荐

- 更多论文：https://arxiv.org/
- arXiv API: http://export.arxiv.org/api/
