# 第二轮正文修改清单（对应 `Development_and_internal_validation_macrosomia_clean.md`）

所有新增或改写的文字都用 `<span style="color:red">` 标成红色；删除的文字直接去掉，不留痕迹。

## 按章节列出的修改

| 位置 | 修改内容 | 对应意见 |
|---|---|---|
| 首页 | 表格数改为 3；正文图改为 4；补充表改为 14；补充图改为 7；字数重新统计 | — |
| What this study adds | 删去 "clinically useful"，改为"内部验证中具有中等判别力"，并补一句"需外部验证" | 编辑第 3 点；审稿人 clinical usefulness |
| 摘要 Methods | 删去 fetal sex | 编辑第 1 点；审稿人 leakage |
| 摘要 Results | AUROC 0.75 改为 0.74；删去 "comparable to WHO"，改为"M1 为 0.64/0.73，低于最强的 Visit 3 WHO 指标" | 编辑第 3 点；审稿人 comparability |
| 摘要 Conclusion | 加 "in internal validation" | 编辑第 3 点 |
| 2.1 | 说明四个模型都在同一分析队列中开发和评估；引用 Table 2 | 编辑第 1、3 点 |
| 2.2 | 补 INTERGROWTH-21st newborn 文献 [20]（阈值 > 与 ≥ 的问题在回复信中说明，正文不另加句子） | 审稿人 minor（阈值、文献） |
| 2.3 | 删去 gravidity 和 fetal sex；补全 Visit 1 的测量项目；说明不纳入 fetal sex 和 GDM 的理由；列出 25 个饮食变量；补 Visit 3 的 AFI 四个象限和 EFW 百分位；说明 Visit 2 EFW 百分位和 Doppler 未纳入；补变量编码方式；引用 Table 2 | 编辑第 1 点；审稿人 predictor reporting、leakage |
| 2.4 | 说明与 WHO 的比较是描述性的，不做检验；补 INTERGROWTH fetal 文献 [28,29]；说明 Visit 2 EFW 百分位只适用于 18 周以后 | 编辑第 2 点；审稿人 Mann–Whitney、S11 |
| 2.5 第 1 段 | 按 42/51/56/65 重写模型定义（M3 = M1 + Visit 3）；说明 M1 的评估人群 | 编辑第 1、3 点 |
| 2.5 第 2–3 段 | **【作者复核】**我按 `revision_status.md` 起草了验证流程：elastic net（C=0.1，l1_ratio=0.3）；100 次重复 10 折；按受试者平均预测；1,000 次受试者 bootstrap；配对 bootstrap；类别权重 1:5 和 1:10；Platt 校准；单次完整 10 折；isotonic 作敏感性分析。请用你写的 2.5 节替换或逐句核对 | 编辑第 2 点；审稿人 validation pipeline |
| 2.5 第 4 段 | 补 scaled Brier、CITL、O/E；"prespecified thresholds" 改为 "fixed risk strata"；补 DCA 的方法描述，并说明未定义具体干预 | 审稿人 calibration、DCA、prespecified |
| 2.5 第 5–6 段 | 说明总分与组分同时入模，系数不能作为独立效应解释；说明消融分析是探索性的；LGA 的 CI 按上文方法计算 | 审稿人 predictor reporting |
| 2.6 | 按 Riley 报告候选变量数和每个变量对应的事件数（>4000 g 为 7.8–12.0，>4500 g 为 1.2–1.8）；描述复杂度分析的方法；表述 FDR 用 q<0.05；新增 MMC 有限评估的方法段 [33] | 编辑第 3、4 点；审稿人 77 events、external evaluation |
| 3.2 | 替换全部 AUROC 数字；删去 p<0.001，改报配对 ΔAUROC；删去 WHO 平均值和 "comparable/inferior"；表号改为 Table 3；补 >4500 g 的 CI 较宽的说明；补 IG Visit 2 EFW（3,834 例）；替换 AUPRC 和校准结果（Platt、scaled Brier）；替换阈值分析数字；DCA 改为纯描述；新增复杂度分析结果段；LGA 数字和 "Model 1/Model 3" 写法；新增 MMC 结果段 | 编辑第 2、3、4 点；审稿人多条 |
| 3.4 | 消融图改为 Supplementary Figures S6/S7；"negative-control-type" 改为 "additional sensitivity analysis"；补一句"假设生成性质、不用于支撑预测结论" | 审稿人 alcohol |
| 4.1 | "meaningful" 改为 "moderate discrimination … during internal validation"；重写与 WHO 比较的段落 | 编辑第 3 点 |
| 4.2 | 酒精段：补"涉及多个饮食组分"；说明胎龄类结局不是严格的阴性对照 | 审稿人 alcohol |
| 4.3 | 替换阈值数字；"prespecified" 改为 "fixed"；补一句"阈值分析和 DCA 都不能确立临床效用" | 编辑第 3 点 |
| 4.4 | MMC 段改为降级表述；补 M1 人群选择的限定；补 >4500 g 只有 77 例事件的限定 | 编辑第 3、4 点 |
| 5 结论 | "clinically meaningful" 改为 "moderate discrimination … in internal validation" | 编辑第 3 点 |
| Declarations | 伦理部分补 MMC；数据可得性部分补 MMC | 审稿人 ethics/data governance |
| 参考文献 | 新增 [20] Villar 2014、[28] Papageorghiou 2014、[29] Stirnemann 2020、[33] Wu 2024；其后按首次引用顺序重排编号；删去重复的 "[29]" | 审稿人 minor |
| 图注 | Figures 1–3 删去 grade 对照句；Figure 4 改为 "≤4000 g"；原 Figures 5–6 移出正文（改为 S6/S7） | 审稿人 figures |
| Table 1 | 标题、表头和表注中 "<4000 g" 改为 "≤4000 g"；表注说明显著性依据 q 值 | 审稿人 Table 1 |
| Table 2（新增） | 模型定义表：变量组、具体变量、获取时间、各模型是否纳入、变量总数；表注列出 25 个饮食组分及未纳入的变量 | 编辑第 1 点 |
| Table 3（原 Table 2） | 删去两行平均值、a/b/c 上标和 Mann–Whitney 脚注；新增"仅作描述性比较"的表注和缩写说明 | 编辑第 2 点 |

## 仍待处理的占位与确认事项

1. **Combined − M3（>4500 g）的 CI "−0.001 to 0.004"**：暂用，待重跑后替换（3.2 节，附近有 HTML 注释标记）。
2. **3.2 节非线性模型一句**：S9 重算后核对（有 HTML 注释标记）。
3. **2.5 节验证流程**：用作者的定稿替换，或逐句核对。特别要确认 "Platt calibrator was fitted within the training folds only" 的具体做法（主分析是否也用内层 CV 预测拟合）。
4. **字数**：暂写 5980，需在 Word 中重新统计。比上一版约多 1,600 词，要确认期刊字数上限。
5. **Visit 3 的 EFW**：是按 Hadlock 公式计算，还是 nuMoM2b 报告值？S10 旧稿写的是 "as reported"。
6. **变量编码**："All predictors were entered as continuous or binary variables without further transformation" 需确认。
7. **MMC 伦理措辞**："approved … which waived the requirement for informed consent" 需确认。
8. **Stirnemann 2020 的卷期页**（UOG 56:946–948）：引用前核对。
9. **图的原图**：Figure 4 和新的 Supplementary Figures S6/S7 图中仍有 grade 标签，需改原图；原 Figure 6 中 "p<0.05" 标记的检验方法需在图注中说明，或从图中删去。
10. **补充材料需同步修改**：Δ 表放入 S5；新增 S14（复杂度分析）；S6/S7 的图注；S3 和 Supplementary Methods 中删去 Mann–Whitney；S4、S5、S8、S10、S11、S13、TRIPOD 表按 `revision_status.md` 更新。

