---
name: mechanics-materials-paper-writing
description: >-
  力学 / 材料方向 SCI 论文写作与投稿技能：内置中科院分区（2025 升级版）期刊库（力学 1 区/2 区
  + 相邻刊 + 三/四区免版面费候选），提供选刊决策、非 OA 免 APC 策略、
  晶体塑性 / Abaqus UMAT / 镍基高温合金 / 损伤力学 / 纯数值模拟类论文的结构模板、
  对标文献检索与本地文献库用法、投稿前后检查清单。
  当用户要写力学或材料类 SCI 论文、选刊、比较期刊分区与版面费、找对标文献、
  准备 cover letter / 投稿材料时使用。
metadata:
  {"openclaw": {"emoji": "📝"}}
---

# 力学材料论文写作 SKILL

面向固体力学 / 计算材料方向（晶体塑性、本构模型、Abaqus UMAT、镍基高温合金、损伤与断裂、有限元数值模拟）的论文写作与投稿助手。

## 1. 何时使用

- 用户要**写 / 改**一篇力学或材料类 SCI 论文（尤其晶体塑性、本构、损伤、数值模拟）；
- 用户要**选刊**：判断中科院分区、是否 Top、JCR、版面费（APC）、录用难度；
- 用户要**找对标文献**（“这个刊最近发什么风格的文章”）；
- 用户要**准备投稿材料**（cover letter、highlights、graphical abstract、审稿人推荐）；
- 用户要判断“这本刊收不收版面费 / 会不会被预警 / 能不能用于考核”。

## 2. 必须讲清的核心事实（避免用户踩坑）

1. **中科院分区（2025 升级版）是最后一版**。据公开信息，中科院文献情报中心自 2026 年起不再更新发布期刊分区表；2026 年之后的“新锐分区”由新锐学术发布，与原中科院分区有人员/方法传承但不是官方分区。**学校认可哪套口径，必须让用户去科研处确认**，不要替他假设。
2. **中科院分区 ≠ JCR 分区**。同一本刊可能 JCR Q1 而中科院 3 区（如 Acta Mechanica）。国内考核普遍看中科院**大类**分区，部分学校认小类，必须先问清楚。
3. **“非 OA 发表”不等于零费用**。订阅制/混合刊通常不收 APC，但可能有超页费、彩图费、彩印费。推荐前必须查作者指南（Author Guidelines / Open Access 页面）确认。
4. **分区表有预警机制**：进入当年《国际期刊预警名单》的期刊不给分区，投稿前查一次预警名单。
5. 俄罗斯出版背景的刊物（Mechanics of Solids、International Applied Mechanics、Strength of Materials、Journal of Applied Mechanics and Technical Physics 等）支付与出版流程有额外风险，优先度放低。
6. 数据时效：本技能内置分区数据采集于 2026-11（SCI365 页面，中科院 2025 升级版），引用时说明来源与时间。

## 3. 内置期刊库（中科院 2025 升级版，实测数据）

> 完整机器可读版本：`references/journals_cas2025.csv`（含 ISSN、大类、大类分区、力学小类分区、Top、JCR、IF）。

### 3.1 力学 1 区（固体力学方向重点）

| 期刊 | ISSN | 中科院大类 | 大类分区 | 力学排名 | Top | JCR | IF |
|---|---|---|---|---|---|---|---|
| International Journal of Plasticity | 0749-6419 | 材料科学 | 1 | 2/171 | 是 | Q1 | 15.4 |
| Applied Mechanics Reviews | 0003-6900 | 工程技术 | 1 | 3/171 | 是 | Q1 | 19.1 |
| International Journal of Mechanical Sciences | 0020-7403 | 工程技术 | 1 | 5/171 | 是 | Q1 | 11.4 |
| Computer Methods in Applied Mechanics and Engineering | 0045-7825 | 工程技术 | 1 | 6/171 | 是 | Q1 | 7.6 |
| Composite Structures | 0263-8223 | 材料科学 | 2 | 9/171 | 否 | Q1 | 7.8 |
| International Journal of Impact Engineering | 0734-743X | 工程技术 | 2 | 10/171 | 否 | Q1 | 6.7 |
| Thin-Walled Structures | 0263-8231 | 工程技术 | 2 | 11/171 | 是 | Q1 | 8.3 |
| Theoretical and Applied Fracture Mechanics | 0167-8442 | 工程技术 | 2 | 13/171 | 是 | Q1 | 6.0 |

### 3.2 力学 2 区（核心固力刊都在这里）

| 期刊 | ISSN | 中科院大类 | 大类分区 | 力学排名 | Top | JCR | IF |
|---|---|---|---|---|---|---|---|
| Journal of the Mechanics and Physics of Solids | 0022-5096 | 工程技术 | 2 | 15/171 | 否 | Q1 | 6.2 |
| International Journal of Heat and Mass Transfer | 0017-9310 | 工程技术 | 2 | 20/171 | 否 | Q1 | 6.6 |
| Applied Mathematical Modelling | 0307-904X | 工程技术 | 2 | 22/171 | 否 | Q1 | 5.5 |
| Nonlinear Dynamics | 0924-090X | 工程技术 | 2 | 23/171 | 否 | Q1 | 5.7 |
| Engineering Fracture Mechanics | 0013-7944 | 工程技术 | 2 | 25/171 | 否 | Q1 | 6.2 |
| Journal of Sound and Vibration | 0022-460X | 工程技术 | 2 | 26/171 | 否 | Q1 | 5.8 |
| International Journal of Damage Mechanics | 1056-7895 | 工程技术 | 2 | 27/171 | 否 | Q2 | 3.0 |
| European Journal of Mechanics - A/Solids | 0997-7538 | 工程技术 | 2 | 29/171 | 否 | Q1 | 4.7 |
| Computational Mechanics | 0178-7675 | 工程技术 | 2 | 34/171 | 否 | Q1 | 4.5 |
| International Journal of Solids and Structures | 0020-7683 | 工程技术 | 2 | 37/171 | 否 | Q1 | 4.6 |
| Applied Mathematics and Mechanics | 0253-4827 | 工程技术 | 2 | 38/171 | 否 | Q1 | 4.9 |
| Theoretical and Applied Mechanics Letters | 2095-0349 | 工程技术 | 2 | 41/171 | 否 | Q2 | 3.0 |

（流体方向 2 区：Physics of Fluids、J. Fluid Mechanics、J. Fluids and Structures、Int. J. Multiphase Flow 等，见 CSV。）

### 3.3 相邻刊（非力学小类，但大类 1–2 区，固体力学/强度方向常用）

| 期刊 | ISSN | 大类 | 分区 | Top | IF |
|---|---|---|---|---|---|
| International Journal of Fatigue | 0142-1123 | 材料科学 | 2 | 是 | 7.0 |
| Composites Science and Technology | 0266-3538 | 材料科学 | 2 | 是 | 9.9 |
| International Journal of Engineering Science | 0020-7225 | 工程技术 | 2 | 否 | 5.4 |
| Mechanical Systems and Signal Processing | 0888-3270 | 工程技术 | 1 | 是 | 10.2 |
| Archives of Computational Methods in Engineering | 1134-3060 | 工程技术 | 1 | 是 | 12.9 |
| Journal of Computational Physics | 0021-9991 | 物理与天体物理 | 2 | 是 | 3.9 |

### 3.4 三 / 四区候选（不花钱投稿候选，需逐刊核实费用与录用难度）

| 期刊 | ISSN | 大类 | 分区 | 力学小类 | JCR | IF | 备注 |
|---|---|---|---|---|---|---|---|
| Mechanics of Time-Dependent Materials | 1385-2000 | 材料科学 | 3 | 4 | Q1 | 4.5 | Springer，订阅路线免 APC；蠕变/黏塑性 |
| Acta Mechanica | 0001-5970 | 工程技术 | 3 | 4 | Q1 | 4.0 | Springer；理论/数值力学 |
| Mechanics Based Design of Structures and Machines | 1539-7734 | 工程技术 | 3 | 4 | Q2 | 3.7 | T&F，官方确认非 OA 免 APC |
| Fatigue & Fracture of Engineering Materials & Structures | 8756-758X | 材料科学 | 3 | — | Q2 | 3.2 | Wiley，疲劳/断裂 |
| Archive of Applied Mechanics | 0939-1533 | 工程技术 | 3 | 4 | Q2 | 3.1 | Springer；本构/有限元/塑性/损伤 |
| Mechanics of Advanced Materials and Structures | 1537-6494 | 材料科学 | 3 | 3 | — | — | T&F，官方确认非 OA 免 APC |
| Acta Mechanica Solida Sinica | 0894-9166 | 工程技术 | 4 | 4 | Q2 | 2.6 | Springer；中国力学学会英文刊 |
| Journal of Mechanical Science and Technology | 1738-494X | 工程技术 | 4 | — | Q3 | 2.2 | 机械有限元、结构优化 |
| Mechanics of Composite Materials | 0191-5665 | 材料科学 | 4 | 4 | Q3 | 1.6 | 偏复合材料 |
| Mechanics of Solids | 0025-6544 | 工程技术 | 4 | 4 | Q4 | 1.0 | 俄罗斯背景，慎选 |
| Journal of Applied Mechanics and Technical Physics | 0021-8944 | 工程技术 | 4 | 4 | Q4 | 0.8 | 俄罗斯背景，慎选 |
| Strength of Materials | 0039-2316 | 材料科学 | 4 | — | Q4 | 0.8 | 俄/乌背景，慎选 |
| International Applied Mechanics | 1063-7095 | 工程技术 | 4 | 4 | Q4 | 0.6 | 俄罗斯背景，慎选 |

### 3.5 高水平“免费发表”刊（订阅/混合，非 OA 不收 APC）

JMPS、IJP、Acta Materialia、Scripta Materialia、IJMS、CMAME 等传统订阅刊，选择非 OA 发表通常不收 APC（仍要确认超页/彩图费）。Nature Communications 是**完全 OA**，APC 约 $7,350，不适合“零费用”目标。

## 4. 选刊决策流程

```
用户考核要求（几年几篇什么分区？大类还是小类？认不认新锐/JCR？）
        │
        ├─ 需要中科院 2 区 → 走 §3.1/3.2/3.3，优先“2 区 + 非OA免费 + 无预警”
        │    主攻：IJP / IJMS / CMAME / TWS / TAFM / EFM / IJSS / ComposStruct / IJF / CST
        │
        ├─ 只要 3/4 区（奖励/申硕指标）→ 走 §3.4，先核实 APC=0 与录用难度
        │    首选：Archive of Applied Mechanics、Mechanics Based Design、
        │          Mechanics of Advanced Materials and Structures、Acta Mech Solida Sinica
        │
        └─ 只求快 → 3/4 区里 IF 2–4、Q2 的刊，避开俄罗斯背景刊物
```

**选刊必做三步核实**（不能只凭分区表）：
1. 期刊官网 Author Guidelines：APC / 超页费 / 彩图费；
2. 最新《国际期刊预警名单》是否包含；
3. 近 3 个月该刊是否有与用户选题相近的文章（说明 scope 匹配）。

## 5. 论文结构模板（力学/材料类 IMRaD 强化版）

**Title**：机制 + 材料/结构 + 方法，避免“Study on…”空话。
例：`Crystal-plasticity-informed damage model for γ′-strengthened Ni-based superalloys under creep–fatigue loading`

**Abstract（150–250 词，五句法）**：
1) 工程/科学问题一句话；2) 现有方法不足；3) 本文做了什么（模型/实验/框架）；4) 关键结果（带数字）；5) 意义/适用边界。

**Highlights（3–5 条，每条 ≤85 字符）**：每条一个“新事实”，不要写方法步骤。

**1 Introduction（4 段式）**：
- 段1：工程背景与重要性（引用 3–5 篇高被引/综述）；
- 段2：已有工作分类综述（分 2–3 类方法，指出代表文献）；
- 段3：现有工作的具体缺口（2–3 条，要能对应本文贡献）；
- 段4：本文贡献列表（3 条以内）+ 文章结构一句话。

**2 Model / Theory**：
- 2.1 运动学与基本假设（符号表放附录或文中表格）；
- 2.2 本构方程（张量形式写全，给出热力学一致性说明）；
- 2.3 数值实现（UMAT/VUMAT：时间积分格式、切线刚度、收敛判据、状态变量定义）；
- 2.4 参数标定流程（哪些参数来自文献、哪些反演、目标函数与误差指标）。

**3 Validation**：
- 3.1 与文献实验对比（应力–应变曲线、多工况；给误差量化，如 RMSE/相对误差）；
- 3.2 网格收敛性（至少 3 套网格，给收敛曲线或误差表）；
- 3.3 参数敏感性（关键参数 ±20% 的影响）；
- 3.4 与已有模型的对比（同工况下预测差异）。

**4 Results & Discussion**：先给验证，再给预测/机理解释；每个图对应一个结论句；讨论局限性与适用条件。

**5 Conclusions**：3–4 条，每条一句，可量化；不要重复摘要。

## 6. 分方向写作要点

### 6.1 晶体塑性 / CPFEM / Abaqus UMAT
- 必须写清：单晶弹性常数、滑移系族（FCC 12 系）、硬化模型（Kocks–Mecking / Bassani–Wu）、Taylor 因子或自洽均匀化；
- 参数标定：单晶/多晶实验曲线（至少 2 个应变率或 2 个温度）；EBSD 初始织构如何映射到 RVE；
- 验证：多晶 RVE 尺寸收敛（晶粒数 50/100/200）、边界条件（PBC vs 位移控制）影响；
- 常见审稿意见：“UMAT 数值细节不足”“参数标定不唯一”“未与实验织构对比”——提前在文中回答。

### 6.2 镍基高温合金
- 析出相（γ′/γ″）体积分数与尺寸分布、错配度、蠕变/疲劳加载历史；
- 若做析出强化建模，说明与 Orowan / 切过机制的对应关系；
- 实验数据优先用公开文献的应力–应变、蠕变曲线、EBSD/TEM 结果。

### 6.3 损伤 / 断裂
- 模型选择写清：GTN、CDM（Lemaitre/Chaboche）、相场、CZM；参数识别用反演 + 实验曲线；
- 网格依赖性：损伤模型必须做网格正则化或非局部处理，否则审稿必问；
- 断裂韧性/裂纹扩展速率与文献对比。

### 6.4 纯数值模拟（无自有实验）
- 创新点包装三选一：新模型/新算法、新耦合机制、新工况/新尺度；
- 验证必须用**文献实验数据**（至少 2 组独立来源）+ 网格收敛 + 参数敏感性；
- 结论要给出适用范围，不要过度外推。

## 7. 图表与数据规范

- 应力–应变曲线：横纵坐标带单位，标注实验/模拟，误差带要说明来源；
- 云图：统一色标范围（对比图必须同色标），标注变形放大系数；
- 微观组织图：标尺、取向图配色说明（IPF 图例）；
- 表格：参数表给单位与来源（文献 [x] / 本文标定）；
- 数据可用性声明（Data availability）越来越常被要求，准备好原始数据/脚本仓库。

## 8. 投稿材料清单

1. Cover letter（1 页）：期刊名 + 一句贡献 + 为何适合该刊 + 无利益冲突 + 未一稿多投；
2. Highlights（3–5 条）；
3. Graphical abstract（可选，但很多 Elsevier 刊鼓励）；
4. 推荐审稿人（3–5 位，同方向、无合作关系）；
5. CRediT 作者贡献声明；
6. 数据可用性声明；
7. 检查：图分辨率（≥300 dpi 线图、≥600 dpi 位图）、参考文献格式、字数/页数限制。

## 9. 审稿意见应对

| 审稿意见类型 | 应对模板 |
|---|---|
| “模型验证不足” | 补一组独立文献实验数据 + 误差表，说明参数未重新标定 |
| “参数标定不唯一” | 给参数敏感性分析 + 多组参数对比，说明选取依据 |
| “网格依赖” | 补 3 套网格收敛曲线 + 正则化说明 |
| “创新性不足” | 明确 2–3 条与已有工作的差异（最好有对比算例） |
| “英文表达” | 全文润色，回复中说明已请母语者/专业润色 |

## 10. 本地文献库（本机已有，优先复用）

```
papers/
├─ 力学一区二区_最新论文清单_202608-11.xlsx   # 5,879 篇 1/2 区论文（含分区/被引/直链）
├─ 三四区选刊参考_近3个月论文.xlsx            # 13 本三/四区候选刊 935 篇，373 篇方向相关
├─ 论文库_全部.ris / .bib                    # Zotero/EndNote 导入
├─ pdf/<期刊简称>/                            # 已下载 OA 全文（600+ 篇）
├─ 文献传递_批处理/                           # 学校无订阅时的文献传递申请材料
└─ _scripts/                                 # Crossref/SCI365/Unpaywall 采集脚本（可重跑）
```

**找对标文献的标准动作**：
1. 打开对应 Excel，按「期刊简称 + 上线日期」筛选目标刊近 3 个月文章；
2. 「核心刊精选」/「方向相关」表里挑 10–20 篇同主题文章；
3. 用 `pdf/` 里已下载的全文看结构（Introduction 怎么切入、Validation 怎么排）；
4. 若目标刊文章没有 PDF → 走文献传递清单模板申请。

## 11. 数据获取渠道（可重跑）

| 用途 | 渠道 | 说明 |
|---|---|---|
| 元数据/DOI/卷期页 | Crossref REST API | 免费，`https://api.crossref.org` |
| 中科院分区（2025 升级版） | SCI365 期刊页 | 文本可抓，含大类/小类/Top/JCR/IF |
| 开放获取全文 | Unpaywall / Semantic Scholar / arXiv | 免费 |
| 订阅全文 | 学校图书馆文献传递（0.5–3 元/篇） | 无订阅时唯一低成本合法路径 |
| 文献管理 | Zotero（导入 RIS 后「查找可获取的 PDF」） | 批量抓 OA |

## 12. 常见坑清单

- ❌ 把 JCR Q1 当成中科院 1 区（两者不是一回事）；
- ❌ 以为“非 OA”就一定零费用（超页/彩图费仍可能收）；
- ❌ 2026 年后仍按旧版分区投考核刊（中科院已停更，学校口径要先确认）；
- ❌ 投预警名单期刊（可能不给分区/不认）；
- ❌ 纯数值论文只放云图、无定量验证（审稿高频拒稿理由）；
- ❌ 俄罗斯背景低区刊的付款/出版风险；
- ❌ 一稿多投、图重复使用、参考文献自引堆砌。

## 13. 参考数据文件

- `references/journals_cas2025.csv`：力学 1/2 区、相邻刊、三/四区候选刊的完整数据（ISSN / 大类 / 分区 / 力学排名 / Top / JCR / IF），可直接用 Excel 打开筛选。
