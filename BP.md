Back to https://github.com/Kwangkee/rPPG
***

## Surveys
- [[Machine learning and deep learning for blood pressure prediction: A methodological review from multiple perspectives](https://github.com/Kwangkee/rPPG/blob/main/BP.md#machine-learning-and-deep-learning-for-blood-pressure-prediction)], https://link.springer.com/article/10.1007/s10462-022-10353-8 
- The experimental data & code and other useful resources are available at https://github.com/v3551G/BP-prediction-survey.

## Papers
- [[Blood pressure estimation from photoplethysmography by considering intra- and inter-subject variabilities: guidelines for a fair assessment](https://github.com/Kwangkee/rPPG/blob/main/BP.md#guidelines-for-a-fair-assessment)], https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=Blood+pressure+estimation+from+photoplethysmography+by+considering+intra-+and+inter-subject+variabilities%3A+guidelines+for+a+fair+assessment&btnG= 

***
## Machine learning and deep learning for blood pressure prediction
- Machine learning and deep learning for blood pressure prediction: A methodological review from multiple perspectives, https://link.springer.com/article/10.1007/s10462-022-10353-8 

#### Data availability
The experiments involved are based on a publicly available database MIMIC III, the script to download the dataset and the related experimental code are released on the Github repository: https://github.com/v3551G/BP-prediction-survey.

#### Multi aspects taxonomy of BP prediction methods
(1) Taxonomy 1-how to model the question of BP prediction from the perspective of machine learning?  
- assification question
- Regression question
- Signal conversion
- Sequence prediction
- Online/Incremental learning

(2) Taxonomy 2-whether feature extraction and predictive model building are performed simultaneously? 
- Machine learning-based methods
- Deep learning-based methods

(3) Taxonomy 3-whether the relationship among different tasks is modeled? 
- Single-task learning
- Multi-task learning

(4) Taxonomy 4-the signal source used for building predictive model. 
- Health Behavior data based
- Trajectory data based
- Facial video based
>- (i) mathematical/optical methods, 
>- (ii) video-based ML methods, 
>- (iii) video-based DL methods, 

![image](https://user-images.githubusercontent.com/109835677/210046688-5a3e10e2-07b3-449e-95c6-f5776e5d82f5.png)

***
Advancement in the Cuffless and Noninvasive Measurement of Blood Pressure: A Review of the Literature and Open Challenges, https://www.mdpi.com/2306-5354/10/1/27

#### 8.2. Validation Protocol
- There have been a significant number of studies done on this topic. However, due to a lack of similarity between the dataset, chosen data sample, or data acquisition protocol, it is tough to compare one technique. Some of the techniques are mathematical equation based, and some are machine learning algorithm based; the result from both may claim higher accuracy, but there is no way to compare which algorithm performed better. While working with machine learning algorithms, popular datasets contain ABP waveform to consider as the gold standard. When the dataset is privately owned or created from real-life patients, the number of subjects usually remains very small, and at the same time, getting ABP is difficult. To solve this problem, there must be a documented protocol for acquiring data from the patient, selecting the patient, preprocessing the data, and testing the data after preparing the model. Till now, there has been no such protocol available. Additionally, even in the successful experiments where a specific algorithm performed well, none of these have gone through a clinical trial. So the research speed needs to be matched with making the innovation available to be used clinically.
To solve this problem, there must be a documented protocol for acquiring data from the patient, selecting the patient, preprocessing the data, and testing the data after preparing the model. Till now, there has been no such protocol available. Additionally, even in the successful experiments where a specific algorithm performed well, none of these have gone through a clinical trial. So the research speed needs to be matched with making the innovation available to be used clinically.  
- 이러한 문제를 해결하기 위해서는 모델을 준비한 후 환자로부터 데이터를 획득하고, 환자를 선택하고, 데이터를 전처리하고, 데이터를 테스트하기 위한 문서화된 프로토콜이 있어야 한다. 지금까지, 그러한 프로토콜은 이용할 수 없었다. 또한, 특정 알고리즘이 잘 수행된 성공적인 실험에서도, 이들 중 어느 것도 임상 실험을 거치지 않았다. 따라서 연구 속도는 혁신을 임상적으로 사용할 수 있도록 하는 것과 일치해야 합니다.  


***
## guidelines for a fair assessment
- Blood pressure estimation from photoplethysmography by considering intra- and inter-subject variabilities: guidelines for a fair assessment, https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=Blood+pressure+estimation+from+photoplethysmography+by+considering+intra-+and+inter-subject+variabilities%3A+guidelines+for+a+fair+assessment&btnG= 

- 많은 연구/논문들이 데이터 사용/관리에 문제가 있고, 결과적으로 과장된 결과를 보고하고 있다는 얘기. How about yours?

- Although the use of a single PPG for assessing hypertension is promising, the relationship between PPG and BP is not completely elucidated in fact. In an attempt to indirectly solve this issue, several authors, [27]–[39], have been reporting an accuracy in line with two guidelines, one by the American Association for the Advancement of Medical Instrumentation (AAMI) and the other published by the British Hypertension Society (BHS) [40], [41]. However, as observed by Schrumpf et al. (2021) [42], there is lack of information in the papers over the distribution of the dataset used by them to ensure (1) no mixing samples of the same subject and (2) equal data size per subject. Indeed, except for [43]–[45], authors which partially or completely follow this recommendation are finding errors far above the reference values [42], [46]–[50], denoting that such an estimation problem is not resolved yet. In this work, we investigate how intra- and inter-subject variabilities in BP lead to different results of machine learning algorithms. Moreover, by considering specifically the intra-subject scenario, we compare single PPG machine learning algorithms with a regression using age, sex, weight and subject index number as attributes, and obtain similar results, indicating that the algorithms might actually be learning to identify persons and not predicting BP.

- Alongside the previous studies, this work proposes to investigate how a single PPG signal can be used to estimate BP, with a representative set of machine learning algorithms covering both feature- and signal-based methods, but with an explicitly emphasis in the effect of the data arrangement—by considering intra- and inter-subject variabilities—in two frequently used databases: Multiparameter Intelligent Monitoring in Intensive Care II and III (MIMICII, MIMIC-III). As mentioned earlier, our work also indicates that, regarding intra-subject scenario, a regression using age, sex, weight and subject index number—therefore without a PPG signal (or its attributes) as input—already reaches an excellent performance in line with AAMI and BHS standards. Finally, we discuss the reasons for it and provide guidelines on what we believe to be essential procedures to properly evaluate BP estimation from PPG only, in order to prevent overestimation of the results.

***
Back to the [Top](#Surveys)  
Back to https://github.com/Kwangkee/rPPG
