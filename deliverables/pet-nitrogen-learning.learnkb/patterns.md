# PET 含氮化学品文献方法库

由 methods.json 生成；修改主数据后重新生成。

保存材料中的实验/模型方法及其条件，属于文献学习卡；整体跨论文结构另存 methodology.json。

## 比较 1:1 介质和底物稀释条件

`pet-nitrogen-papers/r01@1.0.0` · material

该实验观察到介质比及浓度改变双腈选择性。

### 解决的问题

先把 PET 氨解为对苯二甲酰胺，再由 Pd 催化水转移生成对苯二腈；酰胺完全转化仍可能留下单腈。

### 适用场景

复现 Pd/乙腈/水脱水并希望提高双腈比例

### 使用前提

- 模型酰胺、指定 Pd 与溶剂体系

### 限制与不适用情况

- 25 mg 条件的 68% 不是 PET 总收率。

### 原理与依据

该实验观察到介质比及浓度改变双腈选择性。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较 1:1 介质和底物稀释条件
   - 输入: 模型酰胺、指定 Pd 与溶剂体系
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 1.pdf · 标题路径：Upcycling of poly(ethylene terephthalate) waste plastics to terephthalonitrile · PDF 第4页 [src-e62068f57189-pdf_page-00004]
  maximum yield                     61%. At 100 °C and 120 °C, the reaction reached equilibrium
obtained at a 1 : 1 ratio (Fig. 2d). When the substrate amount            after 8 hours and 4 hours, respectively.
varied from 200 mg to 25 mg, we observed higher selectivity                   We then conducted NMR and FT-IR an

## 按平衡平台比较产率而不把延时等同继续增产

`pet-nitrogen-papers/r02@1.0.0` · material

100℃约8 h、120℃约4 h 后双腈产率受平衡限制。

### 解决的问题

单腈积累与正反向水转移平衡有关；质谱和光谱支持共同 Pd 配位物，但具体催化循环仍是提议。

### 适用场景

100℃或120℃曲线已到观察到的平衡平台

### 使用前提

- 本文 Pd 水转移体系

### 限制与不适用情况

- 温度变化只在测试范围内解释。

### 原理与依据

100℃约8 h、120℃约4 h 后双腈产率受平衡限制。

### 效果检查

- 平台以后不承诺达到100%双腈。

### 执行步骤

1. 按平衡平台比较产率而不把延时等同继续增产
   - 输入: 本文 Pd 水转移体系
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 平台以后不承诺达到100%双腈。

### 出处与短引文

- 1.pdf · 标题路径：Upcycling of poly(ethylene terephthalate) waste plastics to terephthalonitrile · PDF 第4页 [src-e62068f57189-pdf_page-00004]
  equilibrium
obtained at a 1 : 1 ratio (Fig. 2d). When the substrate amount            after 8 hours and 4 hours, respectively.
varied from 200 mg to 25 mg, we observed higher selectivity                   We then conducted NMR and FT-IR analyses to monitor the
for terephthalonitrile over 4-cyan

## 先隔离、水洗和干燥酰胺

`pet-nitrogen-papers/r03@1.0.0` · material

残氨强配位与 EG 促进 Pd 黑导致一锅不兼容。

### 解决的问题

氨和残留 EG 会抑制 Pd 脱水；真实原料耐受性与催化剂回收损失共同决定串联流程表现。

### 适用场景

氨解中间体将进入 Pd 脱水

### 使用前提

- 已完成 PET 氨解

### 限制与不适用情况

- 清洗和隔离意味着额外操作，不是无损一锅串联。

### 原理与依据

残氨强配位与 EG 促进 Pd 黑导致一锅不兼容。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 先隔离、水洗和干燥酰胺
   - 输入: 已完成 PET 氨解
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 1.pdf · 标题路径：Upcycling of poly(ethylene terephthalate) waste plastics to terephthalonitrile · PDF 第6页 [src-e62068f57189-pdf_page-00006]
  one-pot transformation from PET to
(CH3CN)x(H2O)y(OH)t species, which subsequently condense          terephthalonitrile by combining the ammonolysis and de-
into a dimer (major form) and a tetramer (minor form)             hydration steps were unsuccessful, even when the

## 蒸发后水洗并按需求进一步重结晶

`pet-nitrogen-papers/r04@1.0.0` · material

分离 TPN 与溶于水的乙酰胺/单腈可改善纯度并减少逆反应组分。

### 解决的问题

氨和残留 EG 会抑制 Pd 脱水；真实原料耐受性与催化剂回收损失共同决定串联流程表现。

### 适用场景

回收 Pd 水转移反应中的 TPN

### 使用前提

- 本文反应后混合物

### 限制与不适用情况

- 水洗约93%纯度，金属回收有损失。

### 原理与依据

分离 TPN 与溶于水的乙酰胺/单腈可改善纯度并减少逆反应组分。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 蒸发后水洗并按需求进一步重结晶
   - 输入: 本文反应后混合物
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 1.pdf · 标题路径：Upcycling of poly(ethylene terephthalate) waste plastics to terephthalonitrile · PDF 第7页 [src-e62068f57189-pdf_page-00007]
  12.5 : 1, approximately 93% purity) (Fig. S7). The                tional approach from p-xylene, our approach achieves a 28%
product was further purified by recrystallization from an aceto-           lower carbon footprint (Fig. 5d), benefiting from the utilization
nitrile–w

## 比较提高酰胺进料浓度的流程情景

`pet-nitrogen-papers/r05@1.0.0` · material

每公斤产品的水/乙腈蒸发负荷降低。

### 解决的问题

低温不是低碳的充分条件；该模型中水和乙腈蒸发以及底物浓度主导碳足迹。

### 适用场景

模型中蒸发贡献超过一半排放

### 使用前提

- 本篇工艺和 LCA 边界

### 限制与不适用情况

- 高浓度改善来自模型，需保证分离与反应仍可运行。

### 原理与依据

每公斤产品的水/乙腈蒸发负荷降低。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较提高酰胺进料浓度的流程情景
   - 输入: 本篇工艺和 LCA 边界
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 1.pdf · 标题路径：Upcycling of poly(ethylene terephthalate) waste plastics to terephthalonitrile · PDF 第7页 [src-e62068f57189-pdf_page-00007]
  more than half of the total CO2
reusability of the PdCl2 catalyst. An eﬀective recyclability               emissions originate from solvent evaporation due to the high
system should recover terephthalonitrile with high purity and              latent heat of water (Fig. S10), making the s

## 冷却至0℃并用少量水改善晶粒

`pet-nitrogen-papers/r06@1.0.0` · material

温度相关溶解度和晶粒增大便于过滤。

### 解决的问题

PET 先成为 BHET，再成为对苯二甲酰胺；反应和结晶分离共同为下游 Hofmann 重排准备进料。

### 适用场景

从 EG 中分离 BHET

### 使用前提

- 已生成 BHET 的乙二醇解液

### 限制与不适用情况

- 少量水条件限定本篇，不能任意加入。

### 原理与依据

温度相关溶解度和晶粒增大便于过滤。

### 效果检查

- 24 h 结晶后过滤。

### 执行步骤

1. 冷却至0℃并用少量水改善晶粒
   - 输入: 已生成 BHET 的乙二醇解液
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 24 h 结晶后过滤。

### 出处与短引文

- 11.pdf · 标题路径：Tandem Thermo−electrochemical Strategy for Upcycling Waste Poly(ethylene terephthalate) into Value-Added Aniline Derivatives · PDF 第3页 [src-214fbead528d-pdf_page-00003]
  100 μm with water; Figure S2), facilitating subsequent
When the catalyst loading was increased to 2%, the BHET                      centrifugal filtration and reducing product loss.
                                                                      7609                                   https://doi.org/10.1021/acssuschemeng.5c02544
                                                                                                            ACS Sustainable Chem. Eng. 2025

## 比较2 wt%催化剂而非继续增加

`pet-nitrogen-papers/r07@1.0.0` · material

更高负载未改善并有活性位覆盖的解释。

### 解决的问题

PET 先成为 BHET，再成为对苯二甲酰胺；反应和结晶分离共同为下游 Hofmann 重排准备进料。

### 适用场景

复现 Zn(OAc)₂ 催化乙二醇解的产率峰

### 使用前提

- 190℃/6 h及指定 EG 比

### 限制与不适用情况

- 不同真实料杂质会改变产率。

### 原理与依据

更高负载未改善并有活性位覆盖的解释。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较2 wt%催化剂而非继续增加
   - 输入: 190℃/6 h及指定 EG 比
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 11.pdf · 标题路径：Tandem Thermo−electrochemical Strategy for Upcycling Waste Poly(ethylene terephthalate) into Value-Added Aniline Derivatives · PDF 第3页 [src-214fbead528d-pdf_page-00003]
  90.5% with 6-h
and lead to more favorable reaction kinetics.45 For instance,
                                                                             degradation time, 190 °C reaction temperature, 2 wt %
ammonolysis reactions involving BHET proceed with higher
yields and faster rates compared to those utilizing TPA and                  catal

## 分开电卤化、加碱重排和热水解三阶段

`pet-nitrogen-papers/r08@1.0.0` · material

活性溴、碱和温度在三个阶段承担不同作用。

### 解决的问题

阳极产生活性溴，阴极生成碱；电卤化、碱重排和热水解脱羧共同形成 PABA/PPD。

### 适用场景

执行本文 TP 到 PABA/PPD 的 e-Hofmann 路线

### 使用前提

- 原文不分隔电解体系和介质

### 限制与不适用情况

- 不是所有阶段都由电流直接完成。

### 原理与依据

活性溴、碱和温度在三个阶段承担不同作用。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 分开电卤化、加碱重排和热水解三阶段
   - 输入: 原文不分隔电解体系和介质
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 11.pdf · 标题路径：Tandem Thermo−electrochemical Strategy for Upcycling Waste Poly(ethylene terephthalate) into Value-Added Aniline Derivatives · PDF 第5页 [src-214fbead528d-pdf_page-00005]
  first stage, using methanol/water mixtures as the
direct ammonolysis would have difficulty separating TP from                 solvent, H2O or MeOH gets reduced at the cathode,
the partially degraded amide oligomers, and the preparation of              generating hydrogen gas along with

## 将产率平台与活性溴回还原一起分析

`pet-nitrogen-papers/r09@1.0.0` · material

额外电量可被阴极副反应消耗而不增加目标物。

### 解决的问题

阳极产生活性溴，阴极生成碱；电卤化、碱重排和热水解脱羧共同形成 PABA/PPD。

### 适用场景

施加电量达到约5 F/mol后产率不再改善

### 使用前提

- 所测石墨/Pt不分隔体系

### 限制与不适用情况

- 阈值仅限原文，非任意电解槽通用。

### 原理与依据

额外电量可被阴极副反应消耗而不增加目标物。

### 效果检查

- 不把5–10 F/mol继续加电当作必然增产。

### 执行步骤

1. 将产率平台与活性溴回还原一起分析
   - 输入: 所测石墨/Pt不分隔体系
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 不把5–10 F/mol继续加电当作必然增产。

### 出处与短引文

- 11.pdf · 标题路径：Tandem Thermo−electrochemical Strategy for Upcycling Waste Poly(ethylene terephthalate) into Value-Added Aniline Derivatives · PDF 第6页 [src-214fbead528d-pdf_page-00006]
  5−10 F/mol charge passed revealed nearly identical                   from the oxidation of Br− to Br3− (3Br− ⇌ Br3− + 2e−), while
concentrations of active bromine (7.6 mM), indicating that the            the second one is attributed to the oxidation of Br3− to Br2
                                                                   7612                                  https://doi.org

## 比较0.94 mM重铬酸盐保护层条件

`pet-nitrogen-papers/r10@1.0.0` · material

Cr(OH)₃ 层抑制阴极活性溴还原并提高总产率。

### 解决的问题

阳极产生活性溴，阴极生成碱；电卤化、碱重排和热水解脱羧共同形成 PABA/PPD。

### 适用场景

评估阴极活性溴还原对 FE 的损失

### 使用前提

- 本文条件、需保留 Cr(VI) 使用事实

### 限制与不适用情况

- 改善不等于完全无危险试剂，不能推广成一般推荐。

### 原理与依据

Cr(OH)₃ 层抑制阴极活性溴还原并提高总产率。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较0.94 mM重铬酸盐保护层条件
   - 输入: 本文条件、需保留 Cr(VI) 使用事实
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 11.pdf · 标题路径：Tandem Thermo−electrochemical Strategy for Upcycling Waste Poly(ethylene terephthalate) into Value-Added Aniline Derivatives · PDF 第6页 [src-214fbead528d-pdf_page-00006]
  43.4%, and a
Hofmann rearrangement. We monitored the progress of the                   significantly improved total yield of 72.2% for PPD and PABA
reaction while increasing the charge input into the solution,             was achieved, which was 21.5% higher than that without
and PPD w

## 先固定1 kg同质量聚合物和北美系统边界

`pet-nitrogen-papers/r11@1.0.0` · material

功能单位和质量假设保证模型比较对象一致。

### 解决的问题

该论文评价的是废 PET 衍生单体制备 Kevlar 聚合物的 cradle-to-gate 模型，首先需要明确功能单位、原料负担和工业放大假设。

### 适用场景

比较废PET与原生Kevlar聚合物

### 使用前提

- 从收集到聚合的 LCI

### 限制与不适用情况

- 同质量是假设而非纤维力学实测。

### 原理与依据

功能单位和质量假设保证模型比较对象一致。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 先固定1 kg同质量聚合物和北美系统边界
   - 输入: 从收集到聚合的 LCI
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 12.pdf · 标题路径：Life Cycle Assessment of Chemical Upcycling of Postconsumer Polyethylene Terephthalate to Kevlar Polymer · PDF 第3页 [src-42d155ded4e1-pdf_page-00003]
  functional unit for this study is 1 kg of Kevlar                     allocation methodology for open-loop recycling.
production. The system boundary is shown in Figure 1,                          2.3. Upcycled Kevlar. 2.3.1. Mechanical Recycling.
illustrating the chemical upcycling process, starting from

## 从废料收集开始且不额外记替代原生PET信用

`pet-nitrogen-papers/r12@1.0.0` · material

前世负担已归原系统，额外信用会改变既定边界。

### 解决的问题

是否分摊前一世 PET 的负担会改变结果；单体制备的溶剂与试剂是主要优化对象。

### 适用场景

用cutoff评价开放循环PET升级

### 使用前提

- 本篇 cutoff 模型

### 限制与不适用情况

- 不能将此法结果与50/50直接拼接。

### 原理与依据

前世负担已归原系统，额外信用会改变既定边界。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 从废料收集开始且不额外记替代原生PET信用
   - 输入: 本篇 cutoff 模型
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 12.pdf · 标题路径：Life Cycle Assessment of Chemical Upcycling of Postconsumer Polyethylene Terephthalate to Kevlar Polymer · PDF 第3页 [src-42d155ded4e1-pdf_page-00003]
  Cut-Off Approach. The cutoff approach is most                       2.3.2. Depolymerization and Precursor Preparation. Part
commonly applied to avoid double-counting burdens between                   of chemical recycling includes PET polymer being broken
product systems and to avoid assum

## 比较5.3与3当量情景

`pet-nitrogen-papers/r13@1.0.0` · material

过量氯化剂贡献成本与环境负担，模型减少其用量。

### 解决的问题

替换碱、减少纯化溶剂和降低过量氯化剂可组合优化，但结果仍来自模型。

### 适用场景

评估TCL制备的过量SOCl₂热点

### 使用前提

- 保留目标TCL产率和纯度的场景假设

### 限制与不适用情况

- 不是本文实测工业配方验证。

### 原理与依据

过量氯化剂贡献成本与环境负担，模型减少其用量。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较5.3与3当量情景
   - 输入: 保留目标TCL产率和纯度的场景假设
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 12.pdf · 标题路径：Life Cycle Assessment of Chemical Upcycling of Postconsumer Polyethylene Terephthalate to Kevlar Polymer · PDF 第10页 [src-42d155ded4e1-pdf_page-00010]
  4.8% and the cost by 6.1% compared with the baseline                        compared to optimizing diethyl ether consumption. The best-
scenario. A previous study also reports that substituting KOH               case scenario, identified as S8, incorporates all modifications
with NaOH re

## 同时核对回收范围和再回收的额外投入

`pet-nitrogen-papers/r14@1.0.0` · material

净收益来自溶剂替代信用与能耗/试剂负担的权衡。

### 解决的问题

溶剂回收率和价格比小幅温度或收率变化更影响该模型；统计范围不消除清单假设的结构性限制。

### 适用场景

解释溶剂回收率的环境敏感性

### 使用前提

- 原模型95%基线及敏感性范围

### 限制与不适用情况

- 副产物提高回收未必总带来净改善。

### 原理与依据

净收益来自溶剂替代信用与能耗/试剂负担的权衡。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 同时核对回收范围和再回收的额外投入
   - 输入: 原模型95%基线及敏感性范围
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 12.pdf · 标题路径：Life Cycle Assessment of Chemical Upcycling of Postconsumer Polyethylene Terephthalate to Kevlar Polymer · PDF 第11页 [src-42d155ded4e1-pdf_page-00011]
  37% and                          lower ecotoxicity impacts. Transportation and waste have a
ecotoxicity by 30%. Sensitivity analysis reveals that more reuse              minimal impact compared to raw materials and chemicals.
of solvents lowers the environmental impact of chemical                       Hots

## 比较THF溶胀和目标TP产率

`pet-nitrogen-papers/r15@1.0.0` · material

甲苯中高PET消失仍只生成较低TP比例。

### 解决的问题

ZnCl₂/THF 氨解把 PET 转成可过滤的酰胺；PET 消失与目标酰胺生成需独立定量。

### 适用场景

选择ZnCl₂氨解PET的溶剂

### 使用前提

- 本篇220℃氨解条件

### 限制与不适用情况

- THF条件不能直接迁移到低温EG或气固体系。

### 原理与依据

甲苯中高PET消失仍只生成较低TP比例。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较THF溶胀和目标TP产率
   - 输入: 本篇220℃氨解条件
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 2.pdf · 标题路径：Upcycling PET waste into high value-added p-xylylenediamine (PXDA): A route to diversify PET-derived chemicals · PDF 第3页 [src-fac9747cbb51-pdf_page-00003]
  32.4 %, and a considerable amount
    Typically, TP (0.1 g), TiO2 (0.1 g) and acetonitrile (5 g) were loaded        of soluble oligomers remains (Fig. S1). In contrast, the yield of TP in THF
into a stainless-steel autoclave reactor. The reactor underwent three N₂          reac

## 比较NH₃分压0.2到0.5 MPa

`pet-nitrogen-papers/r16@1.0.0` · material

较高氨压在所测条件提高TP收率。

### 解决的问题

ZnCl₂/THF 氨解把 PET 转成可过滤的酰胺；PET 消失与目标酰胺生成需独立定量。

### 适用场景

提高原文第一段有效氨供给

### 使用前提

- ZnCl₂/THF和N₂总压条件

### 限制与不适用情况

- 不外推为任意增压均安全或均提高产量。

### 原理与依据

较高氨压在所测条件提高TP收率。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较NH₃分压0.2到0.5 MPa
   - 输入: ZnCl₂/THF和N₂总压条件
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 2.pdf · 标题路径：Upcycling PET waste into high value-added p-xylylenediamine (PXDA): A route to diversify PET-derived chemicals · PDF 第3页 [src-fac9747cbb51-pdf_page-00003]
  85.3 %) is achieved with only 10 mg ZnCl2,
 TP conversion = 1 −                     × 100%                         (4)
                          minitial Tp                                             and further increasing the dosage of the catalyst has little effect on the
                                                                                  TP yield. Finally, the influence of ammonia pressure on the TP yield was
                nproduced TPN
TPN yield =                      × 100%

## 用260℃/4 h观察窗口比较而不无限延时升温

`pet-nitrogen-papers/r17@1.0.0` · material

焦化与产物损失使TPN收率下降。

### 解决的问题

TiO₂ 催化酰胺到 TPN，但高温或过长时间会把产物损失到焦化。

### 适用场景

TiO₂脱水超过产率峰或继续升温

### 使用前提

- 指定TiO₂/乙腈和N₂压力

### 限制与不适用情况

- 温度更低可有较高选择性但产率不同。

### 原理与依据

焦化与产物损失使TPN收率下降。

### 效果检查

- 超过4 h产率下降时停止以延时增产的假设。

### 执行步骤

1. 用260℃/4 h观察窗口比较而不无限延时升温
   - 输入: 指定TiO₂/乙腈和N₂压力
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 超过4 h产率下降时停止以延时增产的假设。

### 出处与短引文

- 2.pdf · 标题路径：Upcycling PET waste into high value-added p-xylylenediamine (PXDA): A route to diversify PET-derived chemicals · PDF 第5页 [src-fac9747cbb51-pdf_page-00005]
  carbon yield, likely attributed to coke formation               attributable to the solvent, CDCl3. No additional peaks are observed,
from TP degradation at higher temperature [31]. The influence of re­                especially those originating from 4-cyanobenzamide, indicatin

## 加水作反溶剂并低温结晶

`pet-nitrogen-papers/r18@1.0.0` · material

TPN可分离为高纯固体供后续氢化。

### 解决的问题

TiO₂ 催化酰胺到 TPN，但高温或过长时间会把产物损失到焦化。

### 适用场景

从TiO₂/乙腈反应液分离TPN

### 使用前提

- 脱水完成后移除固体和溶剂

### 限制与不适用情况

- 65%是分离率，73.1%是分析率。

### 原理与依据

TPN可分离为高纯固体供后续氢化。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 加水作反溶剂并低温结晶
   - 输入: 脱水完成后移除固体和溶剂
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 2.pdf · 标题路径：Upcycling PET waste into high value-added p-xylylenediamine (PXDA): A route to diversify PET-derived chemicals · PDF 第3页 [src-fac9747cbb51-pdf_page-00003]
  − 4 ◦ C overnight to precip­
                                                                                  itate TPN. The purified TPN was then obtained via filtration, washing,
                                                                                  and drying.
2.2. Catalytic performance evaluation
                                                                                  2.2.3. TPN to PXDA process
2.2.1. PET ammonolysis process                                                        Typically, TPN (0.1 g), Pd/C (10 mg) and metha

## 加盐酸形成二盐酸盐并结晶

`pet-nitrogen-papers/r19@1.0.0` · material

盐酸盐形式便于隔离与结构确认。

### 解决的问题

高纯 TPN 氢化可制得 PXDA；产物价格与流程经济性不是同一结论。

### 适用场景

分离PXDA氢化产物

### 使用前提

- 氢化后的原文产物液

### 限制与不适用情况

- 盐酸盐质量不能直接当游离胺摩尔产率。

### 原理与依据

盐酸盐形式便于隔离与结构确认。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 加盐酸形成二盐酸盐并结晶
   - 输入: 氢化后的原文产物液
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 2.pdf · 标题路径：Upcycling PET waste into high value-added p-xylylenediamine (PXDA): A route to diversify PET-derived chemicals · PDF 第3页 [src-fac9747cbb51-pdf_page-00003]
  chloride. Finally, the purified product was obtained via filtration,
number of moles and MwPET represented the molar masses of the PET                 washing and drying.
repeating unit (192 g/mol).
                    (
                         mundepolymerized PET
                                              )                                   3. Results and discussion
PET conversion = 1 −                            × 100

## 使用记录的平均温度而非只用设定点

`pet-nitrogen-papers/r20@1.0.0` · material

升温历程影响反应时间和Arrhenius拟合。

### 解决的问题

DMT 先形成单酰胺 MCB，再形成 TPD；过量氨下可用两步拟一级模型，但速率不同。

### 适用场景

从温度实验拟合氨解速率

### 使用前提

- 可靠温度记录和NMR组分数据

### 限制与不适用情况

- 并不自动处理所有反应器非稳态温差。

### 原理与依据

升温历程影响反应时间和Arrhenius拟合。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 使用记录的平均温度而非只用设定点
   - 输入: 可靠温度记录和NMR组分数据
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 3.pdf · 标题路径：Upcycling Waste PET: I. Ammonolysis Kinetics of Model Dimethyl Terephthalate and the Catalytic Effects of Ethylene Glycol · PDF 第3页 [src-4833ddff420e-pdf_page-00003]
  average temperature experienced                       extinguished, the peaks related to TPD grow. The unknown
over the course of the reaction. Nominal temperatures are                        peaks consist of a multiplet between 8.03 and 7.93 ppm that
presented in Table 1 and correspond to the set poin

## 将解释限定在0–150℃并保留介质变化

`pet-nitrogen-papers/r21@1.0.0` · material

高温会出现甲胺等额外反应，315℃交叉是无效外推。

### 解决的问题

EG 提高两步速率，但整体完成时间由连续网络及中间体积累决定；高温外推有化学边界。

### 适用场景

使用DMT氨解模型进行温度预测

### 使用前提

- MeOH/NH₃模型与原参数定义

### 限制与不适用情况

- 预测不等于实测。

### 原理与依据

高温会出现甲胺等额外反应，315℃交叉是无效外推。

### 效果检查

- 不将315℃模型交叉当工艺优化点。

### 执行步骤

1. 将解释限定在0–150℃并保留介质变化
   - 输入: MeOH/NH₃模型与原参数定义
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 不将315℃模型交叉当工艺优化点。

### 出处与短引文

- 3.pdf · 标题路径：Upcycling Waste PET: I. Ammonolysis Kinetics of Model Dimethyl Terephthalate and the Catalytic Effects of Ethylene Glycol · PDF 第6页 [src-4833ddff420e-pdf_page-00006]
  315.0 °C. Such a high temperature is outside the range
because the amide group is less electron withdrawing than an                  of validity for the model−at temperatures exceeding about 150
ester group. Accordingly, the relatively delocalized electrons of             °C it is ob

## 固液两相分别NMR并合并质量平衡

`pet-nitrogen-papers/r22@1.0.0` · material

可溶BHET/HCB占液相，单测固体会漏计。

### 解决的问题

BHET→HCB→TPD 在 EG 中连续发生，定量必须同时考虑固体与液相；温度改变时氨溶解度也改变。

### 适用场景

定量BHET氨解早期样品

### 使用前提

- 按原文溶解和取样方法

### 限制与不适用情况

- 质量平衡依赖峰归属和代表性取样。

### 原理与依据

可溶BHET/HCB占液相，单测固体会漏计。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 固液两相分别NMR并合并质量平衡
   - 输入: 按原文溶解和取样方法
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 4.pdf · 标题路径：Upcycling of Waste Poly(ethylene Terephthalate): Ammonolysis Kinetics of Model Bis(2-Hydroxyethyl Terephthalate) and Particle Size Effects in Polymeric Substrates · PDF 第4页 [src-b1b3021b0f08-pdf_page-00004]
  solid samples
  reacting for 45 min at 50 °C, only 0.01 g (1 ppm) of the product is
                                                                                showing the reaction trajectory from BHET through HCB to TPD.
  recovered as a solid. The mass fraction recovered as solids
  steadily increases with time as the reactant is converted

## 先用简单切片而不默认增加昂贵细磨

`pet-nitrogen-papers/r23@1.0.0` · material

薄片与150–250 μm颗粒转化接近，进一步研磨增益小。

### 解决的问题

薄片与细粒相近，但毫米粒显著变慢；不是所有 PET 形状都由化学步骤控制。

### 适用场景

处理原文所测约400 μm厚PET薄片

### 使用前提

- 所测EG氨解薄膜体系

### 限制与不适用情况

- 不能推广到毫米厚粒子或不同形状。

### 原理与依据

薄片与150–250 μm颗粒转化接近，进一步研磨增益小。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 先用简单切片而不默认增加昂贵细磨
   - 输入: 所测EG氨解薄膜体系
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 4.pdf · 标题路径：Upcycling of Waste Poly(ethylene Terephthalate): Ammonolysis Kinetics of Model Bis(2-Hydroxyethyl Terephthalate) and Particle Size Effects in Polymeric Substrates · PDF 第7页 [src-b1b3021b0f08-pdf_page-00007]
  costs associated with energy-intensive
                                                                                       Here x ET1 is the mole fraction of ET1 bonds, k is the apparent
                                                                                   rate constant, and k 0 is the apparent pseudo–first-order rate con-
                                                                                   stant. The mole fraction of ET1 bonds is defined by Equation (14).
                                                                                                            nET1
                                                                                   x ET1 ¼                                                              (14)
                                                                                             nET

## 将有效因子、球形几何和D_eff联合拟合

`pet-nitrogen-papers/r24@1.0.0` · material

化学基准与颗粒速率差反映内部扩散影响。

### 解决的问题

将 BHET 化学速率与 PET 颗粒表观速率比较，可构建有效因子；扩散系数是条件依赖的拟合量。

### 适用场景

拟合粒径引起的反应利用率差异

### 使用前提

- BHET基准及三档颗粒数据

### 限制与不适用情况

- D_eff限于100℃EG溶胀多组分体系。

### 原理与依据

化学基准与颗粒速率差反映内部扩散影响。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 将有效因子、球形几何和D_eff联合拟合
   - 输入: BHET基准及三档颗粒数据
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 4.pdf · 标题路径：Upcycling of Waste Poly(ethylene Terephthalate): Ammonolysis Kinetics of Model Bis(2-Hydroxyethyl Terephthalate) and Particle Size Effects in Polymeric Substrates · PDF 第9页 [src-b1b3021b0f08-pdf_page-00009]
  1.37 
                                                                                    0.48 E-7 cm2 s1) falls within the range of known ammonia diffu-
                                                                                   sivities in other polymers at temperatures above their glass transi-
                                                                                   tion temperatures.
                                                                                        While published literature lacks specific information on the
                                                                                   diffusion of ammonia in PET, mod

## 比较120℃2 h与长时条件的两项响应

`pet-nitrogen-papers/r25@1.0.0` · material

长时纯度提高但碳化降低目标收率。

### 解决的问题

无水氨与 PET 气固反应可生成酰胺；多种表征共同确认身份，纯度和产率仍独立。

### 适用场景

提高无水氨气固酰胺产率同时保证纯度

### 使用前提

- 本篇PET薄片/无水氨釜条件

### 限制与不适用情况

- 不能只按最高纯度选择12 h。

### 原理与依据

长时纯度提高但碳化降低目标收率。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较120℃2 h与长时条件的两项响应
   - 输入: 本篇PET薄片/无水氨釜条件
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 5.pdf · 标题路径：Valorization of polyethylene terephthalate wastes to terephthalamide via catalyst-free ammonolysis · PDF 第5页 [src-484e6d8b37d7-pdf_page-00005]
  90.6 mol%) was achieved within approximately 2 h,
melting point and thermal stability (decomposition temperature >                    accompanied by a purity of 96.2 %. The comparison of this study with a
300 ◦ C). These findings, consistent with the prior elucidation, rei

## 比较300 rpm及PET/NH₃比而不任意减氨

`pet-nitrogen-papers/r26@1.0.0` · material

过低有效氨供给及不合适搅拌降低表现。

### 解决的问题

无水氨与 PET 气固反应可生成酰胺；多种表征共同确认身份，纯度和产率仍独立。

### 适用场景

筛选气固氨解混合和投料参数

### 使用前提

- 原文装置和试验负载

### 限制与不适用情况

- 搅拌转速非尺度无关。

### 原理与依据

过低有效氨供给及不合适搅拌降低表现。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较300 rpm及PET/NH₃比而不任意减氨
   - 输入: 原文装置和试验负载
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 5.pdf · 标题路径：Valorization of polyethylene terephthalate wastes to terephthalamide via catalyst-free ammonolysis · PDF 第8页 [src-484e6d8b37d7-pdf_page-00008]
  300 rpm                                                                                                       (4)
stirring yielded a notably elevated TP yield and purity (Fig. 6e) and the                          + 0.0885XBC − 1.28XA2 − 0.6874XB2 − 0.0982XC2
following experimental condition of stirring were set at 300 rpm.
                                                                                             where A, B, and C are the coded values of reaction time, tempera

## 独立重复验证产率与纯度

`pet-nitrogen-papers/r27@1.0.0` · material

实际87.34/94.50与模型88.83/100.46不同，拟合度不能代替验证。

### 解决的问题

三因素响应面可以描述试验范围内的产率和纯度变化，但预测纯度超出物理上限说明模型并未施加约束。

### 适用场景

响应面模型给出近似最优条件

### 使用前提

- 原BBD试验范围

### 限制与不适用情况

- 模型预测纯度超过100%，原表显著性有差异。

### 原理与依据

实际87.34/94.50与模型88.83/100.46不同，拟合度不能代替验证。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 独立重复验证产率与纯度
   - 输入: 原BBD试验范围
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 5.pdf · 标题路径：Valorization of polyethylene terephthalate wastes to terephthalamide via catalyst-free ammonolysis · PDF 第9页 [src-484e6d8b37d7-pdf_page-00009]
  87.34
mol% yield and 94.50 % purity across three repetitions (Table S5),                    This work was supported by the funding of Guangdong Basic and
aligning within a 95 % confidence interval, thereby verifying the                  Applied Basic Research Foundation, China (2022A15150

## 比较质量比1附近而不以更多尿素保证增产

`pet-nitrogen-papers/r28@1.0.0` · material

500℃时0.5→1改善而更高用量趋平台。

### 解决的问题

中等高温利于双腈；更高温促裂解和苯甲腈生成，最大 TPN 收率与最大选择性不完全一致。

### 适用场景

增加尿素作为供氨剂

### 使用前提

- 本篇PET/γ-Al₂O₃固定进料条件

### 限制与不适用情况

- 质量比与摩尔比不能混写。

### 原理与依据

500℃时0.5→1改善而更高用量趋平台。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较质量比1附近而不以更多尿素保证增产
   - 输入: 本篇PET/γ-Al₂O₃固定进料条件
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 6.pdf · 标题路径：Valorization of waste PET: Understanding the role of active ammonia in facilitating PET depolymerization and aromatic nitrile formation · PDF 第5页 [src-4fda33930eaf-pdf_page-00005]
  28.27 C%, which was a great
                                                                                         improvement. Moreover, the yields of TPN and aromatic nitriles did not
                                                                                         increase significantly with the further increase of urea dosage. Mean­
                                                                                         while, the urea dosage had little effect on the selectivity of TPN in the
                                                                                         aromatic nitri

## 比较550℃收率峰和500℃选择性

`pet-nitrogen-papers/r29@1.0.0` · material

更高温引发苯甲腈/芳烃而损失双腈选择性。

### 解决的问题

中等高温利于双腈；更高温促裂解和苯甲腈生成，最大 TPN 收率与最大选择性不完全一致。

### 适用场景

以TPN为尿素热解目标

### 使用前提

- 所测原位热解体系

### 限制与不适用情况

- 最高收率与最高选择性不同。

### 原理与依据

更高温引发苯甲腈/芳烃而损失双腈选择性。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 比较550℃收率峰和500℃选择性
   - 输入: 所测原位热解体系
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 6.pdf · 标题路径：Valorization of waste PET: Understanding the role of active ammonia in facilitating PET depolymerization and aromatic nitrile formation · PDF 第6页 [src-4fda33930eaf-pdf_page-00006]
  32.53 C%), indicating that γ-Al2O3
urea to PET.                                                                            may be slightly inactivated during pyrolysis regeneration, which was
                                                                                        related to the loss of acidic sites on the surface of γ-Al2O3 and the
situ catalytic pyrolysis with the urea process was an effective way to

## 按600℃4 h烧焦再生并检查活性损失

`pet-nitrogen-papers/r30@1.0.0` · material

四轮后产率下降，酸位与孔结构变化。

### 解决的问题

中等高温利于双腈；更高温促裂解和苯甲腈生成，最大 TPN 收率与最大选择性不完全一致。

### 适用场景

重复使用尿素热解γ-Al₂O₃

### 使用前提

- 本文催化剂和循环方法

### 限制与不适用情况

- 有限循环不等于完全恢复。

### 原理与依据

四轮后产率下降，酸位与孔结构变化。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 按600℃4 h烧焦再生并检查活性损失
   - 输入: 本文催化剂和循环方法
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 6.pdf · 标题路径：Valorization of waste PET: Understanding the role of active ammonia in facilitating PET depolymerization and aromatic nitrile formation · PDF 第6页 [src-4fda33930eaf-pdf_page-00006]
  600 ◦ C for 4 h to remove               of terephthalic acid ethylene glycol ester dimer (1, Fig. 8). Through
the coke and regenerate it. Fig. 7 shows the carbon yields of TPN,                      comparing the three decomposition mechanisms with and without the

## 同时看2%改性酸量和孔结构

`pet-nitrogen-papers/r31@1.0.0` · material

过量磷提高酸量但可能破坏孔结构。

### 解决的问题

酸位与孔结构改变芳腈选择性；催化筛选必须把孔结构损失与酸量提高一起看。

### 适用场景

筛选磷改性γ-Al₂O₃

### 使用前提

- P₂O₅质量标定与本文催化条件

### 限制与不适用情况

- 酸位数量不能单独保证目标产率。

### 原理与依据

过量磷提高酸量但可能破坏孔结构。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 同时看2%改性酸量和孔结构
   - 输入: P₂O₅质量标定与本文催化条件
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 7.pdf · 标题路径：Catalytic fast pyrolysis of polyethylene terephthalate plastic for the selective production of terephthalonitrile under ammonia atmosphere · PDF 第4页 [src-82267ef81808-pdf_page-00004]
  315.7 lmol/g, which was 40% higher than                                     Besides, Entries 2–5 demonstrated the detailed product distri-
c-Al2O3. With the mass ratio increasing from 2% to 8%, the total                               butions of CFP-A of PET over different modified c-Al2O3 catalysts.
acid amounts of modi

## 在固定总流量下比较50%与纯氨

`pet-nitrogen-papers/r32@1.0.0` · material

50%在所测条件接近纯氨，20%时含氧残物增加。

### 解决的问题

500℃兼顾腈形成与避免过裂解；氨比例与接触时间需要满足而不过度。

### 适用场景

希望减少NH₃载气用量

### 使用前提

- PET0.5 g、催化剂1 g和总流160 mL/min

### 限制与不适用情况

- 比例不能脱离总流量和负载使用。

### 原理与依据

50%在所测条件接近纯氨，20%时含氧残物增加。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 在固定总流量下比较50%与纯氨
   - 输入: PET0.5 g、催化剂1 g和总流160 mL/min
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 7.pdf · 标题路径：Catalytic fast pyrolysis of polyethylene terephthalate plastic for the selective production of terephthalonitrile under ammonia atmosphere · PDF 第6页 [src-82267ef81808-pdf_page-00006]
  50% NH3 and 50% N2). Fig. 4 show the overall yield and nitriles                       gas with different content ammonia was investigated in the range
selectivity of CFP-A with different catalyst dosage. In Fig. 4a, the                       of 100–20% by fixing temperature at 500 °C, catalyst amoun

## 在0.6–1.2 g中用1 g的比较窗口

`pet-nitrogen-papers/r33@1.0.0` · material

更多接触不一定增产，还会促进副裂解。

### 解决的问题

500℃兼顾腈形成与避免过裂解；氨比例与接触时间需要满足而不过度。

### 适用场景

改变固定床催化剂量

### 使用前提

- 同温度和进料/气流条件

### 限制与不适用情况

- 仅限所测固定床尺度。

### 原理与依据

更多接触不一定增产，还会促进副裂解。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 在0.6–1.2 g中用1 g的比较窗口
   - 输入: 同温度和进料/气流条件
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 7.pdf · 标题路径：Catalytic fast pyrolysis of polyethylene terephthalate plastic for the selective production of terephthalonitrile under ammonia atmosphere · PDF 第6页 [src-82267ef81808-pdf_page-00006]
  1.0 g, amides and oxygenates disap-                             under 50% ammonia (52.27% and 89.95%), and the difference could
peared. Meanwhile, the carbon yield of nitriles reached the highest,                       be negligible. If ammonia content decreased further, the carbon
and the unidentifi

## 550℃空气3 h烧焦后再测酸量和TPN

`pet-nitrogen-papers/r34@1.0.0` · material

焦去除仍伴随酸位损失，五轮产率下降。

### 解决的问题

500℃兼顾腈形成与避免过裂解；氨比例与接触时间需要满足而不过度。

### 适用场景

再用磷改性催化剂

### 使用前提

- 本文磷改性样品

### 限制与不适用情况

- 不能把再生次数直接当长期寿命。

### 原理与依据

焦去除仍伴随酸位损失，五轮产率下降。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 550℃空气3 h烧焦后再测酸量和TPN
   - 输入: 本文磷改性样品
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 7.pdf · 标题路径：Catalytic fast pyrolysis of polyethylene terephthalate plastic for the selective production of terephthalonitrile under ammonia atmosphere · PDF 第6页 [src-82267ef81808-pdf_page-00006]
  46.01%, respectively, slightly decreased as compared
                                                                                           with the first cycle. Meanwhile, the yield of unidentified carbon
                                                                                           increased from14.67% to 18.02%. The variation on the yield of coke,
                                                                                           gases, and aromatics was not obvious, and kept at around 16%, 10%
                                                                                           a

## 热甲醇溶解后−20℃重结晶

`pet-nitrogen-papers/r35@1.0.0` · material

冷热溶解度差可把TPN从其他组分中分开。

### 解决的问题

甲醇冷热溶解度差支持 TPN 分离，但分析产率到纯产品仍有显著回收损失。

### 适用场景

分离快速热解冷阱中的TPN

### 使用前提

- 原混合物与甲醇分离条件

### 限制与不适用情况

- 分离只回收约60%分析TPN。

### 原理与依据

冷热溶解度差可把TPN从其他组分中分开。

### 效果检查

- 12 h结晶后过滤干燥并检查纯度。

### 执行步骤

1. 热甲醇溶解后−20℃重结晶
   - 输入: 原混合物与甲醇分离条件
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 12 h结晶后过滤干燥并检查纯度。

### 出处与短引文

- 7.pdf · 标题路径：Catalytic fast pyrolysis of polyethylene terephthalate plastic for the selective production of terephthalonitrile under ammonia atmosphere · PDF 第8页 [src-82267ef81808-pdf_page-00008]
  Fig. 7. The schematic diagram of the separation and purification of TPN from the pyrolysis products

## 保留5 mol%作为已验证比较点

`pet-nitrogen-papers/r36@1.0.0` · material

减少PdCl₂负载使TPN产率下降。

### 解决的问题

先把 PET 氨解为对苯二甲酰胺，再由 Pd 催化水转移生成对苯二腈；酰胺完全转化仍可能留下单腈。

### 适用场景

降低原文Pd水转移催化剂负载

### 使用前提

- 模型酰胺与原乙腈/水条件

### 限制与不适用情况

- 不把该负载推广为其他Pd催化体系最优。

### 原理与依据

减少PdCl₂负载使TPN产率下降。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 保留5 mol%作为已验证比较点
   - 输入: 模型酰胺与原乙腈/水条件
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 1.pdf · 标题路径：Upcycling of poly(ethylene terephthalate) waste plastics to terephthalonitrile · PDF 第4页 [src-e62068f57189-pdf_page-00004]
  5 mol%, 6 mg), CH3CN (3 mL),
H2O (3 mL), 100 °C, 18 h. acac: acetylacetonate, hfac: hexaﬂuoroacetylacetonate, dba: dibenzylideneacetone, EG: ethylene glycol, THF: tetrahydro-
furan, DMSO: dimethyl sulfoxide.




   We also found that the reaction is sensit

## 预溶氨时冷却并捕集过量气体，温度不超过所测125℃

`pet-nitrogen-papers/r37@1.0.0` · material

预溶控制暴露，温度选择避免约150℃以上副反应。

### 解决的问题

BHET→HCB→TPD 在 EG 中连续发生，定量必须同时考虑固体与液相；温度改变时氨溶解度也改变。

### 适用场景

按原文准备EG氨解动力学实验

### 使用前提

- 原文实验设施、操作与预饱和介质

### 限制与不适用情况

- 方法卡用于理解文献；本文未验证更高温下模型可迁移。

### 原理与依据

预溶控制暴露，温度选择避免约150℃以上副反应。

### 效果检查

- 目标物与副产物分别定量，保持本篇指标口径。

### 执行步骤

1. 预溶氨时冷却并捕集过量气体，温度不超过所测125℃
   - 输入: 原文实验设施、操作与预饱和介质
   - 产出: 原文限定条件下的中间体、数据或比较结果。
   - 检查: 按本篇定量及条件检查，不将模型或有限试验视为普适保证。

### 出处与短引文

- 4.pdf · 标题路径：Upcycling of Waste Poly(ethylene Terephthalate): Ammonolysis Kinetics of Model Bis(2-Hydroxyethyl Terephthalate) and Particle Size Effects in Polymeric Substrates · PDF 第2页 [src-b1b3021b0f08-pdf_page-00002]
  fume hood. The method for dissolv-                bring each reactor up to the setpoint temperature of 50 °C, 75 °C,
  ing ammonia in EG was based on the procedure outlined by Zhou                 100 °C, or 125 °C. Product mixtures were harvested at intervals of
  et al. and illustrated in Figure 1.[

## 氨解—Pd 水转移串联

`pet-nitrogen-papers/f-tandem@1.0.0` · material

通过酰胺中间体将 PET 芳环转成双腈；两个官能团不保证相同转化程度。

### 解决的问题

先把 PET 氨解为对苯二甲酰胺，再由 Pd 催化水转移生成对苯二腈；酰胺完全转化仍可能留下单腈。

### 适用场景

比较 ≤120℃ PET→TPN 路线

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 模型底物条件与 PET 全流程条件不能混同。

### 原理与依据

通过酰胺中间体将 PET 芳环转成双腈；两个官能团不保证相同转化程度。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 先将 PET 氨解并隔离水洗酰胺。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 将酰胺在 PdCl₂/乙腈/水体系中脱水。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 用 GC 与产品分离分别量化双腈、单腈和回收率。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 1.pdf · 标题路径：Upcycling of poly(ethylene terephthalate) waste plastics to terephthalonitrile · PDF 第1页 [src-e62068f57189-pdf_page-00001]
  tandem process for the transformation of
                                           poly(ethylene terephthalate) (PET) waste into terephthalonitrile under mild conditions (≤120 °C). The
                                           process involves PET ammonolysis with ethylene glycol and ammonia, followed by liquid-phase dehydra-
                                           tion of tere

## 串联中间体兼容性

`pet-nitrogen-papers/f-compat@1.0.0` · material

残氨与 EG 抑制 Pd，洗涤隔离是两段催化剂兼容的条件。

### 解决的问题

氨和残留 EG 会抑制 Pd 脱水；真实原料耐受性与催化剂回收损失共同决定串联流程表现。

### 适用场景

判断能否一锅合并氨解和 Pd 脱水

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 工业设备兼容是设计讨论，未给出商业工厂长期运行。

### 原理与依据

残氨与 EG 抑制 Pd，洗涤隔离是两段催化剂兼容的条件。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 完成氨解后过滤隔离酰胺。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 水洗去除残氨和 EG，再干燥。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 将清洗后的中间体加入脱水段并检查 Pd 黑及产物分布。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 1.pdf · 标题路径：Upcycling of poly(ethylene terephthalate) waste plastics to terephthalonitrile · PDF 第6页 [src-e62068f57189-pdf_page-00006]
  one-pot transformation from PET to
(CH3CN)x(H2O)y(OH)t species, which subsequently condense          terephthalonitrile by combining the ammonolysis and de-
into a dimer (major form) and a tetramer (minor form)             hydration steps were unsuccessful, even when the

## 乙二醇解—冷却结晶

`pet-nitrogen-papers/f-crystal@1.0.0` · material

先生成 BHET，利用温度相关溶解度结晶分离，再氨解得到低溶解度酰胺。

### 解决的问题

PET 先成为 BHET，再成为对苯二甲酰胺；反应和结晶分离共同为下游 Hofmann 重排准备进料。

### 适用场景

分析中间体生成与分离耦合

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 不同真实料条件并不完全相同，不能只按收率排名。

### 原理与依据

先生成 BHET，利用温度相关溶解度结晶分离，再氨解得到低溶解度酰胺。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 以 Zn(OAc)₂/EG 将 PET 转为 BHET。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 冷却至 0℃保持 24 h，少量加水改善晶粒并过滤。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 将 BHET 氨解为 TP，过滤干燥并测纯度。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 11.pdf · 标题路径：Tandem Thermo−electrochemical Strategy for Upcycling Waste Poly(ethylene terephthalate) into Value-Added Aniline Derivatives · PDF 第3页 [src-214fbead528d-pdf_page-00003]
  90.5% with 6-h
and lead to more favorable reaction kinetics.45 For instance,
                                                                             degradation time, 190 °C reaction temperature, 2 wt %
ammonolysis reactions involving BHET proceed with higher
yields and faster rates compared to those utilizing TPA and                  catal

## 三阶段 e-Hofmann 重排

`pet-nitrogen-papers/f-hofmann@1.0.0` · material

活性溴电卤化、加碱重排、热水解脱羧共同产生 PABA 与 PPD。

### 解决的问题

阳极产生活性溴，阴极生成碱；电卤化、碱重排和热水解脱羧共同形成 PABA/PPD。

### 适用场景

理解酰胺到芳环胺的路径

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 电极保护改善效率，不等于已解决所有污染和循环问题。

### 原理与依据

活性溴电卤化、加碱重排、热水解脱羧共同产生 PABA 与 PPD。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 0℃电解，阳极形成活性溴并 N-溴化酰胺。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 加入碱后升至 40℃重排形成异氰酸酯。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 加水升至 100℃水解脱羧，分别定量 PABA/PPD。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 11.pdf · 标题路径：Tandem Thermo−electrochemical Strategy for Upcycling Waste Poly(ethylene terephthalate) into Value-Added Aniline Derivatives · PDF 第5页 [src-214fbead528d-pdf_page-00005]
  first stage, using methanol/water mixtures as the
direct ammonolysis would have difficulty separating TP from                 solvent, H2O or MeOH gets reduced at the cathode,
the partially degraded amide oligomers, and the preparation of              generating hydrogen gas along with

## 功能单位与 cradle-to-gate 边界

`pet-nitrogen-papers/f-lca-boundary@1.0.0` · material

用同等质量 1 kg 聚合物比较收集至聚合的物料、能量与排放。

### 解决的问题

该论文评价的是废 PET 衍生单体制备 Kevlar 聚合物的 cradle-to-gate 模型，首先需要明确功能单位、原料负担和工业放大假设。

### 适用场景

开展 PET→芳纶环境比较

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 未证明纤维成形、强度或商业工厂运行；SI 未上传。

### 原理与依据

用同等质量 1 kg 聚合物比较收集至聚合的物料、能量与排放。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 确定 1 kg 同质量聚合物与北美 cradle-to-gate 范围。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 列出两条单体支路及各段原料、能耗和回收假设。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 按背景数据库与影响方法计算四类指标。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 12.pdf · 标题路径：Life Cycle Assessment of Chemical Upcycling of Postconsumer Polyethylene Terephthalate to Kevlar Polymer · PDF 第3页 [src-42d155ded4e1-pdf_page-00003]
  functional unit for this study is 1 kg of Kevlar                     allocation methodology for open-loop recycling.
production. The system boundary is shown in Figure 1,                          2.3. Upcycled Kevlar. 2.3.1. Mechanical Recycling.
illustrating the chemical upcycling process, starting from

## 开放循环三种分配

`pet-nitrogen-papers/f-allocation@1.0.0` · material

cutoff、50/50 与废物价值法决定前世 PET 环境负担的归属。

### 解决的问题

是否分摊前一世 PET 的负担会改变结果；单体制备的溶剂与试剂是主要优化对象。

### 适用场景

比较开放循环产品的环境结果

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 生态毒性只改善约 1%，不能笼统说所有环境风险大幅下降。

### 原理与依据

cutoff、50/50 与废物价值法决定前世 PET 环境负担的归属。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 按 cutoff 从废料收集开始，不分配前世原生 PET 负担。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 分别应用 50/50 与废物价值价格比分配。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 在同一功能单位下比较各指标变化，不混用分母。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 12.pdf · 标题路径：Life Cycle Assessment of Chemical Upcycling of Postconsumer Polyethylene Terephthalate to Kevlar Polymer · PDF 第3页 [src-42d155ded4e1-pdf_page-00003]
  Cut-Off Approach. The cutoff approach is most                       2.3.2. Depolymerization and Precursor Preparation. Part
commonly applied to avoid double-counting burdens between                   of chemical recycling includes PET polymer being broken
product systems and to avoid assum

## 热点—单因素—组合情景

`pet-nitrogen-papers/f-scenarios@1.0.0` · material

四个热点改进构成 S1–S8，场景结果需保留改动和比较基准。

### 解决的问题

替换碱、减少纯化溶剂和降低过量氯化剂可组合优化，但结果仍来自模型。

### 适用场景

评价降低试剂和纯化溶剂用量的潜力

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 优化情景并非所有参数均已实测达到工业标准。

### 原理与依据

四个热点改进构成 S1–S8，场景结果需保留改动和比较基准。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 从热点中选择碱、氯仿、SOCl₂ 和乙醚四个因素。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 建立四个单因素和 Table 2 的四个组合情景。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 计算相对基线及相对原生路线变化并分别报告。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 12.pdf · 标题路径：Life Cycle Assessment of Chemical Upcycling of Postconsumer Polyethylene Terephthalate to Kevlar Polymer · PDF 第5页 [src-42d155ded4e1-pdf_page-00005]
  s
                                                                   18928                                   https://doi.org/10.1021/acssuschemeng.5c04073
                                                                                                        ACS Sustainable Chem. Eng. 2025, 13, 18924−1893

## Monte Carlo 与敏感性分析

`pet-nitrogen-papers/f-sensitivity@1.0.0` · material

统计输入波动和逐因素扰动揭示结果稳健性及主导假设。

### 解决的问题

溶剂回收率和价格比小幅温度或收率变化更影响该模型；统计范围不消除清单假设的结构性限制。

### 适用场景

理解 LCA 不确定性和优化优先级

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- Monte Carlo 不会证明缺失工厂数据可靠；SI 未提供。

### 原理与依据

统计输入波动和逐因素扰动揭示结果稳健性及主导假设。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 按前景与数据库不确定性进行 1000 次 Monte Carlo。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 分别扰动回收率、价格、收率和温度。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 比较影响变化并保留变动范围与回收附加负担。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 12.pdf · 标题路径：Life Cycle Assessment of Chemical Upcycling of Postconsumer Polyethylene Terephthalate to Kevlar Polymer · PDF 第5页 [src-42d155ded4e1-pdf_page-00005]
  1000 iterations at a 95%
                                                                           equipment and processes.
confidence level to estimate uncertainties.57,58 Given the
                                                                              Preference is given to North American average values62 for
inherent variability and limited data for the emerging upcycling
                                                                           chemicals and so

## 两次脱水与焦化竞争

`pet-nitrogen-papers/f-tio2@1.0.0` · material

TP 经单腈酰胺形成 TPN，过高温度或过长时间增加焦化损失。

### 解决的问题

TiO₂ 催化酰胺到 TPN，但高温或过长时间会把产物损失到焦化。

### 适用场景

选择 TiO₂/乙腈脱水的观察窗口

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 该路线 260℃ 与 Pd 水转移 ≤120℃ 的催化环境不同。

### 原理与依据

TP 经单腈酰胺形成 TPN，过高温度或过长时间增加焦化损失。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 在所测 TiO₂/乙腈体系比较温度、时间和剂量。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 对 TP、单腈和 TPN 分别分析，识别四小时产率峰。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 用反溶剂结晶测分离收率及 HPLC/NMR 纯度。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 2.pdf · 标题路径：Upcycling PET waste into high value-added p-xylylenediamine (PXDA): A route to diversify PET-derived chemicals · PDF 第5页 [src-fac9747cbb51-pdf_page-00005]
  73.1 %. Following the selection            TPN conversion under optimized conditions (Fig. 3e). In three cycles,
of TiO₂ as the optimal TP dehydration catalyst, we systematically eval­             the TPN yield remains above 65 %, demonstrating good reusability of
uated the imp

## TPN 氢化到苄位二胺

`pet-nitrogen-papers/f-pxda@1.0.0` · material

双腈氢化生成两个 CH₂NH₂，保留苄位碳而区别于芳环直接连 NH₂ 的 PPD。

### 解决的问题

高纯 TPN 氢化可制得 PXDA；产物价格与流程经济性不是同一结论。

### 适用场景

区分 PXDA 与 PPD 的产物路线

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- SI 未提供，不能核验全部副产物定量与总收率计算。

### 原理与依据

双腈氢化生成两个 CH₂NH₂，保留苄位碳而区别于芳环直接连 NH₂ 的 PPD。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 以高纯 TPN 在 Pd/C/MeOH 中氢化。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 定量 PXDA 产率与选择性，另列副产物。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 用盐酸盐分离确认产物形式和口径。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 2.pdf · 标题路径：Upcycling PET waste into high value-added p-xylylenediamine (PXDA): A route to diversify PET-derived chemicals · PDF 第6页 [src-fac9747cbb51-pdf_page-00006]
  87.4 % yield over a Pd/C catalyst at 65 ◦ C. An overall PXDA yield of
54.5 % is achieved from PET. Crucially, the successful transformation of              Data will be made available on request.
real post-consumer plastic waste and scale-up experiments demonstrate
the r

## 连续两步拟一级动力学

`pet-nitrogen-papers/f-sequential@1.0.0` · material

过量氨并入 k′，A→B→C 中间体先积累再耗尽。

### 解决的问题

DMT 先形成单酰胺 MCB，再形成 TPD；过量氨下可用两步拟一级模型，但速率不同。

### 适用场景

拟合 DMT→MCB→TPD 的浓度—时间曲线

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- ΔG 和不可逆性属于模型依据与近似。

### 原理与依据

过量氨并入 k′，A→B→C 中间体先积累再耗尽。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 用 NMR 定量各组分并记录实际温度历程。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 在过量氨假设下拟合连续两步模型。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 跨温度拟合 Arrhenius 参数，并检查中间体曲线及残差。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 3.pdf · 标题路径：Upcycling Waste PET: I. Ammonolysis Kinetics of Model Dimethyl Terephthalate and the Catalytic Effects of Ethylene Glycol · PDF 第4页 [src-4833ddff420e-pdf_page-00004]
  pseudo first order rate constants for reaction
are used. The calculated activity coefficients were 5−15% away               step one and step two, respectively.
from unity. Details of the activity calculations are provided in                Differential eqs 3-5 can be solved analytically

## 固液两相 NMR 质量平衡

`pet-nitrogen-papers/f-two-phase@1.0.0` · material

同时分析 EG 液相与固体，避免漏计可溶 BHET/HCB。

### 解决的问题

BHET→HCB→TPD 在 EG 中连续发生，定量必须同时考虑固体与液相；温度改变时氨溶解度也改变。

### 适用场景

定量 BHET 氨解全过程

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 只称最终干粉不足以支持全过程浓度曲线。

### 原理与依据

同时分析 EG 液相与固体，避免漏计可溶 BHET/HCB。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 淬冷取样后分离固液相。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 将液相混入 DMSO-d₆，固体另行溶解并 NMR。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 合并积分得到全样品各物质摩尔分数。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 4.pdf · 标题路径：Upcycling of Waste Poly(ethylene Terephthalate): Ammonolysis Kinetics of Model Bis(2-Hydroxyethyl Terephthalate) and Particle Size Effects in Polymeric Substrates · PDF 第4页 [src-b1b3021b0f08-pdf_page-00004]
  solid samples
  reacting for 45 min at 50 °C, only 0.01 g (1 ppm) of the product is
                                                                                showing the reaction trajectory from BHET through HCB to TPD.
  recovered as a solid. The mass fraction recovered as solids
  steadily increases with time as the reactant is converted

## 有效因子与 Thiele 模数

`pet-nitrogen-papers/f-thiele@1.0.0` · material

用化学基准速率和颗粒几何构建 η–φ 关系，拟合条件依赖的有效扩散。

### 解决的问题

将 BHET 化学速率与 PET 颗粒表观速率比较，可构建有效因子；扩散系数是条件依赖的拟合量。

### 适用场景

分析毫米 PET 颗粒传质

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 球形近似和溶胀介质限制了 D_eff 的可迁移性。

### 原理与依据

用化学基准速率和颗粒几何构建 η–φ 关系，拟合条件依赖的有效扩散。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 比较 PET 酯键消失与 BHET 基准速率得到有效因子。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 使用球形与体积/表面积近似计算 Thiele 模数。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 拟合有效扩散系数并说明温度、EG 溶胀和几何限制。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 4.pdf · 标题路径：Upcycling of Waste Poly(ethylene Terephthalate): Ammonolysis Kinetics of Model Bis(2-Hydroxyethyl Terephthalate) and Particle Size Effects in Polymeric Substrates · PDF 第8页 [src-b1b3021b0f08-pdf_page-00008]
  effectiveness factor and the Thiele
  limiting step Figure 8.                                                         modulus for spheres is expressed by Equation (20).
        The ester conversion rates of PET were compared to the
  ammonolysis rate of BHET at 100 °C to assess the effects of mass                      3
                                                                                  η¼       ðϕ cothðϕÞ  1Þ                                                (20)
  transfer lim

## 无水氨气固氨解

`pet-nitrogen-papers/f-gas-solid@1.0.0` · material

无外加催化剂和反应溶剂条件下形成酰胺，延时碳化与纯度提升竞争。

### 解决的问题

无水氨与 PET 气固反应可生成酰胺；多种表征共同确认身份，纯度和产率仍独立。

### 适用场景

分析简化氨解流程的相态和指标

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 特定厚度、负载和釜条件下的证据。

### 原理与依据

无外加催化剂和反应溶剂条件下形成酰胺，延时碳化与纯度提升竞争。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 按原文无水氨/PET 釜条件开展气固反应。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 反应后洗涤、过滤和干燥，保留洗液用于产物分析。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. HPLC 分别计算纯度与摩尔收率，结合多种表征确认身份。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 5.pdf · 标题路径：Valorization of polyethylene terephthalate wastes to terephthalamide via catalyst-free ammonolysis · PDF 第3页 [src-484e6d8b37d7-pdf_page-00003]
  0.85 ± 0.05 MPa at 25 ◦ C. The reaction was con­
                                                                                       functional groups of TP standard, PET flakes, and the ammonolysis
ducted at given temperatures in a range of 40 to 140 ◦ C with reaction
                                                                                       powders, provided insightful distinctions (Fig. 3). The absorption peak
tim

## Box–Behnken 响应面设计

`pet-nitrogen-papers/f-bbd@1.0.0` · material

三因素二次模型在试验范围内优化，需近似独立验证及物理约束检查。

### 解决的问题

三因素响应面可以描述试验范围内的产率和纯度变化，但预测纯度超出物理上限说明模型并未施加约束。

### 适用场景

比较时间、温度与投料量对响应的影响

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 显著性标记和表头存在问题；不能当作规范统计教学模板。

### 原理与依据

三因素二次模型在试验范围内优化，需近似独立验证及物理约束检查。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 按三因素范围完成 15 组 BBD 运行。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 分别拟合产率与变换纯度并检查 ANOVA 与残差。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 在近似最优条件重复验证，同时检查纯度上限。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 5.pdf · 标题路径：Valorization of polyethylene terephthalate wastes to terephthalamide via catalyst-free ammonolysis · PDF 第3页 [src-484e6d8b37d7-pdf_page-00003]
  Box-Behnken optimization design
PET bottles, Sprite bottles, PET textiles and PET headgear was 0.04 %,
                                                                                          Response surface methodology (RSM) was employed to optimize
0.03 %, 0.12 % and 0.43 %, respectively. The bottles and products un­
                                                                                       experimental param

## 分布活化能模型 DAEM

`pet-nitrogen-papers/f-daem@1.0.0` · material

多种独立一阶反应的连续 Ea 分布描述整体 TG，不是单步分子势垒。

### 解决的问题

尿素与 PET 共热解出现协同降解；分布活化能模型描述复杂质量损失，不是某一步分子反应的本征能垒。

### 适用场景

分析 PET/尿素共热解协同

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 式(6)转换量符号值得核对，不作为未经修正的标准计算式。

### 原理与依据

多种独立一阶反应的连续 Ea 分布描述整体 TG，不是单步分子势垒。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 采集三个升温速率的 TG/DTG。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 与无相互作用加权曲线比较，并在 DAEM 假设下拟合。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 报告活化能分布/平均值，区别于单步本征 Ea。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 6.pdf · 标题路径：Valorization of waste PET: Understanding the role of active ammonia in facilitating PET depolymerization and aromatic nitrile formation · PDF 第2页 [src-4fda33930eaf-pdf_page-00002]
  first-order reaction conditions, driving researchers to search for more           2.3. Kinetic analysis
precise fitting models. Osman et al. (2020) successfully applied the
differential iso-conversion method to calculate kinetic parameters for               The kinetic analysi

## 气氛—温度—接触时间窗口

`pet-nitrogen-papers/f-pyro-window@1.0.0` · material

适量氨与合适固定床接触在腈形成和过裂解之间取得平衡。

### 解决的问题

500℃兼顾腈形成与避免过裂解；氨比例与接触时间需要满足而不过度。

### 适用场景

比较 NH₃ 快速热解操作变量

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 有限循环不等于长期金属/酸位完全稳定。

### 原理与依据

适量氨与合适固定床接触在腈形成和过裂解之间取得平衡。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 固定 PET 进料与总气流量，比较温度、催化剂量和 NH₃ 比例。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 分别测腈碳产率、TPN 选择性、气焦与未识别碳。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 再生后重复并报告活性损失，不把筛选点当作尺度无关条件。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 7.pdf · 标题路径：Catalytic fast pyrolysis of polyethylene terephthalate plastic for the selective production of terephthalonitrile under ammonia atmosphere · PDF 第5页 [src-82267ef81808-pdf_page-00005]
  500 °C; N2 and NH3 flow rate, 80 mL/min; PET fed in 0.5 g/batch.
 b
   Nitriles: TPN, benzonitrile, acetonitrile and other alkyl aromatic nitriles.
 c
   Aromatics: benzene, toluene, xylenes, biphenyl, naphthalene, etc.
 d
   Amides: benzamide, terephthalamide

## 冷热溶解度差重结晶

`pet-nitrogen-papers/f-recrystal@1.0.0` · material

热甲醇溶解和低温结晶提高 TPN 纯度，但回收只有部分分析产物。

### 解决的问题

甲醇冷热溶解度差支持 TPN 分离，但分析产率到纯产品仍有显著回收损失。

### 适用场景

解释分析收率到分离产品的损失

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 甲醇使用与冷却能耗没有完整 LCA。

### 原理与依据

热甲醇溶解和低温结晶提高 TPN 纯度，但回收只有部分分析产物。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 将冷阱混合物热甲醇溶解。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. −20℃静置结晶 12 h，过滤干燥。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 用 NMR 确认纯度并独立计算分离碳收率和回收率。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 7.pdf · 标题路径：Catalytic fast pyrolysis of polyethylene terephthalate plastic for the selective production of terephthalonitrile under ammonia atmosphere · PDF 第8页 [src-82267ef81808-pdf_page-00008]
  Fig. 7. The schematic diagram of the separation and purification of TPN from the pyrolysis products

## SEM 形貌时间序列

`pet-nitrogen-papers/f-sem@1.0.0` · material

对比有/无催化及甲胺/氨条件的表面变化，不能以图像替代整体转化和纯度。

### 解决的问题

氨与甲胺都可断 PET 酯键，但生成酰胺结构不同；称量、机理图和形貌不能相互替代。

### 适用场景

解释氨解/胺解形貌证据

### 使用前提

- 本篇原料、介质、装置或模型输入条件；不能把原文参数当作任意体系的通用值。

### 限制与不适用情况

- 文中镀金厚度单位可疑，不用作标准 SEM 配方。

### 原理与依据

对比有/无催化及甲胺/氨条件的表面变化，不能以图像替代整体转化和纯度。

### 效果检查

- 本单元所列条件、定量和分离指标一致；没有普适成功保证。

### 执行步骤

1. 保持各处理的原料与取样时间可比较。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
2. 用 SEM 观察裂缝、层片、棒状残留和晶/非晶选择性。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。
3. 将形貌与称量分别报告，标明不可分离残片及机理推测边界。
   - 输入: 原文规定的进料或数据及适用条件。
   - 产出: 相应中间体、定量结果或模型比较。
   - 检查: 与本单元各项实验或模型口径核对，保留误差与证据边界。

### 出处与短引文

- 9.pdf · 标题路径：Scanning electron microscopic study of hazardous waste flakes of polyethylene terephthalate (PET) by aminolysis and ammonolysis · PDF 第1页 [src-b9d9a37600fe-pdf_page-00001]
  methylamine and aqueous
Received 7 September 2009                                   ammonia, respectively at room temperature in the presence and absence of quaternary ammonium salt as
Received in revised form 15 January 2010                    a catalyst for different periods of time. The aminolysed and ammonol
