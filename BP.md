Back to https://github.com/Kwangkee/rPPG
***


***

## Surveys
- [[Machine learning and deep learning for blood pressure prediction: A methodological review from multiple perspectives](https://github.com/Kwangkee/rPPG/blob/main/BP.md#machine-learning-and-deep-learning-for-blood-pressure-prediction)], https://link.springer.com/article/10.1007/s10462-022-10353-8 
- The experimental data & code and other useful resources are available at https://github.com/v3551G/BP-prediction-survey.

## Papers
- Blood pressure estimation from photoplethysmography by considering intra- and inter-subject variabilities: guidelines for a fair assessment, https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=Blood+pressure+estimation+from+photoplethysmography+by+considering+intra-+and+inter-subject+variabilities%3A+guidelines+for+a+fair+assessment&btnG= 

***
## Machine learning and deep learning for blood pressure prediction
- Machine learning and deep learning for blood pressure prediction: A methodological review from multiple perspectives, https://link.springer.com/article/10.1007/s10462-022-10353-8 

***
## guidelines for a fair assessment
- Blood pressure estimation from photoplethysmography by considering intra- and inter-subject variabilities: guidelines for a fair assessment, https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=Blood+pressure+estimation+from+photoplethysmography+by+considering+intra-+and+inter-subject+variabilities%3A+guidelines+for+a+fair+assessment&btnG= 

- Although the use of a single PPG for assessing hypertension is promising, the relationship between PPG and BP is not completely elucidated in fact. In an attempt to indirectly solve this issue, several authors, [27]–[39], have been reporting an accuracy in line with two guidelines, one by the American Association for the Advancement of Medical Instrumentation (AAMI) and the other published by the British Hypertension Society (BHS) [40], [41]. However, as observed by Schrumpf et al. (2021) [42], there is lack of information in the papers over the distribution of the dataset used by them to ensure (1) no mixing samples of the same subject and (2) equal data size per subject. Indeed, except for [43]–[45], authors which partially or completely follow this recommendation are finding errors far above the reference values [42], [46]–[50], denoting that such an estimation problem is not resolved yet. In this work, we investigate how intra- and inter-subject variabilities in BP lead to different results of machine learning algorithms. Moreover, by considering specifically the intra-subject scenario, we compare single PPG machine learning algorithms with a regression using age, sex, weight and subject index number as attributes, and obtain similar results, indicating that the algorithms might actually be learning to identify persons and not predicting BP.

- Alongside the previous studies, this work proposes to investigate how a single PPG signal can be used to estimate BP, with a representative set of machine learning algorithms covering both feature- and signal-based methods, but with an explicitly emphasis in the effect of the data arrangement—by considering intra- and inter-subject variabilities—in two frequently used databases: Multiparameter Intelligent Monitoring in Intensive Care II and III (MIMICII, MIMIC-III). As mentioned earlier, our work also indicates that, regarding intra-subject scenario, a regression using age, sex, weight and subject index number—therefore without a PPG signal (or its attributes) as input—already reaches an excellent performance in line with AAMI and BHS standards. Finally, we discuss the reasons for it and provide guidelines on what we believe to be essential procedures to properly evaluate BP estimation from PPG only, in order to prevent overestimation of the results.

***
Back to the [Top](#Surveys)  
Back to https://github.com/Kwangkee/rPPG
