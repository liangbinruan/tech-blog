---
title: "Out of Context: Reliability in Multimodal Anomaly Detection Requires Contextual Inference"
date: 2026-04-14
categories: ["cs.LG, cs.AI"]
tags: ["arxiv", "arxiv"]
draft: false
---

## 论文信息

- **标题**: Out of Context: Reliability in Multimodal Anomaly Detection Requires Contextual Inference
- **作者**: Kevin Wilkinghoff, Neelu Madan, Juan Miguel Valverde, Kamal Nasrollahi, Radu Tudor Ionescu, Rafal Wisniewski, Thomas B. Moeslund, Wenwu Wang, Zheng-Hua Tan
- **发表日期**: 2026-04-14T19:32:55Z
- **更新**: N/A
- **arXiv ID**: [2604.13252v1](2604.13252v1)
- **PDF 链接**: [https://arxiv.org/pdf/2604.13252v1](https://arxiv.org/pdf/2604.13252v1)

## 分类

cs.LG, cs.AI

## 摘要

Anomaly detection aims to identify observations that deviate from expected behavior. Because anomalous events are inherently sparse, most frameworks are trained exclusively on normal data to learn a single reference model of normality. This implicitly assumes that normal behavior can be captured by a single, unconditional reference distribution. In practice, however, anomalies are often context-dependent: A specific observation may be normal under one operating condition, yet anomalous under another. As machine learning systems are deployed in dynamic and heterogeneous environments, these fixed-context assumptions introduce structural ambiguity, i.e., the inability to distinguish contextual variation from genuine abnormality under marginal modeling, leading to unstable performance and unreliable anomaly assessments. While modern sensing systems frequently collect multimodal data capturing complementary aspects of both system behavior and operating conditions, existing methods treat all data streams equally, without distinguishing contextual information from anomaly-relevant signals. As a result, abnormality is often evaluated without explicitly conditioning on operating conditions. We argue that multimodal anomaly detection should be reframed as a cross-modal contextual inference problem, in which modalities play asymmetric roles, separating context from observation, to define abnormality conditionally rather than relative to a single global reference. This perspective has implications for model design, evaluation protocols, and benchmark construction, and outline open research challenges toward robust, context-aware multimodal anomaly detection.

## 相关推荐

- 更多论文：https://arxiv.org/
- arXiv API: http://export.arxiv.org/api/
