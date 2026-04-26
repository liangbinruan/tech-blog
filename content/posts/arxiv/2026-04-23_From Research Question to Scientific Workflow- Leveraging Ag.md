---
title: "From Research Question to Scientific Workflow: Leveraging Agentic AI for Science Automation"
date: 2026-04-23
categories: ["arxiv", "cs.AI"]
tags: ["arxiv", "AI", "research"]
draft: false
---

## 论文信息

- **标题**: From Research Question to Scientific Workflow: Leveraging Agentic AI for Science Automation
- **作者**: Bartosz Balis, Michal Orzechowski, Piotr Kica, Michal Dygas, Michal Kuszewski
- **发表日期**: 2026-04-23
- **arXiv ID**: [2604.21910v1](2604.21910v1)
- **PDF 链接**: [https://arxiv.org/pdf/2604.21910v1](https://arxiv.org/pdf/2604.21910v1)

## 分类

cs.AI

## 摘要

Scientific workflow systems automate execution -- scheduling, fault tolerance, resource management -- but not the semantic translation that precedes it. Scientists still manually convert research questions into workflow specifications, a task requiring both domain knowledge and infrastructure expertise. We propose an agentic architecture that closes this gap through three layers: an LLM interprets natural language into structured intents (semantic layer); validated generators produce reproducible workflow DAGs (deterministic layer); and domain experts author ``Skills'': markdown documents encoding vocabulary mappings, parameter constraints, and optimization strategies (knowledge layer). This decomposition confines LLM non-determinism to intent extraction: identical intents always yield identical workflows. We implement and evaluate the architecture on the 1000 Genomes population genetics workflow and Hyperflow WMS running on Kubernetes. In an ablation study on 150 queries, Skills raise full-match intent accuracy from 44% to 83%; skill-driven deferred workflow generation reduces data transfer by 92\%; and the end-to-end pipeline completes queries on Kubernetes with LLM overhead below 15 seconds and cost under $0.001 per query.

---

*本文来源于 arXiv 论文追踪系统，通过 Hermes Agent 自动化发布*
