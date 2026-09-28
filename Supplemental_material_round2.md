<!--
说明：
1. 本文件只写出本轮需要修改或新增的内容；标注"【无改动，沿用原稿】"的部分请直接保留原 Word 中的内容。
2. 新增或改写的文字用红色标出。整表更新的表格，只在表题处标红并注明 "Revised" 或 "New"，在 Word 中整表改为红色即可。
3. 标注【待补】【待确认】的地方需作者提供或确认，最终版中不能保留。
-->

# Supplemental Materials

## Supplementary Methods: Derivation of WHO fetal growth chart–based percentile variables

For each pregnancy with an available ultrasound examination at Visit 2 or Visit 3, gestational age at scan and one fetal biometric measurement were mapped to the World Health Organization fetal growth chart to obtain a gestational-age-specific percentile. The biometric inputs included head circumference, biparietal diameter, abdominal circumference, femur length, and estimated fetal weight. Estimated fetal weight was first calculated from ultrasound biometry using the Hadlock formula and then converted into a WHO chart–based percentile. Percentiles were computed separately for Visit 2 and Visit 3. Accordingly, five WHO-derived percentile variables were generated at Visit 2 and five additional variables were generated at Visit 3. Variable names followed the format WHO-[biometric variable]-[visit], where the suffix "2" denotes Visit 2 and the suffix "3" denotes Visit 3. For example, WHO-EFW-2 represents the percentile derived from estimated fetal weight and gestational age at Visit 2, whereas WHO-AC-3 represents the percentile derived from abdominal circumference and gestational age at Visit 3.

All WHO-derived percentile variables were evaluated as ultrasound-based benchmark predictors in the comparison with the logistic regression models. Their discriminative performance was summarized as area under the receiver operating characteristic curve values in Table <span style="color:red">3</span> of the main manuscript. <span style="color:red">These values are presented for descriptive comparison with the prediction models; no statistical tests were performed between the chart-based comparators and the prediction models.</span> The estimated fetal weight percentile was additionally emphasized in the narrative interpretation because it most closely reflects routine clinical assessment of fetal overgrowth.

<!-- 已删除原句："In addition, mean AUC values across the five WHO-derived percentiles at each visit were used for statistical comparison with the M1, M2, and M3 logistic regression models using the Mann–Whitney U test across repeated cross-validation runs, as described in the main Methods section." -->

---

## Figure S1. Precision–recall (PR) curves for macrosomia prediction.

(a) >4000 g (prevalence 8%). (b) >4500 g (prevalence 1%). <span style="color:red">Curves were computed from participant-level out-of-fold predictions, averaged for each participant across the repeated runs of stratified 10-fold cross-validation.</span> Models: <span style="color:red">Model 1 (Visit 1), Model 2 (Model 1 + Visit 2), Model 3 (Model 1 + Visit 3), and the Combined model (Visits 1–3); the predictors in each model are listed in Table 2 of the main manuscript.</span> AUPRC (area under the precision–recall curve) values by model: >4000 g—M1 <span style="color:red">0.12</span>, M2 0.14, M3 0.20, Combined 0.21; >4500 g—M1 0.03, M2 <span style="color:red">0.04</span>, M3 <span style="color:red">0.07</span>, Combined 0.07.

## Figure S2. Calibration plots for macrosomia prediction.

(a) >4000 g. (b) >4500 g. <span style="color:red">Calibration plots are based on Platt-recalibrated out-of-fold predicted probabilities from one complete run of stratified 10-fold cross-validation, in which the Platt calibrator was fitted within the training folds only; each participant contributes one prediction.</span> Models: <span style="color:red">Model 1 (Visit 1), Model 2 (Model 1 + Visit 2), Model 3 (Model 1 + Visit 3), and the Combined model (Visits 1–3).</span> Brier scores (a): M1 <span style="color:red">0.0721</span>, M2 <span style="color:red">0.0716</span>, M3 <span style="color:red">0.0686</span>, Combined <span style="color:red">0.0687</span>. Brier scores (b): M1 <span style="color:red">0.0119</span>, M2 <span style="color:red">0.0119</span>, M3 <span style="color:red">0.0116</span>, Combined <span style="color:red">0.0116</span>.

## Figure S3. Calibration plots for LGA sensitivity outcomes.

Calibration plots were generated from <span style="color:red">Platt-recalibrated out-of-fold predicted probabilities from one complete run of stratified 10-fold cross-validation, in which the Platt calibrator was fitted within the training folds only</span>. Each point represents one predicted-risk block, plotted as the mean predicted probability against the observed event rate. The dashed diagonal line indicates perfect calibration. Panels show sensitivity outcomes defined as birthweight above the INTERGROWTH-21st gestational-age- and sex-specific (a) 90th percentile and (b) 97th percentile. Model 1, Model 2, Model 3, and the Combined model are shown separately.

## Supplementary Figure S4. Participant flow for derivation of the analytic cohort.

【无改动，沿用原稿（图与图注）】

## Supplementary Figure S5. Decision curve analysis for primary macrosomia outcomes.

Decision curve analysis was performed using <span style="color:red">Platt-recalibrated out-of-fold predicted probabilities from one complete run of stratified 10-fold cross-validation</span>. Net benefit was calculated across threshold-probability ranges and compared with treat-all and treat-none reference strategies. Panels show decision curves for (a) birthweight >4000 g and (b) birthweight >4500 g. Because birthweight >4500 g was rare, a lower threshold-probability range was used for this outcome. <span style="color:red">The curves are intended to illustrate model behavior rather than to establish clinical utility or define recommended intervention thresholds, because no specific clinical intervention or harm–benefit trade-off was defined.</span>

## <span style="color:red">Supplementary Figure S6. Change in area under the receiver operating characteristic curve after sequential removal of individual periconceptional diet components from Model 1 for prediction of birthweight >4000 g.</span>

<span style="color:red">(Previously Figure 5 of the main manuscript.)</span> Values are presented as mean and standard deviation across cross-validation runs, with standard deviation shown as error bars. <span style="color:red">This ablation analysis was exploratory.</span>

## <span style="color:red">Supplementary Figure S7. Change in area under the receiver operating characteristic curve after sequential removal of individual periconceptional diet components from Model 1 for prediction of birthweight >4500 g.</span>

<span style="color:red">(Previously Figure 6 of the main manuscript.)</span> Values are presented as mean and standard deviation across cross-validation runs, with standard deviation shown as error bars. <span style="color:red">This ablation analysis was exploratory.</span><!-- 原图中的显著性标记已删除（需在图上同步删去） -->

---

## Table S1. Univariate associations for macrosomia >4000 g.

【无改动，沿用原稿】

## Table S2. Univariate associations for macrosomia >4500 g.

【无改动，沿用原稿】

## Supplementary Table S3. Definition and analytical role of WHO fetal growth chart–based percentile variables.

【表格正文沿用原稿，只改两处】
- "Role in analysis" 一列中的 "Included in Table 2 benchmark comparison" 全部改为 "Included in Table <span style="color:red">3</span> benchmark comparison"。
- 表注最后一句 "Average AUC values across the five WHO-derived variables at each visit were additionally compared with the AUC distributions of M1, M2, and M3, as indicated in the Table 2 footnotes." 改为：

Note: Estimated fetal weight was calculated using the Hadlock formula, and WHO growth-chart percentiles were assigned according to gestational age and the corresponding ultrasound-derived fetal biometric measurement. All 10 WHO-derived percentile variables were evaluated in the benchmark comparison reported in Table <span style="color:red">3</span>. <span style="color:red">These comparisons are descriptive.</span>

## <span style="color:red">Supplementary Table S4. Discrimination and calibration of the prediction models for LGA sensitivity outcomes (Revised).</span>

| Outcome | Model | Event rate | AUROC (95% CI) | AUPRC (95% CI) | Brier score | Scaled Brier score | Calibration intercept | Calibration slope | CITL | O/E |
|---|---|---:|---|---|---:|---:|---:|---:|---:|---:|
| LGA90 | Model 1 | 20.7% | 0.620 (0.604–0.637) | 0.285 (0.266–0.305) | 0.1598 | 2.7% | −0.005 | 0.997 | −0.001 | 0.999 |
| LGA90 | Model 2 | 20.7% | 0.654 (0.638–0.670) | 0.323 (0.300–0.347) | 0.1563 | 4.8% | 0.001 | 1.002 | −0.001 | 0.999 |
| LGA90 | Model 3 | 20.7% | 0.731 (0.716–0.745) | 0.414 (0.388–0.441) | 0.1454 | 11.4% | −0.010 | 0.993 | −0.003 | 0.998 |
| LGA90 | Combined model | 20.7% | 0.733 (0.719–0.748) | 0.419 (0.393–0.447) | 0.1448 | 11.8% | −0.008 | 0.995 | −0.003 | 0.998 |
| LGA97 | Model 1 | 7.4% | 0.651 (0.626–0.675) | 0.131 (0.113–0.153) | 0.0670 | 2.0% | −0.022 | 0.992 | −0.002 | 0.998 |
| LGA97 | Model 2 | 7.4% | 0.674 (0.648–0.698) | 0.152 (0.131–0.179) | 0.0662 | 3.2% | 0.014 | 1.007 | −0.002 | 0.998 |
| LGA97 | Model 3 | 7.4% | 0.758 (0.734–0.780) | 0.224 (0.191–0.259) | 0.0631 | 7.7% | −0.034 | 0.987 | −0.006 | 0.995 |
| LGA97 | Combined model | 7.4% | 0.759 (0.736–0.780) | 0.228 (0.194–0.265) | 0.0629 | 7.9% | −0.024 | 0.992 | −0.006 | 0.995 |

<span style="color:red">Table note: LGA sensitivity outcomes were defined using INTERGROWTH-21st birthweight centiles according to gestational age at delivery and neonatal sex. AUROC and AUPRC were calculated from out-of-fold predictions averaged for each participant across repeated stratified 10-fold cross-validation; 95% confidence intervals were obtained from 1,000 bootstrap resamples of participants. AUPRC was calculated as the area under the precision–recall curve using the trapezoidal rule. Calibration measures were calculated from Platt-recalibrated out-of-fold predictions from one complete run of stratified 10-fold cross-validation, in which each participant had one prediction. The scaled Brier score is one minus the ratio of the Brier score to that of a null model assigning the observed prevalence to all participants (null Brier score 0.1642 for LGA90 and 0.0683 for LGA97); it was calculated from unrounded values. The calibration intercept and slope were estimated by regressing the outcome on the logit of the predicted probability; calibration-in-the-large (CITL) is the intercept with the slope fixed at 1. 【待确认：截距和 CITL 的计算定义】 AUROC: area under the receiver operating characteristic curve; AUPRC: area under the precision–recall curve; CI: confidence interval; LGA: large for gestational age; O/E: observed-to-expected ratio.</span>

## <span style="color:red">Supplementary Table S5. Discrimination and calibration of the prediction models for the primary macrosomia outcomes (Revised).</span>

<span style="color:red">(a) Discrimination and calibration</span>

| Outcome | Model | Event rate | AUROC (95% CI) | AUPRC (95% CI) | Brier score | Scaled Brier score | Calibration intercept | Calibration slope | CITL | O/E |
|---|---|---:|---|---|---:|---:|---:|---:|---:|---:|
| Birthweight >4000 g | Model 1 | 7.9% | 0.638 (0.612–0.661) | 0.120 (0.106–0.139) | 0.0721 | 1.2% | 0.017 | 1.007 | −0.001 | 0.999 |
| Birthweight >4000 g | Model 2 | 7.9% | 0.661 (0.635–0.684) | 0.136 (0.119–0.159) | 0.0716 | 2.1% | 0.039 | 1.017 | −0.001 | 0.999 |
| Birthweight >4000 g | Model 3 | 7.9% | 0.743 (0.719–0.765) | 0.200 (0.176–0.233) | 0.0686 | 6.0% | −0.006 | 0.999 | −0.003 | 0.997 |
| Birthweight >4000 g | Combined model | 7.9% | 0.742 (0.717–0.764) | 0.209 (0.181–0.240) | 0.0687 | 6.0% | −0.002 | 1.001 | −0.003 | 0.997 |
| Birthweight >4500 g | Model 1 | 1.2% | 0.731 (0.680–0.780) | 0.026 (0.017–0.052) | 0.0119 | 0.6% | −0.007 | 0.999 | −0.005 | 0.995 |
| Birthweight >4500 g | Model 2 | 1.2% | 0.737 (0.685–0.786) | 0.037 (0.018–0.068) | 0.0119 | 0.7% | 0.059 | 1.016 | −0.005 | 0.995 |
| Birthweight >4500 g | Model 3 | 1.2% | 0.829 (0.785–0.874) | 0.073 (0.040–0.129) | 0.0116 | 3.3% | −0.046 | 0.992 | −0.018 | 0.983 |
| Birthweight >4500 g | Combined model | 1.2% | 0.831 (0.788–0.876) | 0.066 (0.042–0.107) | 0.0116 | 2.9% | −0.030 | 0.997 | −0.017 | 0.984 |

<span style="color:red">(b) Paired differences in AUROC between models</span>

| Comparison | Birthweight >4000 g, ΔAUROC (95% CI) | Birthweight >4500 g, ΔAUROC (95% CI) |
|---|---|---|
| Model 2 − Model 1 | 0.023 (0.013 to 0.037) | 0.006 (−0.006 to 0.019) |
| Model 3 − Model 1 | 0.105 (0.081 to 0.128) | 0.098 (0.064 to 0.142) |
| Combined − Model 1 | 0.104 (0.081 to 0.129) | 0.100 (0.061 to 0.139) |
| Model 3 − Model 2 | 0.082 (0.058 to 0.102) | 0.092 (0.058 to 0.134) |
| Combined − Model 2 | 0.081 (0.059 to 0.101) | 0.094 (0.055 to 0.131) |
| Combined − Model 3 | −0.001 (−0.003 to 0.003) | 0.002 (−0.001 to 0.004) |

<span style="color:red">Table note: AUROC and AUPRC were calculated from out-of-fold predictions averaged for each participant across repeated stratified 10-fold cross-validation; 95% confidence intervals were obtained from 1,000 bootstrap resamples of participants. AUPRC was calculated as the area under the precision–recall curve using the trapezoidal rule 【待更新：按梯形积分重算 AUPRC 数值】. Differences in AUROC were estimated by paired bootstrap resampling, in which the same resampled participants were used for both models. Calibration measures were calculated from Platt-recalibrated out-of-fold predictions from one complete run of stratified 10-fold cross-validation, in which each participant had one prediction. The scaled Brier score is one minus the ratio of the Brier score to that of a null model assigning the observed prevalence to all participants (null Brier score 0.0730 for birthweight >4000 g and 0.0119 for birthweight >4500 g); it was calculated from unrounded values. The calibration intercept and slope were estimated by regressing the outcome on the logit of the predicted probability; calibration-in-the-large (CITL) is the intercept with the slope fixed at 1. AUROC: area under the receiver operating characteristic curve; AUPRC: area under the precision–recall curve; CI: confidence interval; O/E: observed-to-expected ratio.</span>

## <span style="color:red">Supplementary Table S6. Additional sensitivity analysis of the alcohol-related variable with gestational duration outcomes.</span>

| Outcome | Model | Estimate | 95% CI |
|---|---|---|---|
| Gestational age at delivery, weeks | Adjusted linear regression | β = 0.099 weeks | −0.046 to 0.243 |
| Delivery <37 weeks | Adjusted logistic regression | OR = 0.92 | 0.73 to 1.15 |
| Delivery <39 weeks | Adjusted logistic regression | OR = 0.90 | 0.76 to 1.07 |
| Delivery ≥41 weeks | Adjusted logistic regression | OR = 1.27 | 0.81 to 1.94 |

<span style="color:red">Table note: The alcohol-related variable was the alcoholic drinks component of the Alternative Healthy Eating Index-2010 [24]. For women, this component assigns 2.5 points to non-drinkers (0 drinks/day), 5 points to 0.1–<0.5 drinks/day, 10 points to 0.5–1.5 drinks/day, 5 points to >1.5–<2.0 drinks/day, 2.5 points to 2.0–<2.5 drinks/day, and 0 points to ≥2.5 drinks/day; the score is therefore not monotonic in alcohol intake, with the highest score assigned to moderate intake. Models were adjusted for maternal age, BMI, income, race and ethnicity, smoking, gravidity, and preexisting diabetes, as in the main alcohol analysis. Because alcohol exposure may itself influence gestational duration, these outcomes are not strict negative controls, and the absence of an association does not exclude residual confounding. This analysis is exploratory. CI: confidence interval; OR: odds ratio.</span>

<!-- 原表的 "Interpretation" 一列已删去；表题中的 "Negative-control-type" 改为 "Additional"。 -->

## Supplementary Table S7. Comparison of included pregnancies and sequentially excluded pregnancies.

【无改动，沿用原稿】

## <span style="color:red">Supplementary Table S8. Threshold-based operating characteristics of the recalibrated models at the upper quintile and upper decile of predicted risk (Revised).</span>

| Outcome | Model | Risk stratum | Predicted-risk cutoff | TP | FN | FP | TN | Sensitivity (%) | Specificity (%) | PPV (%) | NPV (%) |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Birthweight >4000 g | Model 1 | Upper quintile (top 20%) | 10.0% | 166 | 339 | 1109 | 4757 | 32.9 | 81.1 | 13.0 | 93.3 |
| Birthweight >4000 g | Model 1 | Upper decile (top 10%) | 11.8% | 90 | 415 | 548 | 5318 | 17.8 | 90.7 | 14.1 | 92.8 |
| Birthweight >4000 g | Model 2 | Upper quintile (top 20%) | 10.5% | 180 | 325 | 1095 | 4771 | 35.6 | 81.3 | 14.1 | 93.6 |
| Birthweight >4000 g | Model 2 | Upper decile (top 10%) | 12.8% | 102 | 403 | 536 | 5330 | 20.2 | 90.9 | 16.0 | 93.0 |
| Birthweight >4000 g | Model 3 | Upper quintile (top 20%) | 12.2% | 243 | 262 | 1032 | 4834 | 48.1 | 82.4 | 19.1 | 94.9 |
| Birthweight >4000 g | Model 3 | Upper decile (top 10%) | 16.1% | 148 | 357 | 490 | 5376 | 29.3 | 91.6 | 23.2 | 93.8 |
| Birthweight >4000 g | Combined model | Upper quintile (top 20%) | 12.2% | 239 | 266 | 1036 | 4830 | 47.3 | 82.3 | 18.7 | 94.8 |
| Birthweight >4000 g | Combined model | Upper decile (top 10%) | 16.2% | 147 | 358 | 491 | 5375 | 29.1 | 91.6 | 23.0 | 93.8 |
| Birthweight >4500 g | Model 1 | Upper quintile (top 20%) | 1.7% | 35 | 42 | 1240 | 5054 | 45.5 | 80.3 | 2.7 | 99.2 |
| Birthweight >4500 g | Model 1 | Upper decile (top 10%) | 2.4% | 23 | 54 | 615 | 5679 | 29.9 | 90.2 | 3.6 | 99.1 |
| Birthweight >4500 g | Model 2 | Upper quintile (top 20%) | 1.8% | 37 | 40 | 1238 | 5056 | 48.1 | 80.3 | 2.9 | 99.2 |
| Birthweight >4500 g | Model 2 | Upper decile (top 10%) | 2.4% | 25 | 52 | 613 | 5681 | 32.5 | 90.3 | 3.9 | 99.1 |
| Birthweight >4500 g | Model 3 | Upper quintile (top 20%) | 1.7% | 56 | 21 | 1219 | 5075 | 72.7 | 80.6 | 4.4 | 99.6 |
| Birthweight >4500 g | Model 3 | Upper decile (top 10%) | 3.0% | 36 | 41 | 602 | 5692 | 46.8 | 90.4 | 5.6 | 99.3 |
| Birthweight >4500 g | Combined model | Upper quintile (top 20%) | 1.8% | 54 | 23 | 1221 | 5073 | 70.1 | 80.6 | 4.2 | 99.5 |
| Birthweight >4500 g | Combined model | Upper decile (top 10%) | 3.0% | 35 | 42 | 603 | 5691 | 45.5 | 90.4 | 5.5 | 99.3 |
| LGA90 | Model 1 | Upper quintile (top 20%) | 24.8% | 398 | 921 | 877 | 4175 | 30.2 | 82.6 | 31.2 | 81.9 |
| LGA90 | Model 1 | Upper decile (top 10%) | 29.1% | 219 | 1100 | 419 | 4633 | 16.6 | 91.7 | 34.3 | 80.8 |
| LGA90 | Model 2 | Upper quintile (top 20%) | 26.5% | 443 | 876 | 832 | 4220 | 33.6 | 83.5 | 34.7 | 82.8 |
| LGA90 | Model 2 | Upper decile (top 10%) | 32.1% | 255 | 1064 | 383 | 4669 | 19.3 | 92.4 | 40.0 | 81.4 |
| LGA90 | Model 3 | Upper quintile (top 20%) | 31.3% | 554 | 765 | 721 | 4331 | 42.0 | 85.7 | 43.5 | 85.0 |
| LGA90 | Model 3 | Upper decile (top 10%) | 38.6% | 313 | 1006 | 325 | 4727 | 23.7 | 93.6 | 49.1 | 82.5 |
| LGA90 | Combined model | Upper quintile (top 20%) | 31.5% | 560 | 759 | 715 | 4337 | 42.5 | 85.8 | 43.9 | 85.1 |
| LGA90 | Combined model | Upper decile (top 10%) | 38.7% | 322 | 997 | 316 | 4736 | 24.4 | 93.7 | 50.5 | 82.6 |
| LGA97 | Model 1 | Upper quintile (top 20%) | 9.1% | 178 | 292 | 1097 | 4804 | 37.9 | 81.4 | 14.0 | 94.3 |
| LGA97 | Model 1 | Upper decile (top 10%) | 11.5% | 111 | 359 | 527 | 5374 | 23.6 | 91.1 | 17.4 | 93.7 |
| LGA97 | Model 2 | Upper quintile (top 20%) | 9.4% | 194 | 276 | 1081 | 4820 | 41.3 | 81.7 | 15.2 | 94.6 |
| LGA97 | Model 2 | Upper decile (top 10%) | 12.2% | 120 | 350 | 518 | 5383 | 25.5 | 91.2 | 18.8 | 93.9 |
| LGA97 | Model 3 | Upper quintile (top 20%) | 11.4% | 249 | 221 | 1026 | 4875 | 53.0 | 82.6 | 19.5 | 95.7 |
| LGA97 | Model 3 | Upper decile (top 10%) | 15.7% | 164 | 306 | 474 | 5427 | 34.9 | 92.0 | 25.7 | 94.7 |
| LGA97 | Combined model | Upper quintile (top 20%) | 11.2% | 245 | 225 | 1030 | 4871 | 52.1 | 82.5 | 19.2 | 95.6 |
| LGA97 | Combined model | Upper decile (top 10%) | 15.6% | 167 | 303 | 471 | 5430 | 35.5 | 92.0 | 26.2 | 94.7 |

<span style="color:red">Table note: Threshold-based operating characteristics were calculated from Platt-recalibrated out-of-fold predicted probabilities from one complete run of stratified 10-fold cross-validation, in which each participant had one prediction. Predictions from all folds were ranked together, and the 1,275 pregnancies (upper quintile) and 638 pregnancies (upper decile) with the highest predicted risk were classified as screen-positive. The predicted-risk cutoff is the lowest recalibrated predicted probability among screen-positive pregnancies. These fixed risk strata describe screening yield and do not represent recommended clinical intervention thresholds. TP: true positive; FN: false negative; FP: false positive; TN: true negative; PPV: positive predictive value; NPV: negative predictive value.</span>

## <span style="color:red">Supplementary Table S9. Sensitivity comparison of logistic regression and non-linear classifiers for primary macrosomia outcomes (Revised).</span>

| Outcome | Model | Classifier | AUROC (95% CI) | AUPRC (95% CI) |
|---|---|---|---|---|
| Birthweight >4000 g | Model 1 | Logistic regression | 0.638 (0.612–0.661) | 0.120 (0.106–0.139) |
| Birthweight >4000 g | Model 1 | Random forest | 0.634 (0.608–0.660) | 0.118 (0.105–0.136) |
| Birthweight >4000 g | Model 1 | XGBoost | 0.626 (0.602–0.652) | 0.118 (0.105–0.136) |
| Birthweight >4000 g | Model 1 | Gradient boosting | 0.615 (0.590–0.640) | 0.115 (0.102–0.132) |
| Birthweight >4000 g | Model 2 | Logistic regression | 0.661 (0.635–0.684) | 0.136 (0.119–0.159) |
| Birthweight >4000 g | Model 2 | Random forest | 0.650 (0.626–0.676) | 0.131 (0.114–0.153) |
| Birthweight >4000 g | Model 2 | XGBoost | 0.634 (0.609–0.661) | 0.131 (0.115–0.155) |
| Birthweight >4000 g | Model 2 | Gradient boosting | 0.640 (0.616–0.667) | 0.133 (0.116–0.155) |
| Birthweight >4000 g | Model 3 | Logistic regression | 0.743 (0.719–0.765) | 0.200 (0.176–0.233) |
| Birthweight >4000 g | Model 3 | Random forest | 0.731 (0.709–0.755) | 0.207 (0.181–0.242) |
| Birthweight >4000 g | Model 3 | XGBoost | 0.734 (0.712–0.758) | 0.201 (0.177–0.235) |
| Birthweight >4000 g | Model 3 | Gradient boosting | 0.736 (0.714–0.760) | 0.208 (0.182–0.243) |
| Birthweight >4000 g | Combined model | Logistic regression | 0.742 (0.717–0.764) | 0.209 (0.181–0.240) |
| Birthweight >4000 g | Combined model | Random forest | 0.735 (0.712–0.759) | 0.208 (0.181–0.243) |
| Birthweight >4000 g | Combined model | XGBoost | 0.730 (0.708–0.754) | 0.196 (0.172–0.227) |
| Birthweight >4000 g | Combined model | Gradient boosting | 0.738 (0.717–0.761) | 0.201 (0.177–0.233) |
| Birthweight >4500 g | Model 1 | Logistic regression | 0.731 (0.680–0.780) | 0.026 (0.017–0.052) |
| Birthweight >4500 g | Model 1 | Random forest | 0.693 (0.632–0.754) | 0.023 (0.017–0.032) |
| Birthweight >4500 g | Model 1 | XGBoost | 0.667 (0.599–0.733) | 0.020 (0.014–0.027) |
| Birthweight >4500 g | Model 1 | Gradient boosting | 0.681 (0.618–0.738) | 0.021 (0.016–0.029) |
| Birthweight >4500 g | Model 2 | Logistic regression | 0.737 (0.685–0.786) | 0.037 (0.018–0.068) |
| Birthweight >4500 g | Model 2 | Random forest | 0.704 (0.638–0.769) | 0.025 (0.020–0.031) |
| Birthweight >4500 g | Model 2 | XGBoost | 0.673 (0.609–0.733) | 0.023 (0.018–0.031) |
| Birthweight >4500 g | Model 2 | Gradient boosting | 0.711 (0.647–0.768) | 0.025 (0.020–0.033) |
| Birthweight >4500 g | Model 3 | Logistic regression | 0.829 (0.785–0.874) | 0.073 (0.040–0.129) |
| Birthweight >4500 g | Model 3 | Random forest | 0.804 (0.757–0.852) | 0.066 (0.042–0.116) |
| Birthweight >4500 g | Model 3 | XGBoost | 0.782 (0.728–0.836) | 0.066 (0.041–0.117) |
| Birthweight >4500 g | Model 3 | Gradient boosting | 0.798 (0.743–0.849) | 0.065 (0.042–0.108) |
| Birthweight >4500 g | Combined model | Logistic regression | 0.831 (0.788–0.876) | 0.066 (0.042–0.107) |
| Birthweight >4500 g | Combined model | Random forest | 0.820 (0.774–0.866) | 0.058 (0.038–0.096) |
| Birthweight >4500 g | Combined model | XGBoost | 0.778 (0.724–0.831) | 0.061 (0.039–0.108) |
| Birthweight >4500 g | Combined model | Gradient boosting | 0.788 (0.735–0.838) | 0.063 (0.039–0.114) |

<span style="color:red">Table note. Logistic-regression rows correspond to the primary models (Table S5). The non-linear classifiers used the same predictor sets as the logistic regression models (42, 51, 56, and 65 predictors) and were evaluated in one run of stratified 10-fold cross-validation, so that each participant had one out-of-fold prediction. Within each outer training fold, hyperparameters were selected by randomized search with inner 3-fold cross-validation optimizing average precision (12 iterations for random forest and gradient boosting and 18 for XGBoost). 95% confidence intervals were obtained from 2,000 bootstrap resamples of participants. Hyperparameter search spaces are provided in Supplementary Table S15. AUPRC was calculated as the area under the precision–recall curve using the trapezoidal rule. 【待更新：按梯形积分重算后的 AUPRC 数值（当前表中 AUPRC 为 average precision）】 AUROC: area under the receiver operating characteristic curve; AUPRC: area under the precision–recall curve.</span>

## <span style="color:red">Supplementary Table S10. Missingness of the predictors included in the prediction models before k-nearest-neighbor imputation (Revised).</span>

| Predictor | Visit | Missing, % |
|---|---|---:|
| Age | Visit 1 | 0.4 |
| Race and ethnicity (four indicators) | Visit 1 | 0.0 |
| Income level | Visit 1 | 16.3 |
| Smoking in the 3 months before pregnancy | Visit 1 | 0.0 |
| Pre-pregnancy BMI | Visit 1 | 1.3 |
| Preexisting diabetes mellitus | Visit 1 | 0.0 |
| Healthy Eating Index-2010 and Alternative Healthy Eating Index-2010 component and total scores (25 predictors) | Visit 1 | 0.0 |
| BMI at Visit 1 | Visit 1 | 2.0 |
| Gestational weight gain at Visit 1 | Visit 1 | 1.6 |
| Waist circumference at Visit 1 | Visit 1 | 2.0 |
| Waist over iliac crest at Visit 1 | Visit 1 | 2.0 |
| Hip circumference at Visit 1 | Visit 1 | 2.1 |
| Neck circumference at Visit 1 | Visit 1 | 12.1 |
| Systolic blood pressure at Visit 1 | Visit 1 | 1.4 |
| Diastolic blood pressure at Visit 1 | Visit 1 | 1.4 |
| Gestational weight gain at Visit 2 | Visit 2 | 2.2 |
| Systolic blood pressure at Visit 2 | Visit 2 | 1.4 |
| Diastolic blood pressure at Visit 2 | Visit 2 | 1.4 |
| Gestational age at ultrasound, Visit 2 | Visit 2 | 0.5 |
| Biparietal diameter, Visit 2 | Visit 2 | 0.0 |
| Head circumference, Visit 2 | Visit 2 | 0.0 |
| Abdominal circumference, Visit 2 | Visit 2 | 0.2 |
| Femur length, Visit 2 | Visit 2 | 0.0 |
| Estimated fetal weight, Visit 2 | Visit 2 | 0.2 |
| Gestational weight gain at Visit 3 | Visit 3 | 2.1 |
| Systolic blood pressure at Visit 3 | Visit 3 | 1.3 |
| Diastolic blood pressure at Visit 3 | Visit 3 | 1.3 |
| Gestational age at ultrasound, Visit 3 | Visit 3 | 0.4 |
| Biparietal diameter, Visit 3 | Visit 3 | 0.0 |
| Head circumference, Visit 3 | Visit 3 | 0.0 |
| Abdominal circumference, Visit 3 | Visit 3 | 0.0 |
| Femur length, Visit 3 | Visit 3 | 0.0 |
| Amniotic fluid index, quadrant 1 | Visit 3 | 7.4 |
| Amniotic fluid index, quadrant 2 | Visit 3 | 7.2 |
| Amniotic fluid index, quadrant 3 | Visit 3 | 7.1 |
| Amniotic fluid index, quadrant 4 | Visit 3 | 8.0 |
| Estimated fetal weight, Visit 3 | Visit 3 | 0.0 |
| Estimated fetal weight percentile reported in nuMoM2b, Visit 3 | Visit 3 | 0.5 |

<span style="color:red">Note: Missingness was calculated in the final analytic cohort (N=6,371) before k-nearest-neighbor imputation. The table includes all predictors used in the prediction models, as defined in Table 2 of the main manuscript. Residual missingness was handled by k-nearest-neighbor imputation fitted within the training data of each cross-validation split. Variables that were not used as predictors (fetal sex, gestational diabetes mellitus, the Visit-2 reported estimated fetal weight percentile, and uterine artery Doppler measurements) are not shown. Percentages are rounded to one decimal place. BMI: body mass index.</span>

## Supplementary Table S11. Comparison of WHO and INTERGROWTH-21st fetal ultrasound percentile comparators for primary macrosomia outcomes.

【表格其余各行沿用原稿，只新增以下两行（分别插在两个结局的 Visit 2 FL 之后）并修改表注】

| Outcome | Visit | Measure | WHO AUROC | INTERGROWTH-21st AUROC (95% CI) |
|---|---|---|---|---|
| <span style="color:red">Birthweight >4000 g</span> | <span style="color:red">Visit 2</span> | <span style="color:red">EFW</span> | <span style="color:red">0.570</span> | <span style="color:red">0.609 (0.577–0.640)<sup>a</sup></span> |
| <span style="color:red">Birthweight >4500 g</span> | <span style="color:red">Visit 2</span> | <span style="color:red">EFW</span> | <span style="color:red">0.600</span> | <span style="color:red">0.628 (0.545–0.713)<sup>a</sup></span> |

Note. Fetal ultrasound percentiles were evaluated as single-predictor chart-based comparators for subsequent macrosomia. INTERGROWTH-21st values are shown as AUROC with 95% confidence intervals from 2,000 bootstrap resamples. <span style="color:red">INTERGROWTH-21st fetal growth percentiles were derived according to the INTERGROWTH-21st fetal growth standards [28], and estimated fetal weight percentiles according to the INTERGROWTH-21st standards for Hadlock-based estimated fetal weight [29].</span> <span style="color:red"><sup>a</sup> The INTERGROWTH-21st standard for Hadlock-based estimated fetal weight applies from 18 weeks of gestation (126–287 days). Because 39.8% of the Visit-2 scans were performed before 18 weeks, this percentile could be derived for 3,834 pregnancies (320 with birthweight >4000 g and 48 with birthweight >4500 g).</span> AUROC: area under the receiver operating characteristic curve; WHO: World Health Organization; BPD: biparietal diameter; HC: head circumference; AC: abdominal circumference; FL: femur length; EFW: estimated fetal weight.

<!-- 参考文献编号 [28]、[29] 与正文一致。 -->

## Supplementary Table S12. TRIPOD+AI 2024 checklist.

【未列出的条目沿用原稿；以下条目的 "Reported in manuscript / Location / Comments" 替换为下表内容】

| Item | Checklist item | Reported in manuscript | Location | Comments |
|---|---|---|---|---|
| 9b | Predictors are clearly defined, including how and when they were measured. | Yes | Section 2.3; <span style="color:red">Table 2</span>; Supplementary Methods; Supplementary Table S3 | <span style="color:red">All predictors in each model are listed in Table 2 together with their time of availability. Maternal characteristics, anthropometry, diet indices, and ultrasound predictors are described in Section 2.3. Fetal sex and gestational diabetes mellitus were not used as predictors. WHO fetal growth chart–based percentile variables are defined in Supplementary Table S3.</span> |
| 10 | Sample size is explained and justified in the prediction-model context. | <span style="color:red">Partly</span> | Section <span style="color:red">2.6</span>; Section 3.1; <span style="color:red">Supplementary Table S14</span> | <span style="color:red">The sample size was determined by the available nuMoM2b data. The number of candidate predictors and events per candidate predictor are reported for each model and outcome. Because of the limited number of events for birthweight >4500 g, model complexity was additionally assessed (Supplementary Table S14). No a priori sample-size calculation was performed.</span> |
| 12a | Data use for model development and internal validation is described. | Yes | Section 2.5 | Repeated stratified 10-fold cross-validation with 1000 repetitions was used for internal validation. <span style="color:red">Out-of-fold predictions were averaged at the participant level, and confidence intervals were obtained by bootstrap resampling of participants.</span> |
| 12c | Model type, rationale, model-building steps, hyperparameter tuning, and internal validation are described. | Yes | Section 2.5; Supplementary Table<span style="color:red">s</span> S9 <span style="color:red">and S15</span> | Logistic regression was selected as the primary modeling approach. Regularization, class weighting, hyperparameter tuning, <span style="color:red">Platt recalibration</span>, and internal validation are described in Section 2.5. Non-linear classifier sensitivity comparisons are reported in Supplementary Table S9. |
| 12e | Performance measures and plots are specified. | Yes | Section 2.5; Section 3.2; Figure 1; Supplementary Figures S1–S3 <span style="color:red">and S5</span>; Supplementary Tables S4, S5, S8, <span style="color:red">S9, and S14</span> | AUROC, AUPRC, <span style="color:red">paired differences in AUROC,</span> Brier score, <span style="color:red">scaled Brier score,</span> calibration intercept, calibration slope, <span style="color:red">calibration-in-the-large, O/E ratio,</span> reliability plots, threshold-based operating characteristics, <span style="color:red">decision curves,</span> and non-linear model sensitivity comparisons are reported. |
| 12g | Calculation of model predictions for evaluation is described. | Yes | Section 2.5 | <span style="color:red">Out-of-fold predicted probabilities were averaged at the participant level for discrimination analyses. Calibration, threshold-based, and decision-curve analyses used Platt-recalibrated out-of-fold predictions from one complete run of 10-fold cross-validation, with one prediction per participant.</span> |
| 13 | Class imbalance handling and recalibration are described. | Yes | Section 2.5; Supplementary Tables S4–S5; Supplementary Figures S2–S3 | Class-weighted logistic regression was used, followed by <span style="color:red">Platt recalibration fitted within the training folds</span>. Calibration summaries are reported for primary outcomes and LGA sensitivity outcomes. |
| 15 | Model output and thresholds are described. | Yes | Section 2.5; Section 3.2; Supplementary Table S8 | Model output was <span style="color:red">recalibrated</span> predicted probability. Upper-quintile and upper-decile risk strata were evaluated as <span style="color:red">fixed risk strata</span> in Supplementary Table S8<span style="color:red">; they do not represent recommended intervention thresholds</span>. |
| 16 | Differences between development and evaluation data are identified. | <span style="color:red">Yes</span> | <span style="color:red">Sections 2.6, 3.2, and 4.4; Supplementary Table S13</span> | <span style="color:red">Performance of the full models was assessed by internal validation only. A reduced early-pregnancy model with six harmonizable predictors was evaluated in an independent Dutch cohort (MMC). Differences between the cohorts are described: the MMC data included multiparous women and repeated deliveries, and predictor availability was limited to six predictors.</span> |
| 20c | Distribution of predictors and outcomes is compared between development and evaluation data if applicable. | <span style="color:red">Partly</span> | <span style="color:red">Section 3.2; Supplementary Table S13</span> | <span style="color:red">Outcome prevalence is reported for both cohorts. The MMC cohort has been described previously [33].</span> |
| 23a | Model performance estimates are reported with confidence intervals and relevant plots. | Yes | Section 3.2; Figure 1; Table <span style="color:red">3</span>; Supplementary Figures S1–S3 <span style="color:red">and S5</span>; Supplementary Tables S4, S5, S8, S9, S11, <span style="color:red">S13, and S14</span> | Discrimination, precision–recall performance, calibration, threshold operating characteristics, non-linear classifier sensitivity comparisons, <span style="color:red">model-complexity analysis, the limited evaluation in the MMC cohort,</span> and WHO versus INTERGROWTH-21st chart-comparator analyses are reported. |
| 26 | Limitations are discussed, including sample size, missing data, overfitting, representativeness, and generalizability. | Yes | Discussion, Section 4.4; Supplementary Tables S7 and S10 | Limitations include internal validation only, <span style="color:red">evaluation of the early-pregnancy model in the complete-follow-up cohort,</span> selection bias, rare >4500 g outcome, missingness, ultrasound timing, Hadlock-derived EFW limitations, dietary recall bias, and need for external validation. |

<span style="color:red">另外：条目 12f、24 中 "No external model updating, recalibration, or refitting after external validation was performed" 可保留（MMC 分析中确未更新模型），建议在 Comments 中补一句 "In the MMC evaluation, the nuMoM2b coefficients and intercept were applied without updating."</span>

## <span style="color:red">Supplementary Table S13. Limited evaluation of a reduced early-pregnancy model in an independent Dutch cohort (Revised).</span>

| Outcome | Model / evaluation setting | Predictors | Records (events, %) | AUROC (95% CI) |
|---|---|---|---|---|
| Birthweight >4000 g | Model 1, internal validation in nuMoM2b | Full Model 1 predictor set (42 predictors) | 6,371 (505, 7.9%) | 0.638 (0.612–0.661) |
| Birthweight >4000 g | Reduced early-pregnancy model, internal validation in nuMoM2b | Six harmonizable predictors | 6,371 (505, 7.9%) | 0.603 (0.577–0.627) |
| Birthweight >4000 g | Reduced early-pregnancy model applied to MMC | Six harmonizable predictors | 12,043 (1,142, 9.5%) | 0.597 (0.580–0.613) |
| Birthweight >4500 g | Model 1, internal validation in nuMoM2b | Full Model 1 predictor set (42 predictors) | 6,371 (77, 1.2%) | 0.731 (0.680–0.780) |
| Birthweight >4500 g | Reduced early-pregnancy model, internal validation in nuMoM2b | Six harmonizable predictors | 6,371 (77, 1.2%) | 0.615 (0.556–0.678) |
| Birthweight >4500 g | Reduced early-pregnancy model applied to MMC | Six harmonizable predictors | 12,043 (134, 1.1%) | 0.636 (0.589–0.681) |

<span style="color:red">Table note: The MMC cohort comprises retrospective electronic medical record data of pregnant women aged 18–45 years without preexisting diabetes who gave birth at Máxima Medical Center, Veldhoven, the Netherlands, between 2012 and 2017, and has been described previously [33]. The six harmonizable predictors were maternal age, pre-pregnancy BMI, and four race and ethnicity indicators (non-Hispanic White, non-Hispanic Black, Hispanic, and Asian or other). The reduced model was developed in nuMoM2b using the same modeling framework as the main models and was applied to the MMC data with the nuMoM2b coefficients and intercept unchanged, without refitting or recalibration. MMC records with missing predictor or outcome data were excluded. The MMC data included both nulliparous and multiparous women, and some women contributed more than one delivery record. Because the models were trained with class weights, the unchanged intercept does not correspond to absolute risk; therefore, only discrimination was assessed. 95% confidence intervals were obtained by bootstrap resampling at the level of women, with all delivery records of a woman resampled together. Periconceptional diet, most Visit-1 anthropometric measurements, and serial ultrasound measurements were not available in a comparable form in the MMC cohort. This analysis is a limited evaluation of a reduced predictor set and does not constitute external validation of the full visit-updated models. The retrospective analysis of the MMC data was approved by the Medical Ethics Review Committee of Máxima Medical Center, which waived the requirement for informed consent. AUROC: area under the receiver operating characteristic curve; BMI: body mass index; CI: confidence interval; MMC: Máxima Medical Center.</span>

## <span style="color:red">Supplementary Table S14. Model complexity of the Combined model for birthweight >4500 g (New).</span>

| Configuration | Number of predictors | Local approximate effective degrees of freedom | AUROC (95% CI) | ΔAUROC vs full model (95% CI) | Calibration slope | CITL | O/E |
|---|---:|---:|---|---|---:|---:|---:|
| Full model | 65 | 24.2 | 0.828 (0.783–0.873) | — | 1.022 | −0.013 | 0.987 |
| Top 20% of predictors | 13 | 3.7 | 0.813 (0.764–0.859) | −0.015 (−0.044 to 0.011) | 1.056 | −0.011 | 0.990 |
| Top 14% of predictors | 10 | 3.0 | 0.803 (0.752–0.851) | −0.025 (−0.057 to 0.007) | 1.010 | −0.016 | 0.985 |

<span style="color:red">Table note: The analysis used 100 repetitions of stratified 10-fold cross-validation (6,371 pregnancies; 77 events). Within each outer training fold, predictors were ranked by their absolute standardized mean difference (Cohen's d), and the top 20% (13 predictors) or 14% (10 predictors) were retained; the validation fold was not used for ranking, and different folds could select different predictors. Within each outer training set, an inner 5-fold cross-validation was used to obtain out-of-fold scores, to which the Platt calibrator was fitted before application to the outer validation fold. The local approximate effective degrees of freedom were calculated for the penalized model with the given set of active predictors and exclude the intercept; they do not account for the degrees of freedom used by predictor selection. Because predictors were selected within each training fold, the AUROCs of the reduced models include the optimism of selection. Out-of-fold predictions were averaged for each participant across the repetitions, and confidence intervals were obtained by bootstrap resampling of participants; differences in AUROC were estimated by paired bootstrap resampling. The full model in this table was evaluated within the same framework and therefore differs slightly from the Combined model in Table S5. AUROC: area under the receiver operating characteristic curve; CITL: calibration-in-the-large; O/E: observed-to-expected ratio.</span>

## <span style="color:red">Supplementary Table S15. Hyperparameter search spaces (New).</span>

| Classifier | Hyperparameter | Search values |
|---|---|---|
| Logistic regression | C | 0.01, 0.05, 0.1, 0.3, 1 |
| | Penalty | Elastic net |
| | L1 ratio | 0.1, 0.3, 0.5, 0.7, 0.9 |
| | Solver | SAGA |
| | Maximum iterations | 50,000 |
| | Tolerance | 1×10⁻⁴ |
| | Class weight (negative : positive), birthweight >4000 g | 1:2, 1:3, 1:5, 1:7, 1:10, square root of the negative-to-positive ratio |
| | Class weight (negative : positive), birthweight >4500 g | 1:2, 1:3, 1:5, 1:7, 1:10, square root of the negative-to-positive ratio |
| Random forest | n_estimators | 300, 500, 800 |
| | max_depth | None, 3, 5, 8, 12 |
| | min_samples_leaf | 5, 10, 20, 40 |
| | min_samples_split | 2, 10, 20, 50 |
| | max_features | sqrt, 0.30, 0.50, 0.80 |
| | bootstrap | True |
| | Randomized-search draws | 12 |
| XGBoost | n_estimators | 200, 400, 600, 900 |
| | learning_rate | 0.01, 0.03, 0.05, 0.08, 0.10 |
| | max_depth | 1, 2, 3, 4 |
| | min_child_weight | 1, 5, 10, 20 |
| | subsample | 0.60, 0.75, 0.90, 1.00 |
| | colsample_bytree | 0.60, 0.75, 0.90, 1.00 |
| | gamma | 0, 0.1, 0.5, 1.0, 5, 10 |
| | reg_alpha | 0, 0.1, 0.5, 1.0 |
| | reg_lambda | 1, 3, 5, 10 |
| | Randomized-search draws | 18 |
| Gradient boosting | n_estimators | 100, 200, 300, 500 |
| | learning_rate | 0.01, 0.03, 0.05, 0.08, 0.10 |
| | max_depth | 1, 2, 3 |
| | min_samples_leaf | 5, 10, 20, 40 |
| | subsample | 0.60, 0.80, 1.00 |
| | max_features | None, sqrt, 0.50, 0.80 |
| | Randomized-search draws | 12 |

<span style="color:red">Table note: For all classifiers, hyperparameters were selected within each outer training fold by randomized search with inner 3-fold cross-validation optimizing average precision; the validation fold was not used for tuning.</span>
