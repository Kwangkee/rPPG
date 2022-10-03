Back to https://github.com/Kwangkee/rPPG
***

## PPG
[[The use of photoplethysmography for assessing hypertension](https://github.com/Kwangkee/rPPG/blob/main/rPPG4BP.md#the-use-of-photoplethysmography-for-assessing-hypertension)], https://www.nature.com/articles/s41746-019-0136-7
>[한글 해설] https://jiryang.github.io/2020/06/04/PPG4BP/  

[[Blood Pressure Prediction by a Smartphone Sensor using Fully Convolutional Networks](https://github.com/Kwangkee/rPPG/blob/main/rPPG4BP.md#blood-pressure-prediction-by-a-smartphone-sensor-using-fully-convolutional-networks)], https://ieeexplore.ieee.org/document/9175902

## Contact vs. Non-contact methods  
- [Smartphones and Video Cameras: Future Methods for Blood Pressure Measurement](https://github.com/Kwangkee/rPPG/blob/main/rPPG4BP.md#smartphones-and-video-cameras-future-methods-for-blood-pressure-measurement), https://www.frontiersin.org/articles/10.3389/fdgth.2021.770096/full
- [Blood pressure measurement using only a smartphone](https://github.com/Kwangkee/rPPG/blob/main/rPPG4BP.md#blood-pressure-measurement-using-only-a-smartphone), https://www.nature.com/articles/s41746-022-00629-2

***
## The use of photoplethysmography for assessing hypertension
The use of photoplethysmography for assessing hypertension, https://www.nature.com/articles/s41746-019-0136-7
>[한글 해설] https://jiryang.github.io/2020/06/04/PPG4BP/  

![image](https://user-images.githubusercontent.com/109835677/184668411-5d2a4533-71b6-43e0-a047-6331d8b8873f.png)
![image](https://user-images.githubusercontent.com/109835677/184668436-233ba032-1084-40da-b95a-9569de08896b.png)
![image](https://user-images.githubusercontent.com/109835677/184668584-7104bf00-2616-41e1-b00b-9c09d255c7b8.png)

***
## Blood Pressure Prediction by a Smartphone Sensor using Fully Convolutional Networks
Blood Pressure Prediction by a Smartphone Sensor using Fully Convolutional Networks, https://ieeexplore.ieee.org/document/9175902

[삼성전자, PPG:RGB+IR]   
In this paper, we propose a method for predicting BP without feature extraction using only PPG signals measured by smartphone using the convolutional neural networks (CNN) model proposed in the previous study [11]. Instead of using additional physiological cardiovascular signals, multiple wavelengths of PPG (infrared, red, green, blue) signals were measured using the smartphone’s heart rate monitor sensor and analyzed to determine the optimal combination of PPG signals for predicting systolic BP (SBP) and diastolic BP (DBP).  
This combination had an overall mean absolute error (MAE) of 5.28 and 4.92 mmHg for systolic and diastolic BP, respectively. Thus, our CNN-based approach achieved comparable results to other approaches that use a single PPG signal.
PPG data were acquired using the heart rate sensor of the Samsung Galaxy Note8 smartphone. 

#### Implications:
삼성 note 일부 version 에서 “IR 대역 포함 내장 PPG sensor” 지원. 이후 사양에서 제외?  
삼성 발표 논문은 SpO2 검출이 아니라, BP를 좀 더 정확하게 측정하기 위해 IR 유효.   


## Non-contact imaging of peripheral hemodynamics during cognitive and psychological stressors
Non-contact imaging of peripheral hemodynamics during cognitive and psychological stressors, https://www.nature.com/articles/s41598-020-67647-6


***
## Smartphones and Video Cameras: Future Methods for Blood Pressure Measurement
Smartphones and Video Cameras: Future Methods for Blood Pressure Measurement, https://www.frontiersin.org/articles/10.3389/fdgth.2021.770096/full

![image](https://user-images.githubusercontent.com/109835677/184624740-2b4ab3f0-dabe-429f-9db1-65eb5f04eb1f.png)
![image](https://user-images.githubusercontent.com/109835677/184625429-4d245fc1-fcb5-4224-b623-775f1f6b5dcc.png)

#### Discussion, Perspectives, and Future Outlook

Smartphone BP monitors are potentially applicable to ambulatory BP monitoring (examining BP continuously during the day). 
>Measurements in a doctor's office are affected by “white coat” syndrome, where patients are recorded as possessing a higher BP recording when measured clinically. Since BP varies throughout the day, improved understanding of how and why these changes occur could assist physicians in prescribing medication. Smartphones may measure pressure easily, with no additional equipment required beyond the phone or case. In contrast, cuffs may be awkward and bulky, inducing arm soreness or rashes after multiple daily uses (78). Although a smartphone may not be used at night when the user is asleep, video cameras with infrared light can monitor vital signs using similar techniques as those developed for the smartphone (79).

Non-contact methods possess other advantages. 
>Non-contact methods acquire images of multiple regions simultaneously. This enables simultaneous analysis of waveform shape and PTT. Different regions of the body could be affected differently by the sympathetic and parasympathetic nervous system, which is not accounted for through analysis of a single region. 

Several published methods possess a mean error ± standard deviation within the clinically acceptable 5 ± 8 mmHg. 
> In a follow-up study of the Anura TOI-based smartphone app (81), lower BPs tended to be overpredicted, while higher BPs were underpredicted. This was attributed to more limited training data at the extreme ends of BP (81).
>
>81. Yang D, Xiao G, Wei J, Luo H. Preliminary assessment of video-based blood pressure measurement according to ANSI/AAMI/ISO81060-2: 2013 guideline accuracy criteria: Anura smartphone app with transdermal optimal imaging technology. Blood Press Monit. (2020) 25:295–8. doi: 10.1097/MBP.0000000000000467
>>- Preliminary assessment of video-based blood pressure measurement according to ANSI/AAMI/ISO81060-2: 2013 guideline accuracy criteria: Anura smartphone app with transdermal optimal imaging technology, https://pubmed.ncbi.nlm.nih.gov/32842022/  
>>[Fulltext] https://journals.lww.com/bpmonitoring/Fulltext/2020/10000/Preliminary_assessment_of_video_based_blood.12.aspx?casa_token=oB2b5gcUBOEAAAAA:AVEF3Zp9KLx1Uj4QV0UQOwyc8w8VA1tToe4K9WnoqL1HOd035KfUnU5MSy1kdl4T6LmioklAq70QRPbnmTplswC4LA   

Many studies do not meet criteria for validating BP devices. 
>In addition to the AAMI criteria of MAE 5 ± 8 mmHg, several other criteria are listed (82), such as: at least 85 subjects; probability of tolerable errors <10 mmHg is at least 85 %, where a tolerable error is calculated as an average of three measurements against a reference BP; reference BP measurements acquired by two observers; and recording of number of absolute BP differences within 5, 10, and 15 mmHg. The protocol must cover a sufficient time frame to ensure that as the measurement device ages, accuracy is not reduced (83). 
>
>Many clinical validation protocols are tested on new models, without testing sustained accuracy over time, even though BP devices such as sphygmomanometers decline in accuracy over 18-months (84, 85). Over time, an individual may undergo physical changes in skin (i.e., aging) or changes in size, which may influence PPG extraction and BP estimation. Nevertheless, since non-contact methods should be applicable across camera types and imaging conditions, algorithms trained on data from a variety of subject types (age, sex, still vs. movement, range of skin tones and types) should be accurate for a sustainable time period.

TOI possesses advantages to other techniques for clinical translation. 
>The sample size of Luo et al. (36) is over 1,300; 155 features over 17 ROIs relating to waveform shape, population demographics and PTT predicted BP. This is advantageous over methods with small sample size and those that only measure PTT or analyze a single region. A disadvantage of limiting measurements to PTT is the phase shift used to measure PTT partially depends on skin variability/inhomogeneity, affecting PTT accuracy (63).
>Luo et al. (36) acquired images under strict conditions: normotensive, and consistent lighting and camera angle. Future studies may include a wider range of pressures to determine whether TOI may predict hypertension, and a variety of camera angles and lighting conditions.

Additional possibilities are outlined in (90). 
>This includes (A) development of techniques and models robust to “real-life” conditions such shadowing or movement; (B) application of infrared light, which acquires videos in dark conditions and may be less sensitive to variable ambient lighting; (C) development of a large publicly available dataset, where different algorithms may be applied and compared; (D) extraction of additional features beyond PTT; (E) development of a model requiring fewer calibrations.

Smartphone and video BP measurements will likely become more common. 
>Compared to cuff-based techniques, they are cost-effective and convenient. Using a single video, BP may be combined with heart rate detection and stress assessment (66), blood oxygen saturation (23), and blood flow. This technology can be developed for improved digital health consultations to assess a number of health conditions. For example, measurement of the multiple parameters described above currently requires a visit to a medical health professional. This is time consuming, and may necessitate meetings with multiple health professionals.

As methods and techniques for processing video images advances, it is foreseeable a video consultation over Zoom can relay to a doctor/nurse a patient's vitals (heart rate, BP, oxygen saturation, respiratory rate, etc.) and relate this information to stroke risk or susceptibility to cardiovascular disease. This information would be provided in real-time and reduce the need for manual measurements by a medical professional. 
>In addition, through continuous and regular daily monitoring of their own vitals privately with a smartphone, patients can be alerted via algorithms whether further treatment is necessary. Ambulatory BP monitoring (BP monitoring at regular intervals during day, such as via a video camera) may detect abnormal variations in BP not detectable with a single BP measurement session at a doctor's office. Furthermore, ambulatory BP has been demonstrated to correlate more strongly with organ damage caused by hypertension than BP measurements conducted in a clinical setting (91). Data acquired via smartphone may be automatically directed to a health care team for further discussions and medical decisions. Such technology can be extended to blood sugar measurements for diabetes patients, and other information related to cholesterol, fats, and hemoglobin (92). 
>
>Video technology could be on the cusp of a future where a patient's home is transformed into a “smartphone-based doctor's office” where numerous cardiovascular or blood-related metrics are assessed that would previously require expertise and communication across multiple health divisions.


## Blood pressure measurement using only a smartphone
Blood pressure measurement using only a smartphone, https://www.nature.com/articles/s41746-022-00629-2
>Published in partnership with Seoul National University Bundang Hospital

#### Abstract
>There is no consistency regarding the methods for blood pressure data collection and the reference blood pressure measurement and validation. Moreover, no established protocol is currently available for the validation of blood pressure measuring technologies using only a smartphone. 


In our literature search, we found only two publications that are dedicated to contactless BP estimation with a smartphone32,33. However, the number of articles on rPPG-based BP estimation increases substantially if the constraint of using only a smartphone is removed. 
>32. Patil, O. R., Wang, W., Gao, Y. & Jin, Z. A camera-based pulse transit time estimation approach towards non-intrusive blood pressure monitoring. In 2019 IEEE
International Conference on Healthcare Informatics (ICHI), Xi’an, China, 1–10, https://doi.org/10.1109/ICHI.2019.8904498 (IEEE, 2019). https://ieeexplore.ieee.org/abstract/document/8904498
>33. Luo, H. et al. Smartphone-based blood pressure measurement using transdermal optical imaging technology. Circulation: Cardiovasc. Imaging 12, e008857 (2019), https://www.ahajournals.org/doi/10.1161/CIRCIMAGING.119.008857


#### Discussion  
The purpose of this review is to assess the current state in the literature and guide future research dedicated to BP monitoring using only a smartphone. To that end, we conducted an extensive literature search to identify previous studies in the field of BP measurement with only a smartphone. Although numerous articles propose cuffless BP monitoring methods involving a smartphone, a majority incorporates additional devices, such as wristbands, chest bands, ECG sensors, or a second smartphone. 
>**It is particularly striking that there have been such a small number of studies focusing on non-contact smartphone-based BP estimation. Most articles dedicated to noncontact BP estimation rely on an advanced camera setup.**
```
Binah 의 BP는?
Nuralogix 의 BP는?
```

Second, BP monitoring is usually conducted in clinical settings. However, according to O’Brien et al.67, BP monitoring in an ambulatory setting has several advantages over clinical BP monitoring. 
>These include the possibility of acquiring a BP profile in the patient’s usual daily environment, a larger number of readings taken over a longer time period, and assessment of BP variability over 24 h. Furthermore, ambulatory BP monitoring is a stronger predictor of cardiovascular morbidity and mortality than clinical BP monitoring. 

Measuring BP with a smartphone has great potential for alleviating the current limitations in BP monitoring. **As a device with unparalleled ubiquity, it has the potential to serve as a cost-effective and unobtrusive BP monitor, paving the way for long-term ambulatory BP monitoring on a large scale.** Two main facets of BP estimation with only a smartphone were identified in the literature: video-based non-contact methods where all the information is extracted from a facial video sequence and contact methods that require direct contact between the measurement site and the sensor. 
>As seen in our analysis, non-contact methods based on facial videos have the advantage of not being limited to a single measurement site, making them less susceptible to physiological irregularities. **The possibility of acquiring signals simultaneously from multiple ROIs with the same sensor, i.e., the camera, is another asset to the non-contact approach, as it enables the estimation of PTT without the need of an additional signal from another sensor.** Furthermore, acquiring the signal in a contactless manner avoids the deformation of the arterial wall caused by pressing the finger on the camera, which can lead to inaccurate measurements due to changes in the optical properties of the tissue induced by deformation, or due to a hampered blood circulation in the arteries and capillaries underneath the skin. 
```
non-contact methods (facial, rPPG) 가 contact methods (finger, PPG) 보다 장점이라는 입장?
```

The forgoing analysis of the existing literature has shown that BP monitoring with only a smartphone is not ready for clinical use yet. 
>First, only six of the 25 studies satisfied the accuracy threshold for clinical acceptance. 
>
>Second, clinical validation with a clear protocol that sets strict guidelines for experimental design remains missing. We identified a large variety of experiment designs and participant pools, which complicates the comparison of the performance of different approaches. Furthermore, testing and validating the methods with small sample sizes is an unreliable performance indicator, as results may differ considerably when tested on larger samples. 
>
>Third, most experiments were conducted in lab environments that do not represent real-life situations. Based on our findings throughout this review, we recommend the following:

#### Based on our findings throughout this review, we recommend the following:

- Future research must pay more attention to the underlying data that they use. 
>First, the participant sample sizes should be chosen in accordance with the guidelines provided in established validation protocols. For an AAMI/ESH/ISO validation study, at least 85 subjects are required. 
>
> Second, the inclusion and exclusion criteria should be clearly communicated. 
>
> Third, the participant sample must include a broad spectrum of subjects representative of a possible target population. This includes subjects with different hypertensive status, skin tone, age, gender, and comorbidities.

- Incorporating demographic information into BP estimation models can improve accuracy. Future articles should take advantage of such information that can easily be collected from the subjects. Especially in data-driven methods, prior research has shown that categorizing the dataset according to physiological and demographic information improves estimation accuracy.

- Investigating pregnant populations is particularly important, as detecting hypertension at an early stage and relevant measures for it can slow down or prevent disease progression19. The same holds for pediatric populations.

- In order to be applicable in clinical use, future articles need to validate their methods in real-world environments beyond a fixed lab setup. Non-contact BP measurement methods need to be robust to environmental changes, such as alternating lighting conditions and motion artifacts. The same holds true for contact methods susceptible to noise, given that they rely on heart sound signals to estimate BP.

- Future research must scrutinize the calibration of smartphones for BP monitoring. It is important to know how accuracy evolves over time, i.e., how frequently a smartphone needs to be calibrated and whether a calibration can be carried out by the patients themselves.

### CONCLUSION

Our literature search has shown a clear increase in research activity in the field of BP estimation with only a smartphone over the last decade. Methods of estimating BP through pulse wave analysis have especially gained momentum. Technical advancements in smartphone cameras and processors and an ever-growing demand for video-based communication technology have made an imminent breakthrough in non-contact BP monitoring likely. Weaving BP monitoring unobtrusively into our everyday lives as we face screens throughout the day has the potential for cost-effective early detection and large-scale monitoring of hypertension. Contact-based BP measurement, on the other hand, may prove useful in settings where screen time is considerably lower.

**Despite these promising tendencies, the proposed approaches are not yet ready for clinical validation.** Indeed, not a single smartphone application for BP measurement has been approved for medical use yet. Of the 25 articles, six satisfied the pass-fail criterion 1 of the AAMI/ESH/ISO 81060-2:2018 norm, i.e., mean systolic and diastolic BP difference and their standard deviation smaller or equal to 5 ± 8 mmHg. Nonetheless, further research is necessary to improve the accuracy and robustness of BP estimation using only a smartphone. 

Moreover, as there is no established validation protocol available for smartphone-based BP measurement technologies at present, establishing an internationally accepted protocol for clinical validation is a pivotal step towards the clinical use of such technology. Data security is another issue that needs to be dealt with once the technology is ready for use. **In conclusion, smartphone-based BP monitoring has the potential to make regular long-term BP monitoring accessible to a large section of society, thus contributing substantially to the immense challenge of detection, diagnosis, and monitoring of hypertension. Much further study is needed, however, to make this a reality.**



***
Back to the [Top](#papers)  
Back to https://github.com/Kwangkee/rPPG
