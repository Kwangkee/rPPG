Back to https://github.com/Kwangkee/rPPG
***

## Surveys
- [[Machine learning and deep learning for blood pressure prediction: A methodological review from multiple perspectives](https://github.com/Kwangkee/rPPG/blob/main/BP.md#machine-learning-and-deep-learning-for-blood-pressure-prediction)], https://link.springer.com/article/10.1007/s10462-022-10353-8 
- [[Advancement in the Cuffless and Noninvasive Measurement of Blood Pressure: A Review of the Literature and Open Challenges](https://github.com/Kwangkee/rPPG/blob/main/BP.md#advancement-in-the-cuffless-and-noninvasive-measurement-of-blood-pressure)], https://www.mdpi.com/2306-5354/10/1/27

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
## Advancement in the Cuffless and Noninvasive Measurement of Blood Pressure
- Advancement in the Cuffless and Noninvasive Measurement of Blood Pressure: A Review of the Literature and Open Challenges, https://www.mdpi.com/2306-5354/10/1/27

#### 8. Challenges and Future Recommendations
- The continuing research to get cuffless and noninvasive BP measurement model are facing challenges such as data collection, the accuracy of control data, standardization of public dataset, need for validation protocol, patient-specific issues, calibration, the efficiency of the algorithm, integration with the traditional method, issues with the specific dataset, deployment issues, and collaborations, etc. Along with discussing the challenges, there will be recommendations and ways forwards for the researcher to pursue their investigation.
- **커프리스 및 비침습적 BP 측정 모델을 얻기 위한 지속적인 연구는 데이터 수집, 제어 데이터의 정확성, 공개 데이터 세트의 표준화, 검증 프로토콜의 필요성, 환자별 문제, 교정, 알고리즘의 효율성, 기존 방법과의 통합, 특정 데이터 세트와 같은 과제에 직면해 있다.문제, 배치 문제, 협업 등의 문제가 있습니다. 과제에 대한 논의와 함께, 연구원이 조사를 계속할 수 있는 권장 사항과 방법이 있을 것이다.**

8.1. Data Collection and Accuracy of Control Data
8.2. Validation Protocol  
8.3. Calibration  
8.4. The Model or Technique Needs to Be Interpretable  
8.6. Necessity of Collaboration with a Health Professional  

***
## guidelines for a fair assessment
- Blood pressure estimation from photoplethysmography by considering intra- and inter-subject variabilities: guidelines for a fair assessment, https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=Blood+pressure+estimation+from+photoplethysmography+by+considering+intra-+and+inter-subject+variabilities%3A+guidelines+for+a+fair+assessment&btnG= 

- 많은 연구/논문들이 데이터 사용/관리에 문제가 있고, 결과적으로 과장된 결과를 보고하고 있다는 얘기. How about yours?

- Although the use of a single PPG for assessing hypertension is promising, the relationship between PPG and BP is not completely elucidated in fact. In an attempt to indirectly solve this issue, several authors, [27]–[39], have been reporting an accuracy in line with two guidelines, one by the American Association for the Advancement of Medical Instrumentation (AAMI) and the other published by the British Hypertension Society (BHS) [40], [41]. However, as observed by Schrumpf et al. (2021) [42], there is lack of information in the papers over the distribution of the dataset used by them to ensure (1) no mixing samples of the same subject and (2) equal data size per subject. Indeed, except for [43]–[45], authors which partially or completely follow this recommendation are finding errors far above the reference values [42], [46]–[50], denoting that such an estimation problem is not resolved yet. In this work, we investigate how intra- and inter-subject variabilities in BP lead to different results of machine learning algorithms. Moreover, by considering specifically the intra-subject scenario, we compare single PPG machine learning algorithms with a regression using age, sex, weight and subject index number as attributes, and obtain similar results, indicating that the algorithms might actually be learning to identify persons and not predicting BP.

- Alongside the previous studies, this work proposes to investigate how a single PPG signal can be used to estimate BP, with a representative set of machine learning algorithms covering both feature- and signal-based methods, but with an explicitly emphasis in the effect of the data arrangement—by considering intra- and inter-subject variabilities—in two frequently used databases: Multiparameter Intelligent Monitoring in Intensive Care II and III (MIMICII, MIMIC-III). As mentioned earlier, our work also indicates that, regarding intra-subject scenario, a regression using age, sex, weight and subject index number—therefore without a PPG signal (or its attributes) as input—already reaches an excellent performance in line with AAMI and BHS standards. Finally, we discuss the reasons for it and provide guidelines on what we believe to be essential procedures to properly evaluate BP estimation from PPG only, in order to prevent overestimation of the results.

***
Back to the [Top](#Surveys)  
Back to https://github.com/Kwangkee/rPPG
