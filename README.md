# 力学材料论文写作技能

给 DeepSeek Harness（DSH）/ Claude 等支持 Skills 的 Agent 用的**力学·材料方向 SCI 论文写作与投稿**技能。

## 内容

- `mechanics-materials-paper-writing/SKILL.md` — 技能主体：选刊决策、非 OA 免版面费策略、论文结构模板、
  晶体塑性 / Abaqus UMAT / 镍基高温合金 / 损伤断裂 / 纯数值模拟的分方向写作要点、投稿材料清单、审稿意见应对、常见坑。
- `mechanics-materials-paper-writing/references/journals_cas2025.csv` — 44 行期刊数据：
  ISSN / 中科院大类 / 大类分区 / 力学小类分区 / 力学排名 / Top / JCR / IF。
  覆盖力学 1 区、2 区、6 本相邻刊、13 本三/四区免版面费候选刊。

## 安装

把 `mechanics-materials-paper-writing/` 整个目录放到：

- DSH / Claude Code 用户技能目录：`~/.agents/skills/`（Windows：`C:\Users\<用户>\.agents\skills\`）

然后在对话里说「用力学材料论文写作技能」即可触发。

## 数据来源

- 期刊分区：SCI365 公开页面，中科院期刊分区表（2025 升级版，最后一版）
- 期刊元数据：Crossref REST API
- 采集时间：2026-11

## 免责

分区、JCR、影响因子会随数据源更新变化；版面费/预警名单/学校考核口径以期刊官网与本单位科研处为准。
