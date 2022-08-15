Back to https://github.com/Kwangkee/rPPG
***

Kang Lee, https://github.com/Kwangkee/rPPG/blob/main/rPPG@KangLee.md  
Nuralogix, https://github.com/Kwangkee/rPPG/blob/main/rPPG@Nuralogix.md#nuralogix-research

## Papers 
- [Blood pressure measurement using only a smartphone](https://github.com/Kwangkee/rPPG/blob/main/rPPG4BP.md#blood-pressure-measurement-using-only-a-smartphone), https://www.nature.com/articles/s41746-022-00629-2
- [Non-contact imaging of peripheral hemodynamics during cognitive and psychological stressors](https://github.com/Kwangkee/rPPG/blob/main/rPPG4BP.md#non-contact-imaging-of-peripheral-hemodynamics-during-cognitive-and-psychological-stressors), https://www.nature.com/articles/s41598-020-67647-6


***

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


## Non-contact imaging of peripheral hemodynamics during cognitive and psychological stressors
Non-contact imaging of peripheral hemodynamics during cognitive and psychological stressors, https://www.nature.com/articles/s41598-020-67647-6


***
Back to the [Top](#papers)  
Back to https://github.com/Kwangkee/rPPG
