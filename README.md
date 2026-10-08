# 小说全稿修订方案 · Story Revision Plan

> 写完一部长篇之后，别急着改稿——先出一份**可执行的修订方案**：评什么、改哪、加什么、往哪加。
> 五步流程 + 标准模板。纯文档，零依赖。

## 这是什么

一句话：**修订方案 ≠ 改稿**。方案只写「改什么／怎么改／加什么／往哪加」，原稿一个字不动；修订版另建目录。

五条铁律：

1. **方案 ≠ 改稿**：原稿照录归档，修订版另建目录
2. **每个追加点必须带字数预算**（300–800 字/处）——不然执行时没谱
3. **追加点必须具体可执行**：场景名 + 内容分条 + 埋的线／达成的效果。写「可以加深反派的形象」这种空话等于没写
4. **不破坏现有节奏和语气**：追加内容要贴原作口吻（方案末尾显式声明这条原则）
5. **留悬念给续篇，不硬填**：能作续篇种子的线标注「可留」，避免冲淡主角主线

## 五步流程

| 步 | 做什么 | 产出 |
|:--|:--|:--|
| 1 | **全文评估** | 完结状态检查（主线闭环／成长弧光／结局与主题自洽）+ 缺口清单表（角色纵深／设定起源／社会层面／支线闭环／主角心理／收尾力度／结构问题） |
| 2 | **逐章修订大纲** | 每章一节：建议新标题、现有内容一句话、追加场景（带字数）、追加点分条、视觉效果建议 |
| 3 | **信息融合计划** | 背景设定碎片化：核心信息矩阵（模块→嵌入位置）、逐章嵌入方案、信息密度曲线、时间线对照表 |
| 4 | **结构总览**（可选） | 分部分章：功能定位、情绪曲线、章节标题体系、逐节大纲 |
| 5 | **修订优先级** | ★ 分级表（★★★★★ 必改 → ★★☆☆☆ 可选），按「缺了对作品伤害最大」排序 |

追加场景的**弹药库**（从实战里抽的）：独处戏 / 平行视角 / 物件戏 / 对话补深 / 日常细节。

## 三件套什么时候全上（别每次三份全上）

| 方案 | 什么时候要 |
|:--|:--|
| 01 逐章修订大纲 | **默认**：任何写完的长稿都用 |
| 02 信息融合计划 | 只在**背景设定多**（前史／世界观／组织起源一大坨）时才用 |
| 03 结构总览 | 只有**大改结构**（分部分章、重排叙事）时才用 |

## 模板

`templates/revision-plan.md` —— 修订方案标准模板（评估／逐章／信息融合／结构／优先级五件套）。

## 坑

- **别把修订方案写成读后感**——要可执行：什么场景、加在哪、多少字、什么效果
- **追加点别超过既有章节的信息密度**——每章预算总量控制（实战：8 章共追加约 2 万字符，单章 2000–3000 字）
- **别替作者改标题体系**——先看原稿有没有标题，没有才建议（「八章全是编号」才是问题）
- **平行视角是双刃剑**——能补信息，但会打断主角视角；用在关键节点，一稿别超过 3 处
- **修订优先级必须给**——没有优先级的方案等于全都要改，执行时无从下手
- **方案写得比稿子好不算成功**——执行时逐条能落地才算；字数预算是关键，没预算的追加点执行时必然跑偏

## 前置判断 · 方案文档可能是思路本身

收到一份「修订方案／大纲文档」时，**它可能是思路本身而不是待执行的成品**——拿不准先问对方要哪种（照做 / 当参考 / 提炼骨架），别默认当任务书开工。

## 姊妹仓库

- [liya-prose-quality-metrics](https://github.com/feverZHONG/liya-prose-quality-metrics) —— 稿子质量的量化体检：先量再改（改稿之前先量，本仓管「改什么」，它管「平在哪」）
- [liya-corpus-line-mining](https://github.com/feverZHONG/liya-corpus-line-mining) —— 从本地语料／会话库挖可复用原句
- [liya-subtraction-skill](https://github.com/feverZHONG/liya-subtraction-skill) —— 技能库做减法：减法优先、去重、归档、拆薄
- [liya-persona-authoring](https://github.com/feverZHONG/liya-persona-authoring) —— 给 AI agent 写它自己的身份文件（SOUL.md）
- [liya-sillytavern-cards](https://github.com/feverZHONG/liya-sillytavern-cards) · [liya-tavern-card-refinement](https://github.com/feverZHONG/liya-tavern-card-refinement) · [liya-sillytavern-worldbook](https://github.com/feverZHONG/liya-sillytavern-worldbook) —— 酒馆角色卡三件（写卡 / 精修 / 世界书）
- [liya-vision-recognition-traps](https://github.com/feverZHONG/liya-vision-recognition-traps) —— 视觉模型识图陷阱：实测陷阱 + 真 OCR 通道 + 两图差分
- [liya-chat-game-referee](https://github.com/feverZHONG/liya-chat-game-referee) · [liya-spy-game](https://github.com/feverZHONG/liya-spy-game) · [liya-sea-turtle-soup](https://github.com/feverZHONG/liya-sea-turtle-soup) —— 聊天里能玩的三件（回合制裁判引擎 / 谁是卧底 / 海龟汤）
- [liya-delegation-and-verification](https://github.com/feverZHONG/liya-delegation-and-verification) —— 委派与验收：给子代理写任务书、并行隔离、把「自报」验成事实
- [liya-ruozhiba-wordbank](https://github.com/feverZHONG/liya-ruozhiba-wordbank) —— 弱智吧题防御手册：中文逻辑陷阱题 160 道逐题拆解 + 三连防御法
- [liya-subtitle-proofreading](https://github.com/feverZHONG/liya-subtitle-proofreading) —— 字幕校对/重建/外挂 SRT
- [liya-dev-workflow](https://github.com/feverZHONG/liya-dev-workflow) —— 开发全流程方法论：环境侦查／计划／spike／TDD／迭代脚本／调试／预提交审查／推送排障／同步验收
- [liya-news-verification](https://github.com/feverZHONG/liya-news-verification) —— 验证伞：轻量核查／交付前多源验证／链接危险识别／厂商官宣核实／链接考古（含 link_check 工具族）
- [liya-knowledge-persistence](https://github.com/feverZHONG/liya-knowledge-persistence) —— 知识持久化：信息该放记忆层／文件／技能库的分层规范（附记录完整性、语料减法、归档模式）
- [liya-incident-review](https://github.com/feverZHONG/liya-incident-review) —— 社群事件复盘：素材收集 → 时间线重构 → 交叉验证 → 矛盾管理（输出理解不输出建议）
- [liya-document-translation](https://github.com/feverZHONG/liya-document-translation) —— 论文与长文档翻译：提取全文 → 术语表 → 并行分章 → 质量抽查 → 归档
- [liya-source-code-investigation](https://github.com/feverZHONG/liya-source-code-investigation) —— 外部项目调查：源码审计 / 拆包分层 / 数据实测 / 身份链（结论导向，非取用）
- [liya-character-voice-simulation](https://github.com/feverZHONG/liya-character-voice-simulation) —— 角色声线推演：锚点表双向用——分队推演（隔离上下文）＋ 反查认说话人
- [liya-dialogue-system-builder](https://github.com/feverZHONG/liya-dialogue-system-builder)

## 提思路 / 提修正

- 你那边的修订流程、缺口类型、追加点写法 → 开 [Issue](https://github.com/feverZHONG/liya-story-revision-plan/issues)
- 想直接改 → Fork + PR

## 许可

**双许可**——文档与代码分开：

- **代码**（`scripts/` 下的文件）：**MIT** —— 拿去用、改、再发，保留版权声明即可。
- **文档**（`SKILL.md`、`templates/`、本 README 的正文）：**[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)** —— 可以自由使用、改编、连商用都行，**但要署名**（莉娅 / [@feverZHONG](https://github.com/feverZHONG)）并注明来源。

本仓当前是**纯文档仓**（模板在 `templates/`，无 `scripts/`），`LICENSE` 留作后续脚本的默认许可。两份全文：`LICENSE`（MIT）／`LICENSE-DOCS`（CC BY 4.0）。

---

*莉娅（[@feverZHONG](https://github.com/feverZHONG)）· 宇宙美好记录官*
