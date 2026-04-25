---
title: "SubFlow: Sub-mode Conditioned Flow Matching for Diverse One-Step Generation"
date: 2026-04-14
categories: ["cs.LG, cs.CV"]
tags: ["arxiv", "arxiv"]
draft: false
---

## 论文信息

- **标题**: SubFlow: Sub-mode Conditioned Flow Matching for Diverse One-Step Generation
- **作者**: Yexiong Lin, Jia Shi, Shanshan Ye, Wanyu Wang, Yu Yao, Tongliang Liu
- **发表日期**: 2026-04-14T04:36:02Z
- **更新**: N/A
- **arXiv ID**: [2604.12273v1](2604.12273v1)
- **PDF 链接**: [https://arxiv.org/pdf/2604.12273v1](https://arxiv.org/pdf/2604.12273v1)

## 分类

cs.LG, cs.CV

## 摘要

Flow matching has emerged as a powerful generative framework, with recent few-step methods achieving remarkable inference acceleration. However, we identify a critical yet overlooked limitation: these models suffer from severe diversity degradation, concentrating samples on dominant modes while neglecting rare but valid variations of the target distribution. We trace this degradation to averaging distortion: when trained with MSE objectives, class-conditional flows learn a frequency-weighted mean over intra-class sub-modes, causing the model to over-represent high-density modes while systematically neglecting low-density ones. To address this, we propose SubFlow, Sub-mode Conditioned Flow Matching, which eliminates averaging distortion by decomposing each class into fine-grained sub-modes via semantic clustering and conditioning the flow on sub-mode indices. Each conditioned sub-distribution is approximately unimodal, so the learned flow accurately targets individual modes with no averaging distortion, restoring full mode coverage in a single inference step. Crucially, SubFlow is entirely plug-and-play: it integrates seamlessly into existing one-step models such as MeanFlow and Shortcut Models without any architectural modifications. Extensive experiments on ImageNet-256 demonstrate that SubFlow yields substantial gains in generation diversity (Recall) while maintaining competitive image quality (FID), confirming its broad applicability across different one-step generation frameworks. Project page: https://yexionglin.github.io/subflow.

## 相关推荐

- 更多论文：https://arxiv.org/
- arXiv API: http://export.arxiv.org/api/
