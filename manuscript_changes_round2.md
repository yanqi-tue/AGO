# 第二轮正文修改清单（对应 `Development_and_internal_validation_macrosomia_clean.md`）

所有新增或改写的文字都用 `<span style="color:red">` 标成红色；删除的文字直接去掉，不留痕迹。

## 按章节列出的修改

| 位置 | 修改内容 | 对应意见 |
|---|---|---|
| 首页 | 表格数改为 3；正文图改为 4；补充表改为 14；补充图改为 7；字数重新统计 | — |
| What this study adds | 只把 "can already provide clinically useful" 改为 "provided moderate" | 编辑第 3 点 |
| 摘要 Methods | 删去 fetal sex | 编辑第 1 点 |
| 摘要 Results | 0.75 改为 0.74；"comparable to" 改为 "moderate discrimination (0.64 and 0.73), although lower than the strongest third-trimester …" | 编辑第 3 点；审稿人 comparability |
| 2.1 | "Table 1" 后加 "and Table 2" | 编辑第 1 点 |
| 2.2 | 补 INTERGROWTH-21st newborn 文献 [20]（阈值 > 与 ≥ 的问题只在回复信中说明） | 审稿人 minor |
| 2.3 | 删去 gravidity 和 fetal sex；Visit 1 补 GWG；一句话说明 fetal sex 和 GDM 不作为预测变量；一句话说明两个指数的组分和总分都进入模型；Visit 3 补 AFI 四个象限和 EFW 百分位；Doppler 一句去掉 "from Visit 1"；一句话说明变量编码，并引用 Table 2 | 编辑第 1 点；审稿人 predictor reporting、leakage |
| 2.4 | 补"与模型的比较为描述性"；补 INTERGROWTH fetal 文献 [28,29]；一句话说明 Visit 2 EFW 百分位只适用于 18 周以后 | 编辑第 2 点；审稿人 Mann–Whitney、S11 |
| 2.5 第 1 段 | 保留原句式，只改三处：Model 3 改为 "extended Model 1"；Combined 改为 "Visit 1、2、3 全部信息"；各模型补变量数；末尾补一句"四个模型在同一队列中开发和评估，以便直接比较" | 编辑第 1 点 |
| 2.5 第 2–3 段 | 保留原句（1000 次重复；训练数据内调参；平方根类别权重）；新增：受试者层面平均预测、受试者层面 bootstrap、配对 bootstrap；isotonic 改为 Platt（在训练折内拟合），校准、阈值和 DCA 基于单次完整 10 折；isotonic 作敏感性分析 | 编辑第 2 点；审稿人 Comment 3、5 |
| 2.5 第 4 段 | 补 scaled Brier、CITL、O/E；"prespecified risk-stratification thresholds" 改为 "fixed risk strata"；补一句"另做了 DCA" | 审稿人 calibration、prespecified |
| 2.5 第 5–6 段 | 一句话说明总分与组分同时入模，饮食系数不能作为独立效应解释；LGA 的 CI 改为"按上文方法计算" | 审稿人 predictor reporting |
| 2.6 | 按 Riley 报告候选变量数和每个变量对应的事件数；复杂度分析的方法；"(q<0.05)"；MMC 有限评估的方法（两句） | 编辑第 3、4 点；审稿人 77 events、external evaluation |
| 3.2 | 替换全部数字；删去 p<0.001，改报配对 ΔAUROC；补一句"M1 的估计来自完整随访到 Visit 3 的队列"；删去 WHO 平均值和 "comparable/inferior"，改为 "lower than Model 3 and the Combined model"，另补 "However, Model 1 showed lower discrimination than the stronger Visit-3 WHO-derived percentiles"；表号改为 Table 3；AUPRC 和校准结果（Platt、scaled Brier）；阈值分析数字；DCA 一句改为"illustrate model behavior … rather than to establish clinical utility or define …"；新增复杂度分析结果段；LGA 数字；新增 MMC 结果段 | 编辑第 2、3、4 点；审稿人多条 |
| 3.4 | 消融图改为 Supplementary Figures S6/S7；"the exploratory" 改为 "this exploratory"；"negative-control-type sensitivity analysis" 改为 "additional sensitivity analysis" | 审稿人 alcohol |
| 4.1 | "meaningful" 改为 "moderate"；重写与 WHO 比较的一段（M1 低于较强的 Visit 3 WHO 指标，但可提前数月获得；增量主要来自 Visit 3） | 编辑第 3 点 |
| 4.2 | 酒精段：补 "which involved many dietary components"；说明胎龄类结局不是严格的阴性对照 | 审稿人 alcohol |
| 4.3 | 替换阈值数字；"prespecified" 改为 "fixed"；补一句"阈值分析和 DCA 都不能确立临床效用" | 编辑第 3 点 |
| 4.4 | MMC 段改为降级表述；补 M1 人群选择的限定；补 >4500 g 只有 77 例事件的限定 | 编辑第 3、4 点 |
| 5 结论 | "clinically meaningful" 改为 "moderate" | 编辑第 3 点 |
| Declarations | 伦理部分补 MMC；数据可得性部分补 MMC | 审稿人 ethics/data governance |
| 参考文献 | 新增 [20]、[28]、[29]、[33]；其后编号重排；删去重复的 "[29]" | 审稿人 minor |
| 图注 | Figures 1–3 删去 grade 对照句；Figure 4 改为 "≤4000 g"；原 Figures 5–6 移出正文（改为 S6/S7） | 审稿人 figures |
| Table 1 | "<4000 g" 改为 "≤4000 g"；表注说明显著性依据 q 值 | 审稿人 Table 1 |
| Table 2（新增） | 模型定义表；表注列出饮食组分及未纳入的变量 | 编辑第 1 点 |
| Table 3（原 Table 2） | 删去平均值行、a/b/c 上标和 Mann–Whitney 脚注；表注改为"仅作描述性比较"，并补缩写说明 | 编辑第 2 点 |

## 精简原则（第二遍检查后）

- 正文只改必要的词或句，尽量保留原句式；详细解释放在回复信里。
- 同一信息在正文中只出现一次或两次（方法和结果，或结果和局限），不再多处重复：
  - M1 的人群限定：3.2 和 4.4；
  - >4500 g 需谨慎解读：2.6 和 4.4；
  - 阈值和 DCA 不能确立临床效用：3.2 和 4.3；
  - Visit 2 IG EFW 只适用于 18 周以后：2.4 和 S11 表注（3.2 中已删）。
- 已删除的冗余句：2.1 "all four models … common cohort"；2.3 中 Visit 2 EFW 百分位、围度逐项列举、fetal sex 的长解释；2.5 "strata … do not represent …"和 "ablation was exploratory"；2.6 MMC 中 "does not constitute external validation"（保留在 4.4）；3.2 "Given the 77 events …" 和 IG Visit 2 EFW 数字；3.4 "hypothesis-generating"（4.2 已写）；4.4 MMC 段末重复的外部验证句；摘要结论、4.1 和结论中的 "in internal validation"；Table 2 表注中的标准化说明（方法已写）。

## 仍待处理的占位与确认事项

1. **Combined − M3（>4500 g）的 CI "−0.001 to 0.004"**：暂用，待重跑后替换（3.2 节，附近有 HTML 注释标记）。
2. **3.2 节非线性模型一句**：S9 重算后核对（有 HTML 注释标记）。
3. **2.5 节验证流程**：用作者的定稿替换，或逐句核对。特别要确认 "Platt calibrator was fitted within the training folds only" 的具体做法（主分析是否也用内层 CV 预测拟合）。
4. **字数**：暂写 5620（按原口径粗算为 5,625，上一版同口径约 4,345），需在 Word 中重新统计，并确认期刊字数上限。
5. **Visit 3 的 EFW**：是按 Hadlock 公式计算，还是 nuMoM2b 报告值？S10 旧稿写的是 "as reported"。
6. **变量编码**："All predictors were entered as continuous or binary variables without further transformation" 需确认。
7. **MMC 伦理措辞**："approved … which waived the requirement for informed consent" 需确认。
8. **Stirnemann 2020 的卷期页**（UOG 56:946–948）：引用前核对。
9. **图的原图**：Figure 4 和新的 Supplementary Figures S6/S7 图中仍有 grade 标签，需改原图；原 Figure 6 中 "p<0.05" 标记的检验方法需在图注中说明，或从图中删去。
10. **补充材料需同步修改**：Δ 表放入 S5；新增 S14（复杂度分析）；S6/S7 的图注；S3 和 Supplementary Methods 中删去 Mann–Whitney；S4、S5、S8、S10、S11、S13、TRIPOD 表按 `revision_status.md` 更新。

