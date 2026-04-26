---
title: '首页'
---

## 欢迎来到技术观察学习者

这里记录对前沿技术的观察、思考与学习。

### 内容方向

- **arXiv 论文解读** — 追踪 AI/ML 前沿研究，深入解读核心思想
- **技术社区精选** — 从微信公众号等技术社区提取优质内容
- **系统架构实践** — 分享自动化系统、Agent 框架的设计与实现

### 最近文章

{{ range (where .Site.RegularPages "Section" "posts").First 5 }}
- [{{ .Title }}]({{ .RelPermalink }}) — {{ .Date.Format "2006-01-02" }}
{{ end }}
