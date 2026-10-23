# 高校实验室安全培训课件（基于 UC San Diego EH&S 资料）

本课件依据 `lab-safety/zh/` 与 `lab-safety/en/` 中整理的 UC San Diego EH&S 官方页面编写，面向高校本科生、研究生、新入职科研人员和实验室安全员。

> 说明：课件中的电话、时限、数值均来自 UC San Diego，用于教学示例。在其他学校使用时，请把联系人、电话和校内流程替换为本校信息，并保留"原理与规则"部分。

## 课程目标

学完本课程，学员应能：
1. 说出"授权 → 危害控制计划（HCP）→ 培训 → 确认 → 开工"的审批链，并知道自己在其中的责任。
2. 正确选择和穿戴实验室 PPE，说出最低着装要求。
3. 按相容组储存化学品，正确标识容器，理解 SDS 和 GHS。
4. 说出 BSL-1 至 BSL-3 的主要区别，正确使用生物安全柜。
5. 正确分类、标识、储存和申请收集危险废物，判断哪些东西可以倒入下水道。
6. 在溢洒、暴露、针刺伤、火灾、地震等紧急情况下按正确步骤处置并报告。
7. 安全使用离心机、压缩气瓶、通风柜、灭火器、洗眼器和紧急喷淋。

## 课程结构（建议 7 个模块，共约 6 学时）

| 模块 | 文件 | 时长 | 适用对象 |
|---|---|---|---|
| M1 实验室安全总论与责任体系 | [m1-overview.md](m1-overview.md) | 45 分钟 | 所有人（必修） |
| M2 化学品安全 | [m2-chemical.md](m2-chemical.md) | 60 分钟 | 所有人（必修） |
| M3 生物安全 | [m3-biosafety.md](m3-biosafety.md) | 60 分钟 | 生物/医学类（必修），其他选修 |
| M4 危险废物管理 | [m4-waste.md](m4-waste.md) | 45 分钟 | 所有人（必修） |
| M5 应急响应与事故报告 | [m5-emergency.md](m5-emergency.md) | 60 分钟 | 所有人（必修） |
| M6 设备与物理安全 | [m6-equipment.md](m6-equipment.md) | 45 分钟 | 所有人（必修） |
| M7 专题：纳米、生殖危害、未成年人、管制物质、辐射 | [m7-special-topics.md](m7-special-topics.md) | 45 分钟 | 按岗位选修 |

## 课件格式

- 每个模块是一个 [Marp](https://marp.app/) Markdown 幻灯片文件：用 `---` 分隔页面，`<!-- 讲者备注 -->` 为讲稿。
- 生成 PPT/PDF：安装 Marp CLI 后运行 `npx @marp-team/marp-cli m1-overview.md --pptx`（或 `--pdf`）。
- 也可以直接在 VS Code 的 Marp 插件中预览。

## 配套资源

- 题库：[../question-bank/](../question-bank/)
- 视频剧本与制作工作流：[../video/](../video/)
- 汇总分析：[../../analysis/safety-analysis-zh.md](../../analysis/safety-analysis-zh.md)

## 考核建议

- 每个模块后 5–10 道随堂测验（从题库抽取）。
- 结业考试：50 题，80 分及格；不及格者重修对应模块。
- 实操考核：PPE 穿脱、溢洒包使用、灭火器 PASS、洗眼器使用、生物安全柜操作。
- 培训记录保存 ≥ 3 年（"没有记录就等于没做过"）。
