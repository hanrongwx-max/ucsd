# UC San Diego 实验室安全资料库 / Lab Safety Knowledge Base

本目录汇总了 UC San Diego EH&S 网站（https://blink.ucsd.edu/safety/ehs/index.html 及其链接的科研与实验室安全页面）中与实验室相关的资料。资料包括英文原文整理稿和中文译本，并在此基础上编写了分析报告、培训课件、练习题和教学视频剧本。

This folder collects lab-related material from the UC San Diego EH&S site, with English page notes, Chinese translations, an analysis, and training materials built on top of them.

## 目录结构

```
lab-safety/
├── en/                      英文页面整理稿（49 篇）
├── zh/                      中文译本（与 en/ 一一对应）
│   ├── 00-overview              总览、应急指南、报告安全隐患
│   ├── 01-biosafety             生物安全、BUA、血源性病原体、BSC
│   ├── 02-chemical              化学卫生计划、储存、相容性、HCP
│   ├── 03-controlled-substances 管制物质
│   ├── 04-hazardous-waste       危险废物、下水道、标签、锐器
│   ├── 05-laboratory-safety-manual 实验室安全手册、未成年人、生殖危害、洗眼器
│   ├── 06-lab-operations        溢洒、通风柜、PPE、气瓶、消防、离心机
│   ├── 07-occupational-health   职业健康、工伤报告、纳米材料、动物设施
│   ├── 08-training-policy       培训、UC 政策
│   └── 09-radiation             辐射安全
├── analysis/
│   ├── safety-analysis-en.md    整理汇总与分析（英文）
│   └── safety-analysis-zh.md    整理汇总与分析（中文）
└── training/
    ├── courseware/              7 个模块的培训课件（Marp 幻灯片，约 6 学时）
    ├── question-bank/           92 道练习题（含答案、解析、出处）
    └── video/                   6 集教学视频剧本 + 制作工作流
```

## 建议使用顺序

1. 先读 [analysis/safety-analysis-zh.md](analysis/safety-analysis-zh.md)，了解体系和关键数字。
2. 教学：[课件](training/courseware/README.md) → [视频](training/video/README.md) → [练习题](training/question-bank/README.md)。
3. 核对细节：按各文件中的"出处"链接查阅 `zh/` 或 `en/` 中的原始页面整理稿。

## 关于资料来源的说明

- **整理稿，不是逐字副本。** `en/` 中的页面是对原网页内容的结构化整理，保留了原有的标题层级、规定、数值、联系方式和文件链接，但不是逐字复制。每篇的 frontmatter 中都记录了原始网址（`source`）、页面最后更新日期（`page_last_updated`）和抓取日期（`retrieved`，2026-10-23）。
- **PDF 未下载。** 抓取时云端环境的网络策略屏蔽了 blink.ucsd.edu，原网页中链接的 PDF（如化学卫生计划全文、各类表格）无法下载。这些 PDF 的链接都列在对应页面的"文件"部分。如需归档 PDF，可在环境的允许域名中加入 `blink.ucsd.edu` 后补充下载。
- **以官方页面为准。** 规定可能随时更新。使用前请以 EH&S 官方页面为准，尤其是电话、限值和时限。
- **其他高校使用**：课件、题库和视频中的电话、委员会和系统名称都是 UC San Diego 的。请替换为本校的规定，见 [视频制作工作流](training/video/production-workflow.md) 第 0 步。
