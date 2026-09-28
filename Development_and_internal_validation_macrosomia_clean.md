# Development and internal validation of early- and mid-pregnancy prediction models for macrosomia in nulliparous singleton pregnancies

## Authors
Yanqi Wu, PhD<sup>1,4</sup>,

Myrthe van der Ven, PhD<sup>2,3,4</sup>;

Elisabetta Peri, PhD<sup>1,4</sup>;

Sima Asvadi, PhD<sup>1</sup>;

M. Beatrijs van der Hout-van der Jagt, PhD<sup>1,3,4</sup>;

S. Guid Oei, MD, PhD<sup>3,4</sup>;

Massimo Mischi, PhD<sup>1,4</sup>;

Xi Long, PhD<sup>1,4</sup>

## Affiliations
<sup>1</sup> Department of Electrical Engineering, Eindhoven University of Technology, Eindhoven, The Netherlands  
<sup>2</sup> Department of Biomedical Engineering, Eindhoven University of Technology, Eindhoven, The Netherlands  
<sup>3</sup> Department of Obstetrics and Gynaecology, Máxima Medical Center, Veldhoven, The Netherlands  
<sup>4</sup> Eindhoven MedTech Innovation Center, Eindhoven, The Netherlands

## Corresponding author
Xi Long, PhD  
Department of Electrical Engineering, Eindhoven University of Technology  
Groene Loper 19, 5612 AP Eindhoven, The Netherlands  
Email: x.long@tue.nl

## Word count (main)
<span style="color:red">5620</span><!-- 按原口径（摘要至结论）粗算为 5,625，需在 Word 中重新统计 -->

## Number of tables and figures
Tables: <span style="color:red">3</span>

Figures: <span style="color:red">4</span>  
Supplementary tables: <span style="color:red">14</span>  
Supplementary figures: <span style="color:red">7</span>

## What this study adds to the clinical work
Routinely available early-pregnancy maternal characteristics and anthropometry <span style="color:red">provided moderate</span> risk stratification for macrosomia in nulliparous singleton pregnancies. Visit-updated models incorporating later ultrasound measurements improve discrimination further and may help refine surveillance during pregnancy.

## Keywords
Fetal overgrowth; prenatal ultrasound; maternal anthropometry; gestational weight gain; periconceptional diet.

## Abstract

**Purpose:** Macrosomia is associated with adverse maternal and neonatal outcomes, but early risk stratification remains challenging. Most existing prediction approaches rely on later-pregnancy ultrasound measurements, limiting opportunities for earlier preventive counseling and monitoring.

**Methods:** In this secondary analysis of the prospective nuMoM2b cohort in the United States, we included 6,371 nulliparous singleton pregnancies. We developed visit-updated multivariable logistic regression models for birthweight \>4000 g and \>4500 g using routinely available maternal characteristics, anthropometry, periconceptional diet, and serial ultrasound measurements, with sensitivity analyses using large-for-gestational-age birthweight. Model performance was assessed by repeated stratified cross-validation and compared with World Health Organization fetal growth chart–based ultrasound percentile benchmarks, emphasizing the estimated fetal weight percentile as the most clinically familiar proxy.

**Results:** Birthweight \>4000 g and \>4500 g occurred in 7.9% and 1.2% of pregnancies, respectively. Models updated with later pregnancy information achieved the best discrimination, with an area under the receiver operating characteristic curve of <span style="color:red">0.74</span> for birthweight \>4000 g and 0.83 for birthweight \>4500 g. The early-pregnancy model based on maternal data alone provided <span style="color:red">moderate discrimination (0.64 and 0.73, respectively), although lower than the strongest third-trimester</span> WHO fetal growth chart–based ultrasound percentile benchmarks.

**Conclusion:** Routinely available early-pregnancy maternal characteristics and anthropometry provided moderate risk stratification for macrosomia, and later ultrasound measurements improved performance further. External validation is required before clinical implementation.

# 1. Introduction

Fetal macrosomia is associated with increased maternal and neonatal morbidity, including birth trauma and postpartum hemorrhage \[1,2\]. Its definition is not uniform across studies, with birthweight thresholds of \>4000 g and \>4500 g both commonly used to capture varying degrees of risk \[3,4\]. The condition remains a pressing clinical concern, with approximately 8% of neonates in the United States weighing over 4000 g at birth \[5,6\].

Early identification of pregnancies at high risk for macrosomia enables timely lifestyle interventions—such as dietary modification and gestational weight gain management—which can substantially reduce its incidence \[7–9\]. However, predictions relying mainly on later-pregnancy ultrasound provide less opportunity for early preventive action. Furthermore, clinical assessments often depend on sonographic estimated fetal weight, which becomes less reliable at the extremes of birthweight \[10\].

While early prediction approaches exist \[11,12\], a recent systematic review of 58 multivariable models revealed that most still depend predominantly on near-term ultrasound \[13\]. Only five models incorporated second-trimester or earlier ultrasound data together with routinely available maternal characteristics \[14–18\]. This limitation is particularly critical for nulliparous pregnancies, in which previous obstetric history is unavailable for risk stratification.

Therefore, in this secondary analysis of the prospective nuMoM2b cohort \[19\], we aimed to develop and internally validate visit-updated multivariable prediction models for macrosomia (\>4000 g and \>4500 g) in nulliparous singleton pregnancies. Specifically, we evaluated the baseline predictive value of early-pregnancy maternal characteristics and periconceptional diet, quantified the incremental benefit of second- and third-trimester ultrasound, and benchmarked model performance against World Health Organization (WHO) fetal growth chart percentiles \[10,14–18\].

# 2. Materials and methods

## 2.1 Study design and participants

This was a secondary analysis of the prospective Nulliparous Pregnancy Outcomes Study: Monitoring Mothers-to-Be (nuMoM2b) cohort \[19\]. Nulliparous women with singleton pregnancies were recruited between 2010 and 2013 from hospitals affiliated with eight clinical centers in the United States \[19\]. Three standardized prenatal visits were scheduled at 6–13 weeks (Visit 1), 16–21 weeks (Visit 2), and 22–29 weeks (Visit 3) of gestation \[19\]. The original study was approved by the institutional review board at each participating site, and all participants provided written informed consent before enrollment \[19\]. For the present analysis, pregnancies were excluded if periconceptional dietary data, ultrasound fetal biometry measurements from Visit 2 or Visit 3, birth outcome data, or live-birth status were unavailable. Candidate predictors are summarized in Table 1<span style="color:red"> and Table 2</span>.

## 2.2 Outcomes

The primary outcomes were birthweight \>4000 g and \>4500 g. These thresholds were selected because they are widely used absolute definitions of macrosomia and represent clinically relevant degrees of fetal overgrowth. Separate prediction models were developed for each threshold.

Because absolute birthweight thresholds do not account for gestational age at delivery, we additionally performed sensitivity analyses using large-for-gestational-age birthweight. LGA90 and LGA97 were defined as birthweight above the 90th and 97th percentiles, respectively, for gestational age at delivery and neonatal sex according to the INTERGROWTH-21st Newborn Size Standards <span style="color:red">\[20\]</span>. These analyses assessed whether the visit-updated prediction pattern was consistent when fetal overgrowth was defined relative to gestational age rather than by fixed birthweight thresholds.

## 2.3 Candidate predictors

Candidate predictors were prespecified according to clinical availability during antenatal care and prior evidence linking these factors to fetal overgrowth. Early-pregnancy maternal characteristics included age, pre-pregnancy body mass index, income level relative to the state-specific poverty threshold, race and ethnicity, smoking during the 3 months before pregnancy, and preexisting diabetes mellitus. Visit-specific maternal anthropometric measurements included body mass index, <span style="color:red">gestational weight gain, </span>blood pressure, circumference measurements at Visit 1, and gestational weight gain and blood pressure at Visits 2 and 3. <span style="color:red">Fetal sex and gestational diabetes mellitus were not used as predictors, because their availability at the intended prediction times could not be ensured; fetal sex was used only to define the LGA outcomes.</span>

Periconceptional diet was assessed at enrollment using the modified Block 2005 Food Frequency Questionnaire, which captured usual dietary intake during the 3 months around conception \[21\]. Overall diet quality was summarized using the Healthy Eating Index-2010 and the Alternative Healthy Eating Index-2010 \[22–24\]. <span style="color:red">The component and total scores of both indices were used as dietary predictors.</span>

Ultrasound predictors were obtained at Visits 2 and 3. Visit 2 included gestational age at scan, biparietal diameter, head circumference, abdominal circumference, femur length, and estimated fetal weight. Visit 3 included the same biometry variables together with <span style="color:red">the four</span> amniotic fluid index quadrants<span style="color:red"> and the estimated fetal weight percentile reported in nuMoM2b</span>. Estimated fetal weight was calculated using the Hadlock formula \[25\]. Optional uterine artery Doppler measurements were not included because of the high proportion of missing data. Ultrasound availability for cohort derivation was defined primarily using Visit 2 and Visit 3 fetal biometry, because these measurements directly reflect fetal growth. <span style="color:red">Predictors were entered as continuous or binary variables, with race and ethnicity coded as four binary indicators; the predictors included in each model and their time of availability are listed in Table 2.</span>

## 2.4 Fetal growth chart comparator

As a clinical benchmark, we implemented the trimester-specific World Health Organization fetal growth chart \[26,27\]. Percentiles were computed from nuMoM2b fetal biometry or estimated fetal weight together with gestational age at ultrasound. For pregnancies with ultrasound examinations at Visit 2 and Visit 3, the WHO chart provided five percentile estimates at Visit 2 and five additional percentile estimates at Visit 3, based on head circumference, biparietal diameter, abdominal circumference, femur length, and estimated fetal weight. All WHO-derived percentile variables were evaluated as ultrasound-based benchmark comparators in the discrimination analyses<span style="color:red">; these comparisons with the prediction models were descriptive</span>. Because estimated fetal weight is the most clinically familiar summary measure of fetal size, the estimated fetal weight percentile was additionally highlighted as the most practice-oriented WHO chart-based indicator.

As a supplementary comparison, we also evaluated INTERGROWTH-21st fetal ultrasound percentiles within the same chart-based comparator framework <span style="color:red">\[28,29\]</span>. These percentiles were assessed analogously to the WHO-derived percentiles as single-predictor ultrasound comparators for subsequent birthweight \>4000 g and \>4500 g. These chart-based percentiles describe fetal size at the time of ultrasound examination and do not directly project expected birthweight at delivery. <span style="color:red">Because the INTERGROWTH-21st standard for Hadlock-based estimated fetal weight applies from 18 weeks of gestation, the Visit-2 estimated fetal weight percentile could not be derived for scans performed before 18 weeks.</span> Details of percentile computation and variable coding are provided in the Supplementary Methods and Supplementary Table S3 and Supplementary Table S11.

## 2.5 Model development and internal validation

We developed four visit-updated multivariable logistic regression models to reflect information availability across routine antenatal care<span style="color:red"> (Table 2)</span>. Model 1 used maternal demographics and history, Visit-1 anthropometry, early gestational weight gain, and periconceptional diet indices<span style="color:red"> (42 predictors)</span>. Model 2 extended Model 1 by adding Visit-2 anthropometry and second-trimester ultrasound biometry with derived estimated fetal weight<span style="color:red"> (51 predictors)</span>. Model 3 <span style="color:red">extended Model 1</span> by adding Visit-3 anthropometry and third-trimester ultrasound measurements<span style="color:red"> (56 predictors)</span>. The Combined model <span style="color:red">included all information from Visit 1, Visit 2, and Visit 3 (65 predictors). All four models were developed and evaluated in the same analytic cohort to allow direct comparison.</span>

Logistic regression was selected as the primary modeling approach because of its interpretability, reproducibility, and suitability for clinically deployable risk prediction \[30\]. Predictor-level missingness before imputation was summarized in Supplementary Table S10. Missing data among retained candidate predictors were imputed using a k-nearest-neighbor (k=5) approach. To prevent information leakage, all preprocessing steps, including imputation and scaling, were performed after data splitting and within the training data only. Models were developed and internally validated using repeated stratified 10-fold cross-validation with 1000 repetitions \[31\]. Hyperparameter tuning (penalty and regularization strength) was performed within the training data only. <span style="color:red">In each repetition, every participant received one out-of-fold predicted probability; these predictions were averaged across repetitions at the participant level, so that each participant contributed a single prediction to the evaluation. AUROC and AUPRC were calculated from these participant-level predictions, and 95% confidence intervals were obtained from 1,000 bootstrap resamples of participants. Differences in AUROC between models were estimated using paired bootstrap resampling of the same participants.</span>

Class imbalance was handled using weighted logistic regression, with class weights computed within each cross-validation training fold. The negative class was assigned a weight of 1, and the positive class was weighted by the square root of the negative-to-positive sample ratio to avoid excessive up-weighting of rare positive cases. <span style="color:red">Because class weighting changes the relationship between model scores and absolute outcome probabilities, predicted probabilities were then recalibrated using Platt scaling, with the Platt calibrator fitted within the training folds only and applied to the held-out fold. Calibration, threshold-based, and decision-curve analyses were based on one complete run of stratified 10-fold cross-validation, so that each participant had exactly one recalibrated out-of-fold prediction.</span> Performance estimates derived from this procedure therefore represent internal validation and not external validation.

Discrimination was assessed using the area under the receiver operating characteristic curve (AUROC) and the area under the precision-recall curve (AUPRC). Calibration was assessed using the Brier score, <span style="color:red">the scaled Brier score (one minus the ratio of the Brier score to that of a null model assigning the observed prevalence to all participants), </span>reliability plots, calibration intercept, <span style="color:red">calibration</span> slope, <span style="color:red">calibration-in-the-large, and the observed-to-expected (O/E) ratio</span>. To provide <span style="color:red">interpretable</span> operating characteristics, we also evaluated the upper quintile and upper decile of <span style="color:red">recalibrated</span> out-of-fold predicted risk as <span style="color:red">fixed risk strata</span>, and calculated the corresponding predicted-risk cutoff, screen-positive proportion, sensitivity, specificity, positive predictive value, and negative predictive value. <span style="color:red">Decision-curve analysis was additionally performed across a range of threshold probabilities.</span>

For model interpretation, features were ranked according to the absolute magnitude of standardized logistic regression coefficients averaged across cross-validation folds. <span style="color:red">Because the dietary total scores and their component scores were entered jointly, individual dietary coefficients should not be interpreted as independent effects. </span>To explore the contribution of periconceptional diet to early-pregnancy prediction, we performed sequential ablation of Healthy Eating Index and Alternative Healthy Eating Index components in Model 1 and re-evaluated model performance after removal of each component.

The same modeling framework was applied to the LGA90 and LGA97 sensitivity outcomes, with discrimination and calibration summarized using AUROC, AUPRC, Brier score, calibration intercept, and calibration slope; <span style="color:red">confidence intervals for discrimination were obtained as described above.</span> As an additional model-form sensitivity analysis, we compared the primary-outcome discrimination results with hyperparameter-tuned random forest, XGBoost, and gradient boosting models, using AUROC and AUPRC from cross-validated out-of-fold predictions.

## 2.6 Statistical analysis

Because this secondary analysis used an existing cohort, no a priori sample-size calculation was performed. Following Riley et al. \[32\], we report the available sample size (N=6,371) and event counts (\>4000 g: 505; \>4500 g: 77) <span style="color:red">in relation to the number of candidate predictors. The four models included 42, 51, 56, and 65 candidate predictors (Table 2), corresponding to 7.8–12.0 events per candidate predictor for birthweight \>4000 g and 1.2–1.8 events per candidate predictor for birthweight \>4500 g. Because penalized estimation does not use all candidate predictors to the same extent, we additionally examined model complexity for the Combined model for birthweight \>4500 g. We estimated the local approximate effective degrees of freedom of the penalized model and compared the full model with reduced models in which predictors were ranked within each outer training fold by their absolute standardized mean difference (Cohen’s d), retaining only the top 14% (10 predictors) or 20% (13 predictors). This analysis used 100 repetitions of stratified 10-fold cross-validation, with Platt recalibration fitted on inner 5-fold cross-validated predictions within each outer training fold. Results for birthweight \>4500 g were interpreted cautiously given the limited number of events.</span>

Baseline characteristics were summarized as mean (standard deviation) or number (percentage), as appropriate. Continuous variables were compared using Student’s t-test or Mann–Whitney U test according to distributional assumptions, and categorical variables were compared using chi-square test or Fisher’s exact test, as appropriate. Effect sizes were reported alongside significance tests. To account for multiple comparisons, p-values were adjusted using the Benjamini–Hochberg false discovery rate procedure. All tests were two-sided, and statistical significance was defined as p\<0.05 after adjustment where applicable<span style="color:red"> (q\<0.05)</span>. Detailed univariate testing results, including raw p-values, adjusted q-values, and effect sizes, are provided in the Supplementary Material. Participant flow was summarized using sequential, mutually exclusive exclusion steps. To characterize potential selection during cohort derivation, we compared the final analytic cohort with the two main sequential exclusion groups: pregnancies excluded because of missing periconceptional diet data and pregnancies excluded because of incomplete Visit 2 and/or Visit 3 fetal biometry data after diet data were available. Because these two exclusion mechanisms may reflect different sources of selection, each excluded group was compared separately with the included analytic cohort across maternal sociodemographic characteristics, early-pregnancy clinical characteristics, and available pregnancy outcomes. <span style="color:red">As a limited additional analysis, a reduced early-pregnancy model including only the six predictors that could be harmonized with an independent Dutch cohort from Máxima Medical Center (MMC) \[33\] (maternal age, pre-pregnancy BMI, and four race and ethnicity indicators) was developed in nuMoM2b and applied to MMC delivery records with unchanged coefficients and intercept; records with missing data were excluded. Because the MMC data included multiparous women and repeated deliveries, and class weighting affects absolute predicted probabilities, only discrimination was assessed.</span> Reporting was checked against the TRIPOD+AI 2024 guidance for clinical prediction model studies \[34\]; the completed checklist is provided in Supplementary Table S12. Analyses were performed in Python 3.8 using scikit-learn 1.3.2.

# 3. Results

## 3.1 Cohort characteristics

Among the 10,038 women enrolled in the nuMoM2b cohort, 6,371 nulliparous pregnancies were included after excluding those lacking consent (N=749), outcome data (N=755), periconceptional diet information (N=1,349), or Visit 2/3 ultrasound measurements (N=814), as shown in Supplementary Figure S4. Because complete periconceptional diet and serial ultrasound data were required for the primary analysis, we further compared the included cohort with pregnancies excluded because of missing diet data or incomplete Visit 2/3 ultrasound follow-up (Supplementary Table S7). Excluded pregnancies differed from included pregnancies in several maternal sociodemographic characteristics and pregnancy outcomes, indicating potential selection related to data completeness and follow-up.

Birthweight \>4000 g occurred in 505 neonates (7.9%), including 77 (1.2%) \>4500 g. Preterm birth occurred in 880 pregnancies (13.8%), and 284 (4.5%) were complicated by gestational diabetes. Pregnancy characteristics are shown in Table 1. Compared with non-macrosomic pregnancies, those with macrosomia generally exhibited higher maternal anthropometry, greater gestational weight gain, and larger later-pregnancy fetal biometry. These differences were more pronounced for birthweight \>4500 g (Supplementary Tables S1 and S2).

## 3.2 Model performance and comparison with fetal growth chart–based benchmarks

Receiver operating characteristic curves for the four logistic regression models are shown in Figure 1. For prediction of birthweight \>4000 g, Model 3 and the Combined model showed the highest discrimination, <span style="color:red">with AUROCs of 0.743 (95% confidence interval 0.719–0.765) and 0.742 (0.717–0.764), respectively. Compared with Model 1 (0.638, 0.612–0.661), the paired AUROC difference was 0.105 (0.081–0.128) for Model 3 and 0.104 (0.081–0.129) for the Combined model. Model 2 (0.661, 0.635–0.684) showed a smaller improvement over Model 1 (difference 0.023, 0.013–0.037), and the Combined model did not improve on Model 3 (difference −0.001, −0.003 to 0.003). The estimates for Model 1 were obtained in the common analytic cohort with complete follow-up to Visit 3. Paired AUROC differences for all model comparisons are provided in Supplementary Table S5.</span>

WHO fetal growth chart–based percentile variables yielded lower discrimination <span style="color:red">than Model 3 and the Combined model</span>. At Visit 2, the AUROC ranged from 0.54 to 0.59 for prediction of birthweight \>4000 g. At Visit 3, performance improved to a range of 0.61–0.70, with the highest value observed for abdominal circumference percentile (0.70)<span style="color:red"> and a value of 0.68 for estimated fetal weight percentile</span>. <span style="color:red">However, Model 1 showed lower discrimination than the stronger Visit-3 WHO-derived percentiles.</span> Full WHO chart–based results are summarized in Table <span style="color:red">3</span>.

For prediction of birthweight \>4500 g, Model 3 and the Combined model again showed the best discrimination, with AUROCs of <span style="color:red">0.829 (0.785–0.874) and 0.831 (0.788–0.876)</span>, respectively, compared with <span style="color:red">0.731 (0.680–0.780)</span> for Model 1 and <span style="color:red">0.737 (0.685–0.786)</span> for Model 2. <span style="color:red">The paired AUROC difference relative to Model 1 was 0.098 (0.064–0.142) for Model 3 and 0.100 (0.061–0.139) for the Combined model, whereas Visit-2 information added little (Model 2 vs Model 1: 0.006, −0.006 to 0.019; Combined model vs Model 3: 0.002, −0.001 to 0.004).</span> WHO chart–based percentile variables yielded <span style="color:red">AUROCs of 0.54–0.64 at Visit 2 and 0.68–0.79 at Visit 3</span>. Among the WHO-derived measures, estimated fetal weight percentile was the most clinically interpretable single comparator<span style="color:red"> (0.77 at Visit 3)</span>, whereas abdominal circumference percentile provided the highest Visit-3 AUROC (0.79). <span style="color:red">As for birthweight \>4000 g, Model 1 showed lower discrimination than these Visit-3 percentiles, whereas the point estimates for Model 3 and the Combined model were higher.</span><!-- 待重跑：Combined vs Model 3 的 CI (−0.001 to 0.004) --> A supplementary comparison using INTERGROWTH-21st fetal ultrasound percentiles is provided in Supplementary Table S11. The INTERGROWTH-21st comparators showed a similar descriptive pattern to the WHO chart–based comparators, with stronger discrimination for Visit 3 than Visit 2 ultrasound percentiles. For birthweight \>4000 g, Visit-3 abdominal circumference and estimated fetal weight percentiles achieved AUROCs of 0.71 and 0.69, respectively. For birthweight \>4500 g, the corresponding AUROCs were 0.80 and 0.79. These results were closely aligned with the WHO-based comparator pattern, in which abdominal circumference and estimated fetal weight–related percentiles were among the strongest single ultrasound measures.

Additional performance metrics for the final models are provided in Supplementary Table S5 and Supplementary Figure S2. <span style="color:red">For the Combined model, the AUPRC was 0.209 (95% CI 0.181–0.240) for birthweight \>4000 g and 0.066 (0.042–0.107) for birthweight \>4500 g. After Platt recalibration, calibration slopes ranged from 0.992 to 1.017, calibration-in-the-large from −0.018 to −0.001, and O/E ratios from 0.983 to 0.999 across the four models for both outcomes. The Brier score of the Combined model was 0.0687 for birthweight \>4000 g and 0.0116 for birthweight \>4500 g, corresponding to scaled Brier scores of 6.0% and 2.9%; scaled Brier scores were low for all models, as expected for outcomes with low prevalence.</span> Supplementary Figure S2 shows the corresponding calibration plots.

Threshold-based operating characteristics are shown in Supplementary Table S8. For birthweight \>4000 g, the Combined model classified 1,275 pregnancies as screen-positive at the upper-quintile threshold and captured <span style="color:red">239</span> of 505 cases, with a sensitivity of <span style="color:red">47.3%</span>, specificity of <span style="color:red">82.3%</span>, positive predictive value (PPV) of <span style="color:red">18.7%</span>, and negative predictive value (NPV) of <span style="color:red">94.8%</span>. At the upper-decile threshold, it captured <span style="color:red">147</span> of 505 cases, with a sensitivity of <span style="color:red">29.1%</span>, specificity of <span style="color:red">91.6%</span>, PPV of <span style="color:red">23.0%</span>, and NPV of <span style="color:red">93.8%</span>.

For birthweight \>4500 g, Model 3 and the Combined model had similar operating characteristics. <span style="color:red">At the upper-quintile threshold, Model 3 captured 56 of 77 cases, with a sensitivity of 72.7%, specificity of 80.6%, PPV of 4.4%, and NPV of 99.6%; the Combined model captured 54 of 77 cases, with a sensitivity of 70.1%, specificity of 80.6%, PPV of 4.2%, and NPV of 99.5%.</span> At the upper-decile threshold, Model 3 captured 36 of 77 cases, with a sensitivity of 46.8%, specificity of 90.4%, PPV of 5.6%, and NPV of 99.3%; the Combined model captured 35 of 77 cases, with a sensitivity of 45.5%, specificity of 90.4%, PPV of 5.5%, and NPV of 99.3%.

Decision-curve analysis for the two primary macrosomia outcomes is shown in Supplementary Figure S5. The decision curves summarize net benefit across threshold-probability ranges using <span style="color:red">recalibrated</span> out-of-fold predicted probabilities and are intended to illustrate <span style="color:red">model behavior</span> rather than <span style="color:red">to establish clinical utility or</span> define recommended intervention thresholds.

<span style="color:red">In the model-complexity analysis for birthweight \>4500 g (Supplementary Table S14), the local approximate effective degrees of freedom of the penalized Combined model was 24.2, compared with 65 candidate predictors. Retaining 13 or 10 predictors selected within each training fold reduced the effective degrees of freedom to 3.7 and 3.0, respectively, with AUROCs of 0.813 (0.764–0.859) and 0.803 (0.752–0.851), compared with 0.828 (0.783–0.873) for the full model within the same framework. The paired AUROC differences relative to the full model were −0.015 (−0.044 to 0.011) and −0.025 (−0.057 to 0.007), and calibration slopes after Platt recalibration were 1.056 and 1.010, respectively.</span>

Sensitivity analyses using gestational-age-adjusted LGA outcomes supported the same staged prediction pattern. LGA90 occurred in 1,319 pregnancies (20.7%) and LGA97 in 470 pregnancies (7.4%). For LGA90, AUROC increased from <span style="color:red">0.620 (95% CI 0.604–0.637)</span> in <span style="color:red">Model 1</span> to <span style="color:red">0.731 (0.716–0.745)</span> in <span style="color:red">Model 3</span>. For LGA97, AUROC increased from <span style="color:red">0.651 (0.626–0.675)</span> to <span style="color:red">0.758 (0.734–0.780)</span>. AUPRC also improved after incorporation of later ultrasound information. Full discrimination and calibration results for the LGA sensitivity outcomes are provided in Supplementary Table S4, with calibration plots shown in Supplementary Figure S3.

A separate model-form comparison using random forest, XGBoost, and gradient boosting is reported in Supplementary Table S9. These non-linear classifiers followed the same visit-updated performance pattern and did not show a consistent advantage over logistic regression.<!-- 待 S9 重算后核对 -->

<span style="color:red">In the limited evaluation in the MMC cohort (12,043 delivery records; 1,142 \[9.5%\] with birthweight \>4000 g and 134 \[1.1%\] with birthweight \>4500 g), the reduced six-predictor early-pregnancy model applied with the nuMoM2b coefficients yielded AUROCs of 0.597 (0.580–0.613) and 0.636 (0.589–0.681), respectively. In internal validation in nuMoM2b, the same reduced model achieved AUROCs of 0.603 (0.577–0.627) and 0.615 (0.556–0.678), which were lower than those of the full Model 1 (Supplementary Table S13).</span>

## 3.3 Feature contributions of the combined model

The 20 predictors with the largest absolute standardized logistic regression coefficients in the Combined model are shown in Figures 2 and 3 for birthweight \>4000 g and \>4500 g, respectively. Overall, the most influential predictors were concentrated in maternal anthropometry, gestational weight gain, and second- and third-trimester fetal biometry. These results were consistent with the univariate analyses and support the incremental value of incorporating later ultrasound measurements into the visit-updated prediction framework. Coefficients are presented as mean and standard deviation across cross-validation folds.

## 3.4 Periconceptional diet component analysis

The distribution of total diet quality scores is shown in Figure 4. Pregnancies resulting in macrosomia generally had slightly higher overall periconceptional diet quality scores; however, component-level comparisons indicated that most effect sizes were small (Supplementary Tables S1–S2). Sequential ablation of diet components within Model 1 showed that removal of individual components did not materially change discrimination for birthweight \>4000 g (<span style="color:red">Supplementary Figure S6</span>), whereas for birthweight \>4500 g, removal of the Alternative Healthy Eating Index alcoholic drinks component produced the largest reduction in model performance (<span style="color:red">Supplementary Figure S7</span>).

Because the Alternative Healthy Eating Index alcoholic drinks component showed the largest change in <span style="color:red">this</span> exploratory ablation analysis for birthweight \>4500 g, we performed a post-hoc multivariable logistic regression analysis adjusted for early-pregnancy maternal sociodemographic and clinical characteristics, including age, BMI, income, race and ethnicity, smoking, gravidity, and preexisting diabetes. Compared with the non-alcohol group, moderate periconceptional alcohol intake was associated with higher odds of birthweight \>4500 g (adjusted odds ratio 2.76, 95% CI 1.31–5.83). <span style="color:red">In an additional sensitivity analysis</span>, the alcohol-related variable was not materially associated with gestational age at delivery or with preterm or early-term delivery (Supplementary Table S6).

# 4. Discussion

## 4.1 Principal findings

In this secondary analysis of a large prospective cohort of nulliparous singleton pregnancies in the United States, we developed and internally validated visit-updated multivariable logistic regression models for predicting macrosomia. Three main findings emerged. First, routinely available early-pregnancy maternal characteristics and anthropometric measurements provided <span style="color:red">moderate</span> risk stratification for birthweight \>4000 g and \>4500 g. Second, model performance improved when second- and third-trimester ultrasound information was added, with the best discrimination observed for Model 3 and the Combined model. Exploratory diet-component analyses suggested that most individual dietary components contributed limited incremental predictive information, with one post-hoc alcohol-related finding requiring cautious interpretation.

<span style="color:red">Although the early-pregnancy model did not reach the discrimination of the stronger third-trimester WHO chart–based ultrasound percentiles, it relies on information that is available several months earlier in pregnancy. Once Visit-3 ultrasound information was incorporated, the visit-updated models showed higher point estimates than all WHO chart–based comparators, and most of the incremental discrimination was attributable to Visit-3 rather than Visit-2 information.</span> Taken together, these findings support the potential role of early maternal data for initial risk stratification and of later ultrasound data for refinement of risk estimation across gestation.

Sensitivity analyses using LGA90 and LGA97 showed a similar visit-updated pattern, even though LGA and fixed birthweight thresholds represent related but distinct definitions of fetal overgrowth. Discrimination improved after incorporation of Visit-3 ultrasound information for both LGA outcomes, suggesting that the incremental value of later pregnancy information was not limited to fixed birthweight-threshold outcomes. The present analysis focused on birthweight-defined fetal overgrowth rather than downstream delivery complications such as postpartum hemorrhage, shoulder dystocia, or birth trauma, which may also depend on delivery management and other clinical factors beyond fetal size alone.

## 4.2 Comparison with previous studies

Our findings are consistent with previous studies showing that third-trimester ultrasound generally provides better discrimination for macrosomia than earlier ultrasound measurements \[13,14\]. This is clinically plausible, because fetal overgrowth becomes more apparent with advancing gestation and later biometric measurements better capture cumulative growth patterns. At the same time, our results highlight the limitations of relying only on later-pregnancy ultrasound, because such an approach leaves less opportunity for earlier risk stratification and preventive counseling.

Compared with prior prediction studies, our study adds to the literature in three ways. First, it focuses specifically on nulliparous pregnancies, in which prediction is more challenging because previous obstetric history is unavailable \[35\]. Second, it evaluates a visit-updated framework that reflects how information becomes available during routine antenatal care, rather than relying solely on near-term ultrasound \[13–18\]. Third, it benchmarks model performance against WHO fetal growth chart–based ultrasound percentiles, thereby providing a clinically interpretable reference for comparison \[26,27\]. The present study therefore provides a clinically oriented prediction framework developed and internally validated in a large prospective cohort, while further external validation is needed before routine clinical implementation.

Our dietary findings should be interpreted in the context of previous observational work. Existing evidence on the relation between maternal diet quality and macrosomia has been mixed \[36–39\]. In the nuMoM2b cohort, Yee et al. previously reported that higher pre-pregnancy diet quality was associated with increased odds of macrosomia \>4000 g \[40\]. Our results are broadly consistent with this observation at the overall diet-quality level, but the component-level analyses suggested that most individual dietary components contributed little incremental predictive information when considered separately.

The alcohol-related result requires particularly cautious interpretation. Although the Alternative Healthy Eating Index alcoholic drinks component emerged in the exploratory ablation analysis<span style="color:red">, which involved many dietary components,</span> and moderate periconceptional alcohol intake was associated with birthweight \>4500 g in adjusted models, this analysis was not designed to test a prespecified causal hypothesis. <span style="color:red">Additional analyses of gestational age at delivery did not show a material association with the alcohol-related variable; however, because alcohol exposure may itself influence gestational duration, these outcomes are not strict negative controls and do not exclude residual confounding.</span> The finding is also biologically counterintuitive in relation to the broader literature linking maternal alcohol exposure with impaired fetal growth rather than fetal overgrowth. It may therefore reflect residual confounding by socioeconomic status, maternal body composition, broader dietary or lifestyle patterns, or exposure misclassification related to self-reported food-frequency questionnaire data. Accordingly, this result should be regarded as hypothesis-generating only and should not be interpreted as causal or clinically actionable.

## 4.3 Clinical implications

The clinical value of early macrosomia prediction lies less in replacing ultrasound and more in enabling earlier risk stratification. In routine care, pregnancies identified as being at increased risk could be considered for closer monitoring of gestational weight gain, more individualized nutritional counseling, and greater attention to fetal growth across follow-up visits \[9,41–45\]. This may be particularly relevant in nulliparous pregnancies, where clinicians cannot rely on prior delivery history to guide risk assessment \[35\].

Our findings also suggest that a staged strategy may be more realistic than a single-time-point prediction approach. Early-pregnancy maternal data may be useful for initial screening, whereas later ultrasound measurements can refine risk estimates as pregnancy progresses. This interpretation is more clinically appropriate than positioning the model as a replacement for standard sonographic assessment. Rather, the proposed framework may complement existing care by identifying higher-risk pregnancies earlier than ultrasound-only approaches.

The threshold-based analyses translate the discrimination results into operating characteristics at fixed screening fractions. For birthweight \>4000 g, <span style="color:red">23.0%</span> of pregnancies in the highest decile of Combined-model predicted risk had the outcome, compared with an overall prevalence of 7.9%. This indicates that the upper-decile group had a higher observed event rate than the cohort average, although sensitivity at this threshold was <span style="color:red">29.1%</span>. For birthweight \>4500 g, the highest-risk strata also showed higher observed event rates than the overall prevalence of 1.2%, but the absolute positive predictive value remained modest, reaching 5.6% in the upper decile. These results are therefore best interpreted as describing screening yield at <span style="color:red">fixed</span> risk strata, rather than as defining thresholds for clinical intervention. <span style="color:red">Because no specific intervention or harm–benefit trade-off was defined, neither these analyses nor the decision-curve analysis establish clinical utility.</span>

## 4.4 Strengths and limitations

This study has several strengths. It was based on a large prospective multicenter cohort with standardized antenatal data collection \[19\]. The focus on nulliparous singleton pregnancies addresses a clinically important population in which macrosomia risk prediction is often more difficult. In addition, the visit-updated modeling strategy reflects the sequential availability of clinical information in routine care. Finally, we reported not only discrimination but also precision–recall performance and calibration, which strengthens the transparency of model evaluation.

Several limitations should also be acknowledged. First, this was a secondary analysis and all performance estimates were derived from internal validation only; external validation in independent populations is required before clinical implementation. <span style="color:red">In a limited evaluation in an independent Dutch cohort, a reduced early-pregnancy model restricted to six harmonizable predictors showed discrimination similar to that observed for the same reduced model in nuMoM2b (Supplementary Table S13). This analysis did not include periconceptional diet, most Visit-1 anthropometric measurements, or serial ultrasound measurements, included multiparous women, and assessed discrimination only; it therefore does not constitute external validation of the full visit-updated models.</span> Second, the cohort consisted of nulliparous singleton pregnancies from the United States, which may limit generalizability to other populations and care settings. Third, ultrasound data near delivery were not available, which restricts comparison with models based on near-term fetal biometry and may underestimate the performance achievable with later gestational data. In addition, because estimated fetal weight was derived using the Hadlock formula, possible underestimation of fetal weight at the upper extremes should be considered when interpreting EFW-based predictors and chart-based comparators. Relatedly, although we added LGA90 and LGA97 sensitivity analyses to account for gestational age at delivery, absolute macrosomia and LGA should not be interpreted interchangeably. Future studies should determine which fetal overgrowth definition best predicts delivery and neonatal complications. Fourth, periconceptional dietary intake was assessed using the Block 2005 Food Frequency Questionnaire, which relied on self-reported recall of usual intake during the 3 months around conception and was therefore subject to recall bias and exposure misclassification. Dietary intake was not assessed longitudinally across pregnancy, limiting inference about changes in diet over time. The requirement for complete periconceptional diet and serial Visit 2/Visit 3 ultrasound data may also have introduced selection bias. Although this restriction was necessary for evaluating visit-updated models incorporating diet and antenatal ultrasound information, the included-versus-excluded comparison suggested that data completeness and follow-up were not entirely random. <span style="color:red">In particular, Model 1 was evaluated only among pregnancies with subsequent complete dietary and ultrasound data, so its performance may not reflect that in all pregnancies eligible at Visit 1. In addition, prediction of birthweight \>4500 g was based on only 77 events; although the model-complexity analysis suggested that most of the discrimination was retained with substantially fewer predictors, estimates for this outcome remain imprecise and should be interpreted cautiously.</span> Fifth, although the WHO fetal growth chart provided an interpretable benchmark, direct comparison with our internally derived models should be made cautiously because the WHO chart was developed from a different reference population and was not calibrated to the same dataset. Finally, the alcohol-related finding was exploratory, post hoc, and based on self-reported periconceptional intake. Given the small number of birthweight \>4500 g cases and the potential for residual confounding, recall bias, and exposure misclassification, this association should not be interpreted as causal and requires independent confirmation.

# 5. Conclusion

In nulliparous singleton pregnancies, routinely available early-pregnancy maternal characteristics and anthropometry provided <span style="color:red">moderate</span> risk stratification for macrosomia, while later ultrasound measurements improved performance further. The proposed visit-updated framework may support earlier identification of pregnancies at increased risk, but external validation is needed before clinical use.


# Declarations

## Funding Information
This study was performed within the framework of the Eindhoven MedTech Innovation Center and was supported by the China Scholarship Council (grant number 201906340168). The funder had no role in study design, data collection, data analysis, data interpretation, or manuscript preparation.

## Conflict of Interest Statement
The authors declare no conflicts of interest.

## Ethics Statement
This study analyzed de-identified data from the nuMoM2b dataset. The Eunice Kennedy Shriver National Institute of Child Health and Human Development review board (approval date: December 15, 2021, request ID: 11961) and Eindhoven University of Technology ethical review board (approval date: November 1, 2021, reference number: ERB2021BME4) approved the study protocol. <span style="color:red">The retrospective analysis of the MMC data was approved by the Medical Ethics Review Committee of Máxima Medical Center, which waived the requirement for informed consent \[33\]. </span>Our study complied with all relevant ethical regulations, including the Declaration of Helsinki and the Good Clinical Practice Guidelines.

## Data Availability Statement
The data that support the findings of this study are available from the Eunice Kennedy Shriver National Institute of Child Health and Human Development Data and Specimen Hub upon application and approval. Restrictions apply to the availability of these data. <span style="color:red">The MMC data are not publicly available because of privacy regulations; further information is available from the corresponding author upon reasonable request.</span>

## Consent to participate

Informed consent was obtained from all subjects involved in the original nuMoM2b study.

## Author Contributions

**Yanqi Wu** contributed to the conceptualization, study design, data interpretation, statistical analysis, visualization, and drafting of the manuscript.

**Sima Asvadi** contributed to the conceptualization, study design, data interpretation, and critical revision of the manuscript.

**Myrthe van der Ven** contributed to the methodology, supervision, data interpretation, and critical revision of the manuscript.

**Elisabetta Peri** contributed to the methodology, supervision, statistical analysis, and critical revision of the manuscript.

**M. Beatrijs van der Hout-van der Jagt** contributed to data curation, statistical analysis, and critical revision of the manuscript.

**S. Guid Oei** contributed to the methodology, supervision, and critical revision of the manuscript. **Massimo Mischi** was involved in project administration, supervision, and manuscript editing.

**Xi Long** contributed to project administration, supervision, investigation, conceptualization, study design, and critical revision of the manuscript. All authors read and approved the final manuscript.

# References

\[1\] Boulet SL, Alexander GR, Salihu HM, Pass M (2003) Macrosomic births in the United States: determinants, outcomes, and proposed grades of risk. Am J Obstet Gynecol 188:1372–1378

\[2\] Grassi AE, Giuliano MA (2000) The neonate with macrosomia. Clin Obstet Gynecol 43:340–348

\[3\] Langer O (2000) Fetal macrosomia: etiologic factors. Clin Obstet Gynecol 43:283–297

\[4\] Rossi AC, Mullin P, Prefumo F (2013) Prevention, management, and outcomes of macrosomia: a systematic review and meta-analysis. Obstet Gynecol Surv 68:702–709

\[5\] Li G, Kong L, Li Z, et al. (2014) Prevalence of macrosomia and its risk factors in China: a multicentre survey based on birth data involving 101,723 singleton term infants. Paediatr Perinat Epidemiol 28:345–350

\[6\] Salihu HM, Dongarwar D, King LM, Yusuf KK, Ibrahimi S, Salinas-Miranda AA (2020) Trends in the incidence of fetal macrosomia and its phenotypes in the United States, 1971-2017. Arch Gynecol Obstet 301:415–426

\[7\] Hui AL, Back L, Ludwig S, et al. (2014) Effects of lifestyle intervention on dietary intake, physical activity level, and gestational weight gain in pregnant women with different pre-pregnancy body mass index in a randomized control trial. BMC Pregnancy Childbirth 14:331

\[8\] Gardner B, Wardle J, Poston L, Croker H (2011) Changing diet and physical activity to reduce gestational weight gain: a meta-analysis. Obes Rev 12:e602–e620

\[9\] Zheng W, Yan X, Liang S, et al. (2024) The reduction in macrosomia prevalence over a decade following the intensive intervention programs. Glob Transit 6:187–193

\[10\] Milner J, Arezina J (2018) The accuracy of ultrasound estimation of fetal weight in comparison to birth weight: a systematic review. Ultrasound 26:32–41

\[11\] Shamshuzzoha M, Islam MM (2023) Early prediction model of macrosomia using machine learning for clinical decision support. Diagnostics (Basel) 13:2754

\[12\] Poon LC, Karagiannis G, Stratieva V, Syngelaki A, Nicolaides KH (2011) First-trimester prediction of macrosomia. Fetal Diagn Ther 29:139–147

\[13\] Ewington L, Black N, Leeson C, et al. (2024) Maternal, pregnancy, and birth characteristics predicting large for gestational age: a systematic review. BJOG 131:1591–1602

\[14\] Erkamp JS, Voerman E, Steegers EAP, et al. (2020) Second and third trimester fetal ultrasound population screening for risks of preterm birth and small-size and large-size for gestational age at birth: a population-based prospective cohort study. BMC Med 18:63

\[15\] Papastefanou I, Pilalis A, Chrelias C, Kassanos D, Souka AP (2014) Screening for birth weight deviations by second and third trimester ultrasound scan. Prenat Diagn 34:759–764

\[16\] Papastefanou I, Souka AP, Pilalis A, Eleftheriades M, Michalitsi V, Kassanos D (2012) First trimester prediction of small- and large-for-gestation neonates by an integrated model incorporating ultrasound parameters, biochemical indices and maternal characteristics. Acta Obstet Gynecol Scand 91:104–111

\[17\] Zhang J, Kim S, Grewal J, Albert PS (2012) Predicting large fetuses at birth: do multiple ultrasound examinations and longitudinal statistical modelling improve prediction? Paediatr Perinat Epidemiol 26:199–207

\[18\] Plasencia W, González Dávila E, Tetilla V, Padrón Pérez E, García Hernández JA, González NLG (2012) First-trimester screening for large-for-gestational-age infants. Ultrasound Obstet Gynecol 39:389–395

\[19\] Haas DM, Parker CB, Wing DA, et al. (2015) A description of the methods of the Nulliparous Pregnancy Outcomes Study: Monitoring mothers-to-be (nuMoM2b). Am J Obstet Gynecol 212:539.e1–539.e24

\[20\] <span style="color:red">Villar J, Cheikh Ismail L, Victora CG, et al. (2014) International standards for newborn weight, length, and head circumference by gestational age and sex: the Newborn Cross-Sectional Study of the INTERGROWTH-21st Project. Lancet 384:857–868</span>

\[21\] Subar AF, Thompson FE, Kipnis V, et al. (2001) Comparative validation of the Block, Willett, and National Cancer Institute food frequency questionnaires: the Eating at America’s Table Study. Am J Epidemiol 154:1089–1099

\[22\] Guenther PM, Casavale KO, Reedy J, et al. (2013) Update of the Healthy Eating Index: HEI-2010. J Acad Nutr Diet 113:569–580

\[23\] U.S. Department of Agriculture and U.S. Department of Health and Human Services (2010) Report of the Dietary Guidelines Advisory Committee on the Dietary Guidelines for Americans, 2010 \[DietaryGuidelines.gov website\]. <https://www.dietaryguidelines.gov/sites/default/files/2019-05/2010DGACReport-camera-ready-Jan11-11.pdf>

\[24\] Chiuve SE, Fung TT, Rimm EB, et al. (2012) Alternative dietary indices both strongly predict risk of chronic disease. J Nutr 142:1009–1018

\[25\] Hadlock FP, Harrist RB, Sharman RS, Deter RL, Park SK (1985) Estimation of fetal weight with the use of head, body, and femur measurements—a prospective study. Am J Obstet Gynecol 151:333–337

\[26\] Kiserud T, Piaggio G, Carroli G, et al. (2017) The World Health Organization fetal growth charts: a multinational longitudinal study of ultrasound biometric measurements and estimated fetal weight. PLoS Med 14:e1002220

\[27\] Kiserud T, Benachi A, Hecher K, et al. (2018) The World Health Organization fetal growth charts: concept, findings, interpretation, and application. Am J Obstet Gynecol 218:S619–S629

\[28\] <span style="color:red">Papageorghiou AT, Ohuma EO, Altman DG, et al. (2014) International standards for fetal growth based on serial ultrasound measurements: the Fetal Growth Longitudinal Study of the INTERGROWTH-21st Project. Lancet 384:869–879</span>

\[29\] <span style="color:red">Stirnemann J, Salomon LJ, Papageorghiou AT (2020) INTERGROWTH-21st standards for Hadlock’s estimation of fetal weight. Ultrasound Obstet Gynecol 56:946–948</span>

\[30\] Steyerberg EW (2019) Clinical Prediction Models: A Practical Approach to Development, Validation, and Updating, 2nd ed. Springer, Cham

\[31\] Berrar D (2018) Cross-validation. In: Ranganathan S, Gribskov M, Nakai K, Schönbach C (eds) Encyclopedia of Bioinformatics and Computational Biology. Elsevier, Amsterdam, pp 542–545

\[32\] Riley RD, Snell KIE, Ensor J, et al. (2019) Minimum sample size for developing a multivariable prediction model: Part II—binary and time-to-event outcomes. Stat Med 38:1276–1296

\[33\] <span style="color:red">Wu Y, Hamelmann P, van der Ven M, et al. (2024) Early prediction of gestational diabetes mellitus using maternal demographic and clinical risk factors. BMC Res Notes 17:105</span>

\[34\] Collins GS, Moons KGM, Dhiman P, et al. (2024) TRIPOD+AI statement: updated guidance for reporting clinical prediction models that use regression or machine learning methods. BMJ 385:e078378

\[35\] Jeffers E, Dodds L, Allen V, Woolcott C (2017) Predicting the risk of macrosomia at mid-pregnancy among non-diabetics: a retrospective cohort study. J Obstet Gynaecol Can 39:1129–1136

\[36\] Grandy M, Snowden JM, Boone-Heinonen J, Purnell JQ, Thornburg KL, Marshall NE (2018) Poorer maternal diet quality and increased birth weight. J Matern Fetal Neonatal Med 31:1613–1619

\[37\] Santos IdS, Crivellenti LC, Franco LJ, Sartorelli DS (2021) Relationship between the quality of the pregnant woman’s diet and birth weight: a prospective cohort study. Eur J Clin Nutr 75:1819–1828

\[38\] Zhu Y, Hedderson MM, Sridhar S, Xu F, Feng J, Ferrara A (2019) Poor diet quality in pregnancy is associated with increased risk of excess fetal growth: a prospective multi-racial/ethnic cohort study. Int J Epidemiol 48:423–432

\[39\] Raghavan R, Dreibelbis C, Kingshipp BL, et al. (2019) Dietary patterns before and during pregnancy and birth outcomes: a systematic review. Am J Clin Nutr 109:729S–756S

\[40\] Yee LM, Silver RM, Haas DM, et al. (2020) Quality of periconceptional dietary intake and maternal and neonatal outcomes. Am J Obstet Gynecol 223:121.e1–121.e8

\[41\] Araujo Júnior E, Peixoto AB, Zamarian ACP, Elito Júnior J, Tonni G (2017) Macrosomia. Best Pract Res Clin Obstet Gynaecol 38:83–96

\[42\] Walsh JM, McGowan CA, Mahony R, Foley ME, McAuliffe FM (2012) Low glycaemic index diet in pregnancy to prevent macrosomia (ROLO study): randomised control trial. BMJ 345:e5605

\[43\] American College of Obstetricians and Gynecologists (2020) Macrosomia: ACOG Practice Bulletin, Number 216. Obstet Gynecol 135:e18–e35

\[44\] Muktabhant B, Lawrie TA, Lumbiganon P, Laopaiboon M (2015) Diet or exercise, or both, for preventing excessive weight gain in pregnancy. Cochrane Database Syst Rev 2015:CD007145

\[45\] International Weight Management in Pregnancy (i-WIP) Collaborative Group (2017) Effect of diet and physical activity based interventions in pregnancy on gestational weight gain and pregnancy outcomes: meta-analysis of individual participant data from randomised trials. BMJ 358:j3119

# Figure legends

**Figure 1. Receiver operating characteristic curves of the visit-updated logistic regression models for prediction of macrosomia.** (a) Prediction of birthweight \>4000 g. (b) Prediction of birthweight \>4500 g.

**Figure 2. Twenty predictors with the largest absolute standardized logistic regression coefficients in the Combined model for prediction of birthweight \>4000 g.** Bars extending to the right indicate positive coefficients and bars extending to the left indicate negative coefficients. Error bars represent standard deviation across cross-validation folds.

**Figure 3. Twenty predictors with the largest absolute standardized logistic regression coefficients in the Combined model for prediction of birthweight \>4500 g.** Bars extending to the right indicate positive coefficients and bars extending to the left indicate negative coefficients. Error bars represent standard deviation across cross-validation folds.

**Figure 4. Distribution of total periconceptional diet quality scores according to birthweight category.**

**(a) Alternative Healthy Eating Index-2010 total score. (b) Healthy Eating Index-2010 total score.** Scores are shown for pregnancies with birthweight \>4500 g, birthweight 4000–4500 g, and <span style="color:red">birthweight ≤4000 g</span>.

# Tables

## Table 1. Pregnancy characteristics by birthweight category (\>4500 g, 4000–4500 g, and <span style="color:red">≤4000 g</span>).

<table>
<colgroup>
<col style="width: 32%" />
<col style="width: 23%" />
<col style="width: 23%" />
<col style="width: 19%" />
</colgroup>
<thead>
<tr class="header">
<th>Characteristics</th>
<th>birthweight &gt;4500 g N=77</th>
<th>birthweight between 4000 and 4500 g N=428</th>
<th><p>birthweight <span style="color:red">≤4000 g</span></p>
<p>N=5866</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td colspan="4"><em>Preliminary maternal characteristics</em></td>
</tr>
<tr class="even">
<td>Age, mean (SD), years</td>
<td>29.3 (5.1) <sup>a</sup></td>
<td>28.2 (5.3) <sup>a</sup></td>
<td>27.3 (5.6)</td>
</tr>
<tr class="odd">
<td>Pre-pregnancy BMI, mean (SD), kg/m<sup>2</sup></td>
<td>28.4 (7.5) <sup>a</sup></td>
<td>26.8 (6.1) <sup>a</sup></td>
<td>25.3 (6.1)</td>
</tr>
<tr class="even">
<td>Smoked in 3 months before pregnancy, N (%)</td>
<td>9 (11.7)</td>
<td>79 (18.5)</td>
<td>990 (16.8)</td>
</tr>
<tr class="odd">
<td>Preexisting diabetes mellitus, N (%)</td>
<td>2 (2.6)</td>
<td>7 (1.6)</td>
<td>79 (1.3)</td>
</tr>
<tr class="even">
<td>Fetal sex (Male), N (%)</td>
<td>55 (71.4) <sup>a</sup></td>
<td>279 (65.2) <sup>a</sup></td>
<td>2910 (49.6)</td>
</tr>
<tr class="odd">
<td>Gravidity, mean (SD), times</td>
<td>1.3 (0.6)</td>
<td>1.3 (0.6)</td>
<td>1.3 (0.6)</td>
</tr>
<tr class="even">
<td>GDM, N (%)</td>
<td>5 (6.5)</td>
<td>31 (7.2)</td>
<td>248 (4.2)</td>
</tr>
<tr class="odd">
<td>Race and Ethnicity</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td><ul>
<li><p>Non-Hispanic White, N (%)</p></li>
</ul></td>
<td>51 (66.2)</td>
<td>310 (72.4) <sup>a</sup></td>
<td>3720 (63.4)</td>
</tr>
<tr class="odd">
<td><ul>
<li><p>Non-Hispanic Black, N (%)</p></li>
</ul></td>
<td>4 (5.2)</td>
<td>34 (7.9) <sup>a</sup></td>
<td>656 (11.2)</td>
</tr>
<tr class="even">
<td><ul>
<li><p>Hispanic, N (%)</p></li>
</ul></td>
<td>17 (22.1) <sup>b</sup></td>
<td>55 (12.9)</td>
<td>950 (16.2)</td>
</tr>
<tr class="odd">
<td><ul>
<li><p>Other/Unknown, N (%)</p></li>
</ul></td>
<td>5 (6.5)</td>
<td>29 (6.8)</td>
<td>540 (9.2)</td>
</tr>
<tr class="even">
<td>Income level (percentage to poverty line) mean, (SD)</td>
<td>544.0 (292.4) <sup>a</sup></td>
<td>491.3 (284.7) <sup>a</sup></td>
<td>449.4 (292.1)</td>
</tr>
<tr class="odd">
<td colspan="4"><em>Clinical anthropometry</em></td>
</tr>
<tr class="even">
<td>BMI at visit 1, mean (SD), kg/m<sup>2</sup></td>
<td>29.9 (7.8) <sup>a b</sup></td>
<td>27.8 (6.2) <sup>a</sup></td>
<td>26.1 (6.2)</td>
</tr>
<tr class="odd">
<td>SBP at visit 1, mean (SD), mmHg</td>
<td>112.0 (10.1) <sup>a b</sup></td>
<td>109.7 (10.0)</td>
<td>109.0 (10.7)</td>
</tr>
<tr class="even">
<td>DBP at visit 1, mean (SD), mmHg</td>
<td>68.4 (9.0) <sup>a</sup></td>
<td>67.8 (7.9) <sup>a</sup></td>
<td>67.0 (8.3)</td>
</tr>
<tr class="odd">
<td>SBP at visit 2, mean (SD), mmHg</td>
<td>111.7 (11.9)</td>
<td>110.7 (10.0) <sup>a</sup></td>
<td>109.4 (10.5)</td>
</tr>
<tr class="even">
<td>DBP at visit 2, mean (SD), mmHg</td>
<td>67.7 (8.5)</td>
<td>66.9 (7.7)</td>
<td>66.4 (8.2)</td>
</tr>
<tr class="odd">
<td>SBP at visit 3, mean (SD), mmHg</td>
<td>112.2 (9.8)</td>
<td>111.3 (11.3) <sup>a</sup></td>
<td>110.2 (10.9)</td>
</tr>
<tr class="even">
<td>DBP at visit 3, mean (SD), mmHg</td>
<td>67.7 (8.6)</td>
<td>67.0 (8.5)</td>
<td>66.8 (8.5)</td>
</tr>
<tr class="odd">
<td>Hip circumference at visit 1, mean (SD), cm</td>
<td>112.4 (16.2) <sup>a</sup> <sup>b</sup></td>
<td>107.4 (12.8) <sup>a</sup></td>
<td>103.8 (12.4)</td>
</tr>
<tr class="even">
<td>Neck circumference at visit 1, mean (SD), cm</td>
<td>34.6 (3.1) <sup>a b</sup></td>
<td>33.7 (2.9) <sup>a</sup></td>
<td>32.7 (2.9)</td>
</tr>
<tr class="odd">
<td>Waist circumference at visit 1, mean (SD), cm</td>
<td>90.2 (15.8) <sup>a b</sup></td>
<td>86.2 (13.9) <sup>a</sup></td>
<td>82.3 (12.8)</td>
</tr>
<tr class="even">
<td>Waist over iliac crest circumference at visit 1, mean (SD), cm</td>
<td>103.2 (16.6) <sup>a b</sup></td>
<td>98.6 (14.5) <sup>a</sup></td>
<td>94.4 (14.0)</td>
</tr>
<tr class="odd">
<td>GWG at visit 1, mean (SD), kg</td>
<td>3.1 (3.6)</td>
<td>2.7 (4.3) <sup>a</sup></td>
<td>2.1 (3.7)</td>
</tr>
<tr class="even">
<td>GWG at visit 2, mean (SD), kg</td>
<td>6.2 (7.7) <sup>a</sup></td>
<td>5.7 (4.9) <sup>a</sup></td>
<td>4.6 (4.7)</td>
</tr>
<tr class="odd">
<td>GWG at visit 3, mean (SD), kg</td>
<td>11.8 (5.6) <sup>a</sup></td>
<td>11.0 (6.4) <sup>a</sup></td>
<td>9.5 (5.3)</td>
</tr>
<tr class="even">
<td colspan="4"><em>(Part of) Periconceptional diet characteristics</em></td>
</tr>
<tr class="odd">
<td>Healthy Eating Index - total score, mean (SD),</td>
<td>65.9 (11.2) <sup>a</sup></td>
<td>64.9 (11.9) <sup>a</sup></td>
<td>63.0 (12.6)</td>
</tr>
<tr class="even">
<td>Alternative Healthy Eating Index - total score, mean (SD),</td>
<td>59.2 (10.9) <sup>a</sup></td>
<td>56.6 (12.0) <sup>a</sup></td>
<td>55.1 (12.6)</td>
</tr>
<tr class="odd">
<td colspan="4"><em>Ultrasound measurement at second and third trimester</em></td>
</tr>
<tr class="even">
<td>GA at visit 2, mean (SD), weeks</td>
<td>18.3 (1.5)</td>
<td>18.5 (1.5) <sup>a</sup></td>
<td>18.3 (1.5)</td>
</tr>
<tr class="odd">
<td>BPD at visit 2, mean (SD), cm</td>
<td>4.5 (0.5)</td>
<td>4.5 (0.5)</td>
<td>4.4 (0.5)</td>
</tr>
<tr class="even">
<td>HC at visit 2, mean (SD), cm</td>
<td>16.9 (1.9) <sup>a</sup></td>
<td>16.9 (1.9) <sup>a</sup></td>
<td>16.4 (1.8)</td>
</tr>
<tr class="odd">
<td>AC at visit 2, mean (SD), cm</td>
<td>14.8 (1.8) <sup>a</sup></td>
<td>14.7 (1.9) <sup>a</sup></td>
<td>14.2 (1.8)</td>
</tr>
<tr class="even">
<td>FL at visit 2, mean (SD), cm</td>
<td>3.0 (0.4)</td>
<td>3.1 (0.5) <sup>a</sup></td>
<td>3.0 (0.5)</td>
</tr>
<tr class="odd">
<td>EFW (Hadlock) at visit 2, mean (SD), grams</td>
<td>324.8 (93.6) <sup>a</sup></td>
<td>324.1 (100.5) <sup>a</sup></td>
<td>299.0 (88.8)</td>
</tr>
<tr class="even">
<td>GA at visit 3, mean (SD), weeks</td>
<td>27.0 (1.6)</td>
<td>27.1 (1.6) <sup>a</sup></td>
<td>26.8 (1.8)</td>
</tr>
<tr class="odd">
<td>BPD at visit 3, mean (SD), cm</td>
<td>7.5 (0.6) <sup>a b</sup></td>
<td>7.3 (0.6) <sup>a</sup></td>
<td>7.0 (0.6)</td>
</tr>
<tr class="even">
<td>HC at visit 3, mean (SD), cm</td>
<td>27.4 (2.0) <sup>a b</sup></td>
<td>26.9 (1.9) <sup>a</sup></td>
<td>26.0 (2.0)</td>
</tr>
<tr class="odd">
<td>AC at visit 3, mean (SD), cm</td>
<td>25.5 (2.1) <sup>a b</sup></td>
<td>24.7 (2.1) <sup>a</sup></td>
<td>23.4 (2.2)</td>
</tr>
<tr class="even">
<td>FL at visit 3, mean (SD), cm</td>
<td>5.5 (0.4) <sup>a b</sup></td>
<td>5.4 (0.5) <sup>a</sup></td>
<td>5.2 (0.5)</td>
</tr>
<tr class="odd">
<td>EFW (Hadlock) at visit 3, mean (SD), grams</td>
<td>1444.4 (315.8) <sup>a b</sup></td>
<td>1328.6 (295.4) <sup>a</sup></td>
<td>1172.6 (283.5)</td>
</tr>
<tr class="even">
<td>AFI - Quadrant 1 at visit 3, mean (SD), cm</td>
<td>4.5 (1.7) <sup>a</sup></td>
<td>4.3 (1.5) <sup>a</sup></td>
<td>4.0 (1.3)</td>
</tr>
<tr class="odd">
<td>AFI - Quadrant 2 at visit 3, mean (SD), cm</td>
<td>4.0 (1.4) <sup>a</sup></td>
<td>4.1 (1.4) <sup>a</sup></td>
<td>3.7 (1.3)</td>
</tr>
<tr class="even">
<td>AFI - Quadrant 3 at visit 3, mean (SD), cm</td>
<td>4.5 (1.5) <sup>a b</sup></td>
<td>4.0 (1.3) <sup>a</sup></td>
<td>3.8 (1.3)</td>
</tr>
<tr class="odd">
<td>AFI - Quadrant 4 at visit 3, mean (SD), cm</td>
<td>4.0 (1.6) <sup>a b</sup></td>
<td>3.7 (1.2) <sup>a</sup></td>
<td>3.6 (1.3)</td>
</tr>
</tbody>
</table>

<sup>a</sup> <span style="color:red">q value (Benjamini–Hochberg false discovery rate–adjusted p value)</span> \<0.05 in comparison with birthweight <span style="color:red">≤4000 g</span> group.

<sup>b</sup> <span style="color:red">q value</span> \<0.05 between birthweight \>4500 g and 4000-4500 g group

N: number; GDM: gestational diabetes mellitus; BMI: body mass index; SBP: systolic blood pressure; GWG: gestational weight gain; GA: gestational age; BPD: biparietal diameter; HC: head circumference; AC: abdominal circumference; FL: femur length; AFI: Amniotic Fluid Index; SD: standard deviation.

<span style="color:red">## Table 2. Predictors included in each prediction model and their time of availability.</span>

<table>
<thead>
<tr class="header">
<th><span style="color:red">Predictor domain (number of predictors)</span></th>
<th><span style="color:red">Predictors</span></th>
<th><span style="color:red">Time of availability</span></th>
<th><span style="color:red">Model 1</span></th>
<th><span style="color:red">Model 2</span></th>
<th><span style="color:red">Model 3</span></th>
<th><span style="color:red">Combined</span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span style="color:red">Maternal demographics and history (9)</span></td>
<td><span style="color:red">Age; race and ethnicity (non-Hispanic White, non-Hispanic Black, Hispanic, Asian or other; four binary indicators); income relative to the poverty threshold; smoking in the 3 months before pregnancy; pre-pregnancy BMI; preexisting diabetes mellitus</span></td>
<td><span style="color:red">Visit 1 (6–13 weeks)</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
</tr>
<tr class="even">
<td><span style="color:red">Periconceptional diet (25)</span></td>
<td><span style="color:red">Healthy Eating Index-2010: 12 component scores and total score; Alternative Healthy Eating Index-2010: 11 component scores and total score<sup>a</sup></span></td>
<td><span style="color:red">Visit 1 (Food Frequency Questionnaire at enrollment, covering the 3 months around conception)</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
</tr>
<tr class="odd">
<td><span style="color:red">Visit-1 maternal measurements (8)</span></td>
<td><span style="color:red">BMI; gestational weight gain; waist, waist over iliac crest, hip, and neck circumference; systolic and diastolic blood pressure</span></td>
<td><span style="color:red">Visit 1 (6–13 weeks)</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
</tr>
<tr class="even">
<td><span style="color:red">Visit-2 maternal measurements (3)</span></td>
<td><span style="color:red">Gestational weight gain; systolic and diastolic blood pressure</span></td>
<td><span style="color:red">Visit 2 (16–21 weeks)</span></td>
<td></td>
<td><span style="color:red">✓</span></td>
<td></td>
<td><span style="color:red">✓</span></td>
</tr>
<tr class="odd">
<td><span style="color:red">Visit-2 ultrasound (6)</span></td>
<td><span style="color:red">Gestational age at scan; BPD; HC; AC; FL; EFW</span></td>
<td><span style="color:red">Visit 2 (16–21 weeks)</span></td>
<td></td>
<td><span style="color:red">✓</span></td>
<td></td>
<td><span style="color:red">✓</span></td>
</tr>
<tr class="even">
<td><span style="color:red">Visit-3 maternal measurements (3)</span></td>
<td><span style="color:red">Gestational weight gain; systolic and diastolic blood pressure</span></td>
<td><span style="color:red">Visit 3 (22–29 weeks)</span></td>
<td></td>
<td></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
</tr>
<tr class="odd">
<td><span style="color:red">Visit-3 ultrasound (11)</span></td>
<td><span style="color:red">Gestational age at scan; BPD; HC; AC; FL; AFI quadrants 1–4; EFW; EFW percentile reported in nuMoM2b</span></td>
<td><span style="color:red">Visit 3 (22–29 weeks)</span></td>
<td></td>
<td></td>
<td><span style="color:red">✓</span></td>
<td><span style="color:red">✓</span></td>
</tr>
<tr class="even">
<td><span style="color:red">Total number of predictors</span></td>
<td></td>
<td></td>
<td><span style="color:red">42</span></td>
<td><span style="color:red">51</span></td>
<td><span style="color:red">56</span></td>
<td><span style="color:red">65</span></td>
</tr>
</tbody>
</table>

<span style="color:red"><sup>a</sup> Healthy Eating Index-2010 components: total vegetables; vegetables and legumes; total fruit; whole fruit; whole grains; milk; meat and beans; seafood and plant protein; fatty acid ratio; sodium; refined grains; calories from solid fats, alcohol, and added sugars. Alternative Healthy Eating Index-2010 components: vegetables; fruit; whole grains; sugar-sweetened beverages; nuts and legumes; red meat; trans fat; DHA and EPA; polyunsaturated fat; sodium; alcoholic drinks.</span>

<span style="color:red">Fetal sex, gestational diabetes mellitus, the Visit-2 reported EFW percentile, and uterine artery Doppler measurements were not included as predictors in any model.</span>

<span style="color:red">BMI: body mass index; BPD: biparietal diameter; HC: head circumference; AC: abdominal circumference; FL: femur length; EFW: estimated fetal weight; AFI: amniotic fluid index; DHA: docosahexaenoic acid; EPA: eicosapentaenoic acid.</span>

## Table <span style="color:red">3</span>. Area under the receiver operating characteristic curve of WHO fetal growth chart–based percentile variables for predicting macrosomia.

| WHO Characteristics                  | AUC                   | WHO Characteristics                  | AUC                   |
|--------------------------------------|-----------------------|--------------------------------------|-----------------------|
| For birthweight \> 4000 g prediction |                       | For birthweight \> 4500 g prediction |                       |
|                                      |                       |                                      |                       |
| WHO-BPD-2                            | 0.57                  | WHO-BPD-2                            | 0.58                  |
| WHO-AC-2                             | 0.59                  | WHO-AC-2                             | 0.64                  |
| WHO-HC-2                             | 0.58                  | WHO-HC-2                             | 0.62                  |
| WHO-FL-2                             | 0.54                  | WHO-FL-2                             | 0.54                  |
| WHO-EFW-2                            | 0.57                  | WHO-EFW-2                            | 0.60                  |
|                                      |                       |                                      |                       |
| WHO-BPD-3                            | 0.65                  | WHO-BPD-3                            | 0.74                  |
| WHO-AC-3                             | 0.70                  | WHO-AC-3                             | 0.79                  |
| WHO-HC-3                             | 0.65                  | WHO-HC-3                             | 0.74                  |
| WHO-FL-3                             | 0.61                  | WHO-FL-3                             | 0.68                  |
| WHO-EFW-3                            | 0.68                  | WHO-EFW-3                            | 0.77                  |

<span style="color:red">AUROC values are presented for descriptive comparison with the prediction models.</span>

<span style="color:red">WHO: World Health Organization; BPD: biparietal diameter; AC: abdominal circumference; HC: head circumference; FL: femur length; EFW: estimated fetal weight. The suffixes 2 and 3 denote Visit 2 and Visit 3.</span>
