# Response to the Editor

Dear Dr Kehl,

Thank you for your careful assessment of our revised manuscript, "Development and internal validation of early- and mid-pregnancy prediction models for macrosomia in nulliparous singleton pregnancies," and for the clear guidance on the issues that should be addressed before further consideration. We are grateful for your positive remarks on the previous revision.

We have revised the manuscript in line with the five points raised in your letter. Following your advice, we did not add a new external cohort or alternative machine-learning models; instead, we focused on making the description of the existing modelling and validation framework transparent and internally consistent. In the course of this work, we re-examined every predictor against its time of availability. As a result, fetal sex and gestational diabetes mellitus were removed from all prediction models, and all analyses were repeated. The main changes are summarized below, and a detailed point-by-point response to the reviewer follows. Changes in the manuscript are highlighted in red.

**1. Definition of the four models and time of availability of predictors**

We have added a new Table 2, which lists every predictor included in Model 1, Model 2, Model 3, and the Combined model, together with its time of availability. The model definitions in Section 2.5 have been revised so that they are consistent with this table and with the Supplementary Material: Model 3 extends Model 1 with Visit-3 information, and only the Combined model includes information from both Visit 2 and Visit 3 (42, 51, 56, and 65 predictors, respectively).

We also re-examined the time of availability of each predictor. Because the time at which fetal sex was ascertained is not documented in the nuMoM2b dataset, we could not confirm that it was available at the intended prediction time. We therefore removed fetal sex from all models. Gestational diabetes mellitus, which had been included among the Visit-2 predictors of Model 2 and the Combined model, was also removed because it is usually diagnosed after the second-trimester visit. All analyses were then repeated, and all results in the manuscript and the Supplementary Material have been updated. Fetal sex is now used to define the LGA sensitivity outcomes and in descriptive and univariate analyses, but not as a predictor in any model.

**2. Use of repeated cross-validation predictions and comparison with ultrasound benchmarks**

We have clarified in Section 2.5 how the repeated cross-validation predictions were used. The out-of-fold predictions of each participant were averaged across the repeated cross-validation runs, so that each participant contributed a single prediction to the discrimination analyses, and confidence intervals were obtained by bootstrap resampling of participants. Calibration, threshold-based, and decision-curve analyses were based on one complete run of 10-fold cross-validation, in which each participant had exactly one recalibrated out-of-fold prediction. Repeated predictions from the same participant are therefore no longer treated as independent observations.

As requested, the Mann–Whitney comparisons between the WHO chart-based AUROCs and the cross-validation AUROC distributions have been removed from Table 3 (previously Table 2), the Results, and the Supplementary Material. The comparison between the models and the ultrasound benchmarks is now purely descriptive. Differences between the prediction models themselves are reported as participant-level paired bootstrap differences in AUROC.

**3. Interpretation in line with the limits of the data**

We have stated explicitly, where the performance of Model 1 is presented and in the limitations, that the early-pregnancy model was evaluated in the common analytic cohort with complete follow-up to Visit 3. We have also emphasized that the birthweight >4500 g outcome was based on only 77 events and that these results should be interpreted cautiously. To support this interpretation, we report the number of candidate predictors and events per candidate predictor, together with a model-complexity analysis for this outcome.

Expressions such as "clinically useful," "clinically meaningful," and "performed comparably" have been removed from the Abstract, the Discussion, and the Conclusion. The upper-quintile and upper-decile analyses are now described as fixed risk strata rather than prespecified thresholds, and we state that neither these analyses nor the decision-curve analysis establish clinical utility.

**4. The Dutch analysis**

We have retained the Dutch analysis but now describe it throughout as a limited evaluation of a reduced early-pregnancy predictor set, and state explicitly that it does not constitute external validation of the full visit-updated models. The necessary information has been added to the Methods, Results, and Supplementary Table S12: the six harmonized predictors, the number of records and events, application of the nuMoM2b coefficients without refitting, the handling of missing data, and AUROCs with 95% confidence intervals. The ethics and data-availability statements have been updated accordingly, and the statement that external validation is required before clinical use has been retained.

**5. Scope of the revision**

In line with your guidance, no new external cohort or alternative modelling approach was introduced. The additional material in this revision is limited to what was needed for a transparent description of the existing framework, namely the model-definition table, the corrected validation description, the recalculated results after removal of fetal sex and gestational diabetes mellitus, and the model-complexity assessment for the >4500 g outcome. We have also removed the separate post-hoc alcohol association analysis to keep the manuscript focused on prediction.

We have uploaded the following files: a revised manuscript with changes highlighted in red, a clean version of the revised manuscript, this point-by-point response, and the updated Supplementary Material.

We hope that the revised manuscript is now suitable for further consideration in *Archives of Gynecology and Obstetrics*.

Best regards,

Xi Long
on behalf of all authors

---

# Response to the Reviewer

We thank the reviewer for the second careful evaluation of our manuscript and for recognizing the improvements made in the previous revision. The comments have helped us identify several points at which the description of the modelling framework was incomplete or inconsistent. In particular, re-examining the time of availability of each predictor led us to remove fetal sex and gestational diabetes mellitus from all prediction models and to repeat all analyses. Below, we respond to each comment in turn. Revised text from the manuscript is shown in italics, and changes are highlighted in red in the revised manuscript. Line numbers refer to the revised manuscript with changes highlighted.

## Comment 1. Definitions of the four prediction models

**1.1** *"The definitions of the four prediction models remain inconsistent. … According to this description, Model 3 and the Combined model would be identical. … The authors should provide a table listing every predictor included in each model and its time of availability."*

We thank the reviewer for pointing this out. We have revised the model definitions in Section 2.5 so that they are consistent with the Supplementary Material and with the new Table 2. Model 3 extends Model 1 with Visit-3 information, and only the Combined model includes information from both Visit 2 and Visit 3:

*"Model 1 used maternal demographics and history, Visit-1 anthropometry, early gestational weight gain, and periconceptional diet indices (42 predictors). Model 2 extended Model 1 by adding Visit-2 anthropometry and second-trimester ultrasound biometry with derived estimated fetal weight (51 predictors). Model 3 extended Model 1 by adding Visit-3 anthropometry and third-trimester ultrasound measurements (56 predictors). The Combined model included all information from Visit 1, Visit 2, and Visit 3 (65 predictors). All four models were developed and evaluated in the same analytic cohort to allow direct comparison."* (Section 2.5, lines XX–XX)

As suggested, we have added a new Table 2 to the main text. It lists every predictor, grouped by domain and visit, together with its time of availability and the models in which it was included. The model descriptions in the Supplementary Material have been aligned with this table.

**1.2** *"Supplementary Table S10 also contains several predictors not adequately described in Section 2.3, including education, family history of diabetes, gestational diabetes, cervical length, Visit-2 uterine artery Doppler variables, and reported EFW percentiles."*

We thank the reviewer for this comment. Supplementary Table S9 has been revised so that it now lists only the predictors included in the models, as defined in Table 2. Regarding the variables mentioned by the reviewer:

- **Education and family history of diabetes** were used only in the comparison of included and excluded pregnancies (Supplementary Table S6) and were not model predictors.
- **Cervical length and Visit-2 uterine artery Doppler variables** were not included in any model.
- **Gestational diabetes mellitus** was removed from the models, as described under Comment 2.
- **Reported EFW percentiles:** the percentile reported at Visit 3 is a predictor in Model 3 and the Combined model, whereas the percentile reported at Visit 2 was not used because of substantial missingness.

Section 2.3 has been revised to describe these predictors:

*"Visit 3 included the same biometry variables together with the four amniotic fluid index quadrants and the estimated fetal weight percentile reported in nuMoM2b."* (Section 2.3, lines XX–XX)

The predictors not included in any model are also listed in the footnote to Table 2.

**1.3** *"Conversely, the individual dietary components appearing in Figures 2–6 are not fully identified as model predictors in the Methods."*

We thank the reviewer for this comment. All component scores and both total scores of the Healthy Eating Index-2010 and the Alternative Healthy Eating Index-2010 were used as dietary predictors. This is now stated in Section 2.3:

*"The component and total scores of both indices were used as dietary predictors."* (Section 2.3, lines XX–XX)

The 25 dietary predictors are listed individually in the footnote to Table 2. Because the total scores and their components were entered jointly, we have added a note to Section 2.5 that individual dietary coefficients should not be interpreted as independent effects.

**1.4** *"Exact predictor coding, transformations, categorical-variable handling, and model-specific inclusion criteria must therefore be reported."*

We have added the following to Section 2.3:

*"Predictors were entered as continuous or binary variables, with race and ethnicity coded as four binary indicators; the predictors included in each model and their time of availability are listed in Table 2."* (Section 2.3, lines XX–XX)

No further transformations were applied. Imputation and standardization were fitted within the training data of each cross-validation split (Section 2.5). There were no model-specific inclusion criteria: all four models were developed and evaluated in the same analytic cohort, which is now stated in Section 2.5.

## Comment 2. Temporal data leakage

**2.1** *"Fetal sex is included in the early-pregnancy model and reportedly has no missing data. It is unclear whether fetal sex was genuinely known at 6–13 weeks or obtained from delivery or newborn records."*

We thank the reviewer for raising this important point. The nuMoM2b dataset does not document when fetal sex was ascertained, and we could therefore not confirm that it was available at the intended prediction time of Model 1. To exclude any possibility of temporal leakage, we removed fetal sex from all prediction models and repeated all analyses. It is now used to define the LGA sensitivity outcomes, which by definition depend on neonatal sex, and in descriptive and univariate analyses. The revised Section 2.3 states:

*"Fetal sex and gestational diabetes mellitus were not used as predictors, because their availability at the intended prediction times could not be ensured; fetal sex was used to define the LGA outcomes and in descriptive and univariate analyses."* (Section 2.3, lines XX–XX)

After this change, the AUROC of Model 1 was 0.628 (95% CI 0.602–0.651) for birthweight >4000 g and 0.721 (0.670–0.770) for birthweight >4500 g. All results in the Abstract, Results, Discussion, figures, and Supplementary Material have been updated accordingly.

**2.2** *"Similarly, if gestational diabetes or any other later-occurring variable listed in Supplementary Table S10 entered an earlier model, this would also represent leakage."*

We agree. We re-examined the timing of all predictors listed in Supplementary Table S9. Gestational diabetes mellitus, which was among the Visit-2 predictors of Model 2 and the Combined model, has been removed because it is usually diagnosed after the second-trimester visit, and the affected analyses have been repeated. Model 1 and Model 3 did not include this variable.

**2.3** *"The source and timing of every predictor should be documented, and variables unavailable at the intended prediction time should be removed before repeating the affected analyses."*

We have checked the source and timing of every remaining predictor. All are measured at or before the visit that defines the corresponding model, and their time of availability is now documented in Table 2. The dietary predictors were obtained from the Food Frequency Questionnaire administered at enrollment (Visit 1), covering the 3 months around conception.

## Comment 3. Internal validation and uncertainty estimation

**3.1** *"It is unclear whether the repeated predictions generated for each participant were averaged at the participant level or pooled as if they were independent observations."*

We thank the reviewer for this important comment. We agree that treating repeated predictions from the same participant as independent would overstate precision. The out-of-fold predictions were averaged at the participant level, and bootstrap resampling was performed at the participant level. The discrimination results for the primary and LGA outcomes in Supplementary Tables S4 and S5 are based on this approach, which is now described explicitly in Section 2.5:

*"In each repetition, every participant received one out-of-fold predicted probability; these predictions were averaged across repetitions at the participant level, so that each participant contributed a single prediction to the evaluation. AUROC and AUPRC were calculated from these participant-level predictions, and 95% confidence intervals were obtained from 1,000 bootstrap resamples of participants. Differences in AUROC between models were estimated using paired bootstrap resampling of the same participants."* (Section 2.5, lines XX–XX)

For the main model evaluations of the primary and LGA outcomes, calibration, threshold-based, and decision-curve analyses used one complete run of stratified 10-fold cross-validation, giving each participant exactly one recalibrated out-of-fold prediction (see Comment 5).

**3.2** *"The authors should clearly describe the complete nested-validation pipeline, including the logistic-regression penalty, hyperparameter search space, optimization metric, inner-validation procedure, method used to combine repeated predictions, and level at which bootstrap resampling was conducted."*

We have expanded the description of the validation procedure in Section 2.5. The components requested by the reviewer are as follows.

- **Penalty and hyperparameters:** the logistic regression models used an elastic-net penalty. The regularization strength (C) and the L1 ratio were tuned within the training data of each outer fold by randomized search with inner 3-fold cross-validation, using average precision as the optimization metric. The search spaces are now provided in the note to Supplementary Table S8.
- **Class weights:** class weights were computed within each training fold, with the negative class assigned a weight of 1 and the positive class weighted by the square root of the negative-to-positive sample ratio.
- **Recalibration:** the Platt calibrator was fitted within the training folds only and applied to the held-out fold (see Comment 5).
- **Combining repeated predictions:** the out-of-fold predictions were averaged across the repeated cross-validation runs at the participant level (Comment 3.1).
- **Level of bootstrap resampling:** bootstrap resampling was conducted at the participant level, with 1,000 resamples; for differences between models, the same resampled participants were used for both models (paired bootstrap).

In addition, nested cross-validation was used in the model-complexity analysis for birthweight >4500 g, in which predictor selection and Platt recalibration were performed within each outer training fold (Comment 4).

**3.3** *"The Mann–Whitney U comparisons in Table 2 are particularly problematic … A participant-level paired analysis, such as a paired bootstrap comparison of clinically relevant predictors, should be used instead."*

We agree and have removed all Mann–Whitney comparisons from Table 3 (previously Table 2), the Results, and the Supplementary Methods, together with the averaged WHO AUROCs to which they referred. The WHO chart-based percentiles are now presented as descriptive benchmarks only:

*"All WHO-derived percentile variables were evaluated as ultrasound-based benchmark comparators in the discrimination analyses; these comparisons with the prediction models were descriptive."* (Section 2.4, lines XX–XX)

Comparisons between the prediction models are now based on participant-level paired bootstrap differences in AUROC, as suggested. For example, for birthweight >4000 g:

*"Compared with Model 1 (0.628, 0.602–0.651), the paired AUROC difference was 0.105 (0.081–0.128) for Model 3 and 0.104 (0.081–0.129) for the Combined model. Model 2 (0.651, 0.625–0.674) showed a smaller improvement over Model 1 (difference 0.024, 0.013–0.037), and the Combined model did not improve on Model 3 (difference −0.001, −0.004 to 0.002)."* (Section 3.2, lines XX–XX)

The paired differences for all model comparisons are provided in Supplementary Table S5.

## Comment 4. Overfitting risk for birthweight >4500 g

**4.1** *"Only 77 outcome events were available … Simply reporting the sample size and event count does not constitute a Riley-based sample-size justification. The authors should report the number of candidate parameters and effective model degrees of freedom and provide a formal assessment of anticipated shrinkage or overfitting."*

We thank the reviewer for this comment and agree that 77 events is a real limitation. Because this study used an existing cohort, the sample size was fixed and no a priori calculation was possible. In line with the reviewer's suggestion, we now report the number of candidate predictors for each model and the corresponding events per candidate predictor. Because the models were fitted with penalization, the nominal number of candidate predictors overstates the complexity actually used by the model. We therefore added an empirical assessment of model complexity for the Combined model for birthweight >4500 g. Section 2.6 now states:

*"The four models included 42, 51, 56, and 65 candidate predictors (Table 2), corresponding to 7.8–12.0 events per candidate predictor for birthweight >4000 g and 1.2–1.8 events per candidate predictor for birthweight >4500 g. Because penalized estimation does not use all candidate predictors to the same extent, we additionally examined model complexity for the Combined model for birthweight >4500 g. We estimated the local approximate effective degrees of freedom of the penalized model and compared the full model with reduced models in which predictors were ranked within each outer training fold by their absolute standardized mean difference (Cohen’s d), retaining the 10 or 13 highest-ranked predictors."* (Section 2.6, lines XX–XX)

The results are reported in Section 3.2 and in the new Supplementary Table S13:

*"In the model-complexity analysis for birthweight >4500 g (Supplementary Table S13), the local approximate effective degrees of freedom of the penalized Combined model was 24.2, compared with 65 candidate predictors. Retaining 13 or 10 predictors selected within each training fold reduced the effective degrees of freedom to 3.7 and 3.0, respectively, with AUROCs of 0.813 (0.764–0.859) and 0.803 (0.752–0.851), compared with 0.821 (0.778–0.866) for the full model within the same framework. The paired AUROC differences relative to the full model were −0.008 (−0.037 to 0.018) and −0.018 (−0.050 to 0.014), and calibration slopes after Platt recalibration were 1.056 and 1.010, respectively."* (Section 3.2, lines XX–XX)

The reported effective degrees of freedom and calibration measures were obtained from a separate 30-repetition run, with calibration assessed using participant-level mean Platt-recalibrated out-of-fold probabilities. The effective degrees of freedom are a local approximation for a given set of active predictors and do not account for the full variable-selection process. Selection was performed within each outer training fold, so validation assessed the complete selection-and-fitting procedure. The reduced models were still developed from a pool of 65 candidate predictors.

**4.2** *"The calibration slopes of only 0.485–0.703 for the models predicting birthweight above 4500 g reinforce this concern."*

We thank the reviewer for this comment. These slopes were obtained with isotonic recalibration, which, as the reviewer notes under Comment 5, is unlikely to be stable for this outcome. After cross-fitted Platt recalibration, with one prediction per participant, the calibration slopes for birthweight >4500 g ranged from 0.992 to 1.016 (Supplementary Table S5). These estimates characterize the recalibrated prediction procedure.

**4.3** *"The authors should consider substantially simplifying these models or explicitly classifying the 4500-g analyses as exploratory."*

We have considered this suggestion carefully. In the model-complexity analysis, models with 10–13 predictors selected within the training folds and approximately 3–4 local effective degrees of freedom retained most of the discrimination observed for the full model. The paired confidence intervals also allow for a loss of discrimination, so these results do not establish equivalence or exclude overfitting. They support our decision to retain the same four model definitions across outcomes, with cautious interpretation of the >4500 g results.

We agree that estimates based on 77 events are imprecise. In keeping with the Editor's request for cautious interpretation, we have made this limitation explicit:

*"In addition, prediction of birthweight >4500 g was based on only 77 events; although the model-complexity analysis suggested that most of the discrimination was retained with substantially fewer predictors, estimates for this outcome remain imprecise and should be interpreted cautiously."* (Section 4.4, lines XX–XX)

## Comment 5. Calibration approach

**5.1** *"Isotonic regression was fitted using 10% of each outer training fold, which would contain approximately seven events above 4500 g per calibration subset. This is unlikely to be sufficient for stable non-parametric calibration."*

We agree with the reviewer. We have replaced isotonic regression with Platt scaling, a two-parameter logistic recalibration that is more appropriate for the available number of events. All calibration, threshold-based, and decision-curve results in the revised manuscript are based on Platt recalibration.

**5.2** *"Furthermore, class-weighted logistic regression changes the relationship between model scores and absolute outcome probabilities, making appropriate recalibration essential. … The authors should clarify whether these measures were calculated from raw or recalibrated predictions."*

We agree that recalibration is essential after class weighting, and this is now stated in the Methods:

*"Because class weighting changes the relationship between model scores and absolute outcome probabilities, predicted probabilities were then recalibrated using Platt scaling, with the Platt calibrator fitted within the training folds only and applied to the held-out fold. For the main model evaluations, calibration, threshold-based, and decision-curve analyses were based on one complete run of stratified 10-fold cross-validation, so that each participant had exactly one recalibrated out-of-fold prediction."* (Section 2.5, lines XX–XX)

All calibration measures in the revised manuscript are therefore calculated from recalibrated, cross-fitted predictions.

**5.3** *"… and report calibration-in-the-large or observed-to-expected ratios. Brier scores should be compared with those of a null model or presented as scaled Brier scores."*

We have added calibration-in-the-large, the observed-to-expected (O/E) ratio, and the scaled Brier score to the Methods (Section 2.5) and report them for all models and outcomes in Supplementary Tables S4 and S5. Section 3.2 now states:

*"After Platt recalibration, calibration slopes ranged from 0.992 to 1.017, calibration-in-the-large from −0.018 to −0.001, and O/E ratios from 0.983 to 0.999 across the four models for both outcomes. The Brier score of the Combined model was 0.0686 for birthweight >4000 g and 0.0116 for birthweight >4500 g, corresponding to scaled Brier scores of 6.0% and 2.9%; these values indicate modest reductions in prediction error relative to the prevalence-only model."* (Section 3.2, lines XX–XX)

The scaled Brier scores indicate modest reductions in prediction error relative to a model assigning the observed prevalence to all participants. We interpret them alongside discrimination and calibration.

**5.4** *"Threshold analyses and decision curves should then be recalculated using properly cross-fitted probabilities. The current decision-curve analysis alone does not establish clinical utility, particularly because no specific clinical intervention or harm-benefit trade-off has been defined."*

The threshold-based analyses (Supplementary Table S7) and decision curves (Supplementary Figure S5) have been recalculated using the cross-fitted Platt-recalibrated probabilities, and the corresponding numbers in Sections 3.2 and 4.3 have been updated. We agree that the decision-curve analysis does not establish clinical utility, and we have revised the text accordingly:

*"The decision curves summarize net benefit across threshold-probability ranges using recalibrated out-of-fold predicted probabilities and are intended to illustrate model behavior rather than to establish clinical utility or define recommended intervention thresholds."* (Section 3.2, lines XX–XX)

*"Because no specific intervention or harm–benefit trade-off was defined, neither these analyses nor the decision-curve analysis establish clinical utility."* (Section 4.3, lines XX–XX)

## Comment 6. Evaluation in the Dutch cohort

**6.1** *"The newly presented external evaluation is too incompletely reported to be considered a valid external validation. Supplementary Table S13 provides only AUROC point estimates and does not report the Dutch cohort's sample size, event numbers, recruitment dates, eligibility criteria, outcome prevalence, missingness, predictor distributions, harmonization procedures, confidence intervals, or calibration. It is also unclear whether the original nuMoM2b coefficients and intercept were applied without refitting."*

We thank the reviewer for this comment and agree that the previous description was insufficient. Following the Editor's guidance, we have retained this analysis but describe it as a limited evaluation of a reduced early-pregnancy predictor set, and we now report the information needed to interpret it.

- **Cohort:** the MMC cohort has been described in detail in our previous publication [33]. It includes pregnant women aged 18–45 years without preexisting diabetes who gave birth at Máxima Medical Center between 2012 and 2017.
- **Predictors and model application:** only six predictors could be harmonized: maternal age, pre-pregnancy BMI, and four race and ethnicity indicators. A reduced model with these predictors was developed in nuMoM2b and applied to the MMC records with the nuMoM2b coefficients and intercept unchanged, without refitting or recalibration.
- **Missing data:** records with missing predictor or outcome data were excluded.
- **Sample and events:** the analysis included 12,043 delivery records, with 1,142 (9.5%) births >4000 g and 134 (1.1%) births >4500 g.
- **Results:** the AUROCs, with 95% confidence intervals, are now reported for both the MMC evaluation and the same reduced model in nuMoM2b. For the MMC data, bootstrap resampling was performed at the level of women, so that all delivery records of a woman were resampled together.

These details are provided in Section 2.6, Section 3.2, and Supplementary Table S12:

*"As a limited additional analysis, a reduced early-pregnancy model including only the six predictors that could be harmonized with an independent Dutch cohort from Máxima Medical Center (MMC) [33] (maternal age, pre-pregnancy BMI, and four race and ethnicity indicators) was developed in nuMoM2b and applied to MMC delivery records with unchanged coefficients and intercept; records with missing data were excluded. This limited evaluation assessed discrimination only. The MMC data included multiparous women and repeated deliveries, and absolute-risk calibration was not evaluated."* (Section 2.6, lines XX–XX)

*"In the limited evaluation in the MMC cohort (12,043 delivery records; 1,142 [9.5%] with birthweight >4000 g and 134 [1.1%] with birthweight >4500 g), the reduced six-predictor early-pregnancy model applied with the nuMoM2b coefficients yielded AUROCs of 0.597 (0.580–0.613) and 0.636 (0.589–0.681), respectively. In internal validation in nuMoM2b, the same reduced model achieved AUROCs of 0.603 (0.577–0.627) and 0.615 (0.556–0.678), which were lower than those of the full Model 1 (Supplementary Table S12)."* (Section 3.2, lines XX–XX)

We restricted this analysis to discrimination of the reduced predictor set. Calibration was not evaluated, and we make no claim about the accuracy of absolute risks in MMC. The Methods also note that the cohort included multiparous women and repeated deliveries.

**6.2** *"The analysis is absent from the main Methods and Results, while Items 16 and 20c of the TRIPOD+AI checklist still state that no separate external evaluation dataset was used. Ethical approval, consent or data-governance arrangements, and data availability for the MMC cohort should also be documented."*

The analysis is now described in the Methods (Section 2.6) and Results (Section 3.2). Items 16 and 20c of the TRIPOD+AI checklist (Supplementary Table S11) have been updated. They now describe the differences between the development data and the MMC data, and refer to Supplementary Table S12. The ethics and data-availability statements have been extended:

*"The Medical Ethics Review Committee of Máxima Medical Center reviewed the retrospective use of the MMC data and waived the requirement for formal ethical approval [33]."* (Ethics Statement, lines XX–XX)

*"The MMC data are not publicly available because of privacy regulations; further information is available from the corresponding author upon reasonable request."* (Data Availability Statement, lines XX–XX)

**6.3** *"AUROCs of 0.60 and 0.64 without confidence intervals or calibration do not support the statement that the findings demonstrate potential transferability. … It must not be used to imply external validation of the complete visit-updated models."*

We agree and have removed the statement on potential transferability. The limitations section now reads:

*"In a limited evaluation in an independent Dutch cohort, a reduced early-pregnancy model restricted to six harmonizable predictors showed discrimination similar to that observed for the same reduced model in nuMoM2b (Supplementary Table S12). This analysis did not include periconceptional diet, most Visit-1 anthropometric measurements, or serial ultrasound measurements, included multiparous women, and assessed discrimination only; it therefore does not constitute external validation of the full visit-updated models."* (Section 4.4, lines XX–XX)

External validation of the complete visit-updated models requires a cohort with periconceptional dietary data and serial second- and third-trimester ultrasound in a comparable form. Such data were not available to us, and we consider this an important direction for future work.

## Comment 7. Selection of the analytic cohort for the early-pregnancy model

**7.1** *"Model 1 is evaluated only among pregnancies that subsequently had complete dietary data and Visit-2 and Visit-3 ultrasound availability. … Model 1 should be evaluated in the largest cohort eligible at Visit 1, and Model 2 should similarly be evaluated in the cohort eligible at Visit 2. If the same complete-follow-up cohort is retained only to permit direct model comparisons, claims concerning general early-pregnancy performance should be explicitly limited to this selected population."*

We thank the reviewer for this comment and agree that the early-pregnancy model is evaluated in a selected population. We retained the common complete-follow-up cohort because the aim of the study was to compare the four models directly. Paired comparisons between models, such as the participant-level paired bootstrap differences now reported, require that all models be evaluated in the same participants. Evaluating each model in a different cohort would make it difficult to separate differences in model performance from differences in the population.

Among the 7,185 pregnancies remaining after the consent, outcome-data, and periconceptional-diet screening steps, 814 were excluded because of incomplete Visit-2 or Visit-3 ultrasound data. This group is characterized in Supplementary Table S6.

As suggested by the reviewer and the Editor, we have limited the claims about early-pregnancy performance to this selected population. This is stated where the performance of Model 1 is presented and in the limitations:

*"The estimates for Model 1 were obtained in the common analytic cohort with complete follow-up to Visit 3."* (Section 3.2, lines XX–XX)

*"In particular, Model 1 was evaluated only among pregnancies with periconceptional dietary data and subsequent Visit-2 and Visit-3 ultrasound data, so its performance may not reflect that in all pregnancies eligible at Visit 1."* (Section 4.4, lines XX–XX)

Evaluation of the early-pregnancy model in all pregnancies eligible at Visit 1 would be a useful extension in future work.

## Comment 8. Comparability with ultrasound benchmarks and clinical usefulness

**8.1** *"The assertion that Model 1 performed comparably to later WHO ultrasound benchmarks depends largely on averaging the AUROCs of five different biometric measurements. Such an average does not represent a clinically applicable test. … The results therefore do not demonstrate equivalence with the strongest or most clinically relevant ultrasound measures."*

We agree with the reviewer. The averaged WHO AUROCs have been removed from Table 3 and from the text, and the statements that Model 1 performed comparably to the WHO benchmarks have been removed from the Abstract, Results, and Discussion. The Abstract now states:

*"In this selected analytic cohort, the early-pregnancy model based on maternal data alone provided moderate discrimination (0.63 and 0.72, respectively), although lower than the strongest third-trimester WHO fetal growth chart–based ultrasound percentile benchmarks."* (Abstract, lines XX–XX)

In the Results:

*"However, Model 1 showed lower discrimination than the stronger Visit-3 WHO-derived percentiles."* (Section 3.2, lines XX–XX)

In the Discussion:

*"Although the early-pregnancy model did not reach the discrimination of the stronger third-trimester WHO chart–based ultrasound percentiles, it relies on information that is available several months earlier in pregnancy. Once Visit-3 ultrasound information was incorporated, the visit-updated models showed higher point estimates than all WHO chart–based comparators, and most of the incremental discrimination was attributable to Visit-3 rather than Visit-2 information."* (Section 4.1, lines XX–XX)

**8.2** *"Moreover, upper-decile sensitivity was only 30.7% for birthweight above 4000 g, while PPV remained approximately 5.5% for birthweight above 4500 g. Expressions such as 'clinically useful,' 'clinically meaningful,' and 'clinical utility' should be replaced by more neutral language describing moderate discrimination during internal validation."*

We agree. "Clinically useful" in the "What this study adds" section and "clinically meaningful" in the Conclusion have been replaced by "moderate," and "meaningful risk stratification" in Section 4.1 has been revised in the same way. The Discussion continues to report the modest sensitivity and positive predictive values explicitly; after recalculation, the upper-decile sensitivity for birthweight >4000 g was 29.1%, and the positive predictive value for birthweight >4500 g reached 5.6%. The statement that neither the threshold analyses nor the decision curves establish clinical utility has been added to Section 4.3 (see Comment 5.4).

**8.3** *"The upper-quintile and upper-decile analyses were introduced following peer review and should not be called 'prespecified' unless they were documented in a protocol before the original analyses."*

We agree and have removed the word "prespecified." The upper quintile and upper decile are now described as "fixed risk strata" in Section 2.5 and Section 4.3 (lines XX–XX and XX–XX).

## Comment 9. Alcohol analysis

**9.1** *"The response letter states that this finding is retained only in the Discussion, whereas the adjusted odds ratio of 2.76 and the negative-control-type analysis remain in Section 3.4 of the Results."*

We thank the reviewer for this comment. We have removed the separate post-hoc alcohol association analysis, including the adjusted odds ratio, and its interpretation from the Results, Discussion, and limitations. The alcoholic drinks score is retained only as part of the overall dietary predictor set and the descriptive dietary analyses.

**9.2** *"In addition, gestational duration and preterm birth are not convincing negative-control outcomes because alcohol exposure may plausibly affect these outcomes; their null associations do not exclude residual confounding."*

The gestational-duration sensitivity analyses and their accompanying supplementary table have been removed. We no longer draw conclusions about residual confounding from these analyses.

**9.3** *"The finding is based on a data-driven ablation analysis, numerous dietary comparisons, and only 77 cases above 4500 g. Figure 6 also labels the alcohol component as 'p<0.05' without defining the statistical test or multiplicity correction."*

The dietary ablation analyses are retained as descriptive exploratory analyses in Supplementary Figures S6 and S7. The significance marker has been removed from the figure (now Supplementary Figure S7). No independent alcohol association is inferred from the ablation results.

**9.4** *"If retained, the authors should report exposure-group and event counts, the exact definition of moderate alcohol exposure, the complete adjustment model, missing-data handling, multiplicity control, and a valid uncertainty analysis."*

The separate alcohol association analysis has been removed. The score appears only within the overall dietary analyses, with a brief scoring definition in the shared note to Supplementary Figures S6 and S7. No alcohol-specific effect estimate or causal interpretation is retained.

## Comment 10. Figures, tables, and references

**10.1** *"The figures should be revised to use the actual thresholds 'birthweight >4000 g' and 'birthweight >4500 g.' Retaining 'grade I & II' and 'grade II' in the artwork and translating these expressions in the legends remains confusing. 'BDP' should be corrected to 'BPD' in Figures 2 and 3, and 'fetal gender' should be replaced with 'fetal sex.'"*

All figures have been redrawn with the labels "birthweight >4000 g" and "birthweight >4500 g", and the translating sentences have been removed from the figure legends. In Figures 2 and 3, "BDP" has been corrected to "BPD." Fetal sex no longer appears in these figures because it has been removed from the models. Elsewhere in the manuscript, the term "fetal sex" is used throughout.

**10.2** *"Supplementary Table S11 omits Visit-2 INTERGROWTH-21st EFW despite the Methods describing five analogous measurements at both visits; this discrepancy should be explained."*

We thank the reviewer for noting this. The INTERGROWTH-21st standard for Hadlock-based estimated fetal weight applies from 18 weeks of gestation. Because 39.8% of the Visit-2 scans were performed before 18 weeks, the percentile could not be derived for these pregnancies. The Visit-2 EFW percentile has now been added to Supplementary Table S10 for the 3,834 pregnancies in whom it could be derived, with AUROCs of 0.61 for birthweight >4000 g and 0.63 for birthweight >4500 g. The table note explains the smaller sample. The Methods now state:

*"Because the INTERGROWTH-21st standard for Hadlock-based estimated fetal weight applies from 18 weeks of gestation, the Visit-2 estimated fetal weight percentile could not be derived for scans performed before 18 weeks."* (Section 2.4, lines XX–XX)

**10.3** *"Appropriate references for the INTERGROWTH-21st newborn and fetal ultrasound standards should be added."*

We have added references to the INTERGROWTH-21st Newborn Size Standards [20], the INTERGROWTH-21st fetal growth standards [28], and the INTERGROWTH-21st standards for Hadlock-based estimated fetal weight [29] (Sections 2.2 and 2.4).

**10.4** *"The authors should also clarify whether the significance markers in Table 1 represent raw p-values or FDR-adjusted q-values, define consistently whether the thresholds are greater than or greater than or equal to 4000 and 4500 g, and correct the duplicated '[29]' in the reference list."*

- **Table 1:** the significance markers are based on Benjamini–Hochberg FDR-adjusted q-values, and the table footnote has been revised to state this.
- **Thresholds:** both outcomes are defined as birthweight strictly greater than 4000 g and strictly greater than 4500 g. The reference group in Table 1 and the Figure 4 legend is labelled "≤4000 g," and the intermediate group is explicitly labelled ">4000 to ≤4500 g."
- **Reference list:** the duplicated "[29]" has been corrected. Because new references were added, the references have been renumbered in order of citation.

We thank the reviewer again for the detailed and constructive comments, which have substantially improved the transparency and consistency of the manuscript.
