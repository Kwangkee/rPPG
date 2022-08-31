Back to https://github.com/Kwangkee/rPPG
***

## MobilePhys
MobilePhys: Personalized Mobile Camera-Based Contactless Physiological Sensing, https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=m7Jr-b4AAAAJ&sortby=pubdate&citation_for_view=m7Jr-b4AAAAJ:D_tqNUsBuKoC  

>DeepPhys -> MTTS-CAN -> MetaPhys -> MobilePhys 로 진화 中
>-	이론적으로 새로 제시하는 것은 없지만, 조명/움직임/skin Color/Device 등의 다양한 조건들을 갖는 Dataset을 구축했고, 
>-	데이터 수집/확보 환경, SmartPhone Camera의 특징 분석, 한계와 향후 방향을 나름 친절히 제시. 특히 개발/제안 중인 과제들을 위해 참고할 만한 insight 들이 많습니다. Must Read Article!!!
>- pseudo PPG labels 를 얻기 위해 POS 를 사용했는데 한계가 많아서, 후방 카메라 (index finger) 를 활용했고, 결과적으로 모든 환경 변화에 적응할 수 있는 우수한 personalization 확인  
>- 무엇보다 관심 가는 얘기는, We plan to release this dataset with this paper.  

## VitalSeer
VitalSeer: The development of a contactless sensing technology based on a user-centric data-driven clinical approach - NCBI, https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9285145/  

This paper presents the outcome of a multidisciplinary collaboration to ensure clinical usability of a remote contactless sensing technology, VitalSeer, and to help close gaps between emerging technologies and clinical practice. 
The studies on volunteers demonstrated the accuracy of VitalSeer’s heart rate model at a low MAE of 0.74 (bpm) and a RMSE of 1.2 bpm, **below the threshold of clinical grade contact-based sensors.**

VitalSeer software aims to conduct remote monitoring of critical vital signs including HR, RR and SpO2. 

## Revise 
Revise: Remote vital signs measurement using smartphone video camera (2022), https://arxiv.org/abs/2206.08748   

#### Veyetals App
- https://veyetals.com/
-	https://veyetals.com/pricing-and-features/ 무료 버전 & 유료 버전
-	https://www.youtube.com/watch?v=peot6UUbEU0 정확도 90% 이상이고, 전문가 (의사?) 들도 좋다고 한다는데 ….


## A Web Application for Experimenting and Validating Remote Measurement of Vital Signs 
A Web Application for Experimenting and Validating Remote Measurement of Vital Signs, https://arxiv.org/abs/2208.09916
  >- [23] Qiao D., Zulkernin, F.M.R.R.R.J.N.: Measuring heart rate and heart rate variability with smartphone camera. 22nd IEEE International Conference on Mobile Data Management (MDM) (2021), https://sensights.ai/wp-content/uploads/2021/05/Measuring-Heart-Rate-and-Heart-Rate-Variability-with-Smartphone-Camera-1.pdf   
  >- [24] Qiao D., Ayesha A., Z.F.M.R.J.N.: Revise: Remote vital signs measurement using smartphone video camera (2022), https://arxiv.org/abs/2206.08748   
  >- Heart Rate Monitoring Using PPG With Smartphone Camera, https://ieeexplore.ieee.org/abstract/document/9669735/
  
#### We propose a web-based, publicly accessible ubiquitous framework for estimating six vitals namely, Heart Rate (HR), Heart Rate Variability (HRV), Respiration Rate (RR), Oxygen Saturation (SpO2), Blood Pressure (BP), and stress, which handles movement and illumination artifacts prevalent in real life. We validate the accuracy, robustness, usability and functionality of the rPPG models in estimating the vitals from face videos.

In this paper,   
(1) we present a web application framework with a back-end server as shown in Fig. 1 for remote web-based measurement of vitals signs namely HR, HRV, SpO2, RR, BP and stress in near real-time using a privacy preserving face video captured with a device camera.   
(2) We validate the rPPG technology using our web application in the real world environment with different sources of light, varying camera resolutions, multiple browsers, several devices, and networks.   
(3) Extensive research was done to explore existing rPPG methods [23] and improve the BVP signal by diminishing motion and light noises encountered in real world environment and giving the user appropriate messages to capture a good quality video. In this version of the application, scalability and load balancing was not addressed. Instead, we focused mainly on validating the accuracy of the framework in the real world.  

#### 3.1 Subsystem 1: Front-end Web Interface The front-end web interface shown in Fig. 2 can be accessed on the browser via a public web URL    
  >https://vital-signs-bamlab.tk/    

#### 3.2 Subsystem 2: Back-end Data Processing The back-end hosts a Python 3.8 application on the server.    
The videos received from Subsystem 1 are saved on the server, processed and analyzed to extract the raw PPG signals and reduce noises due to changes in light intensity and motion to obtain a robust BVP signal for higher accuracy of vital signs. We used the state-of-the-art methods from Qiao et al [24] for vital sign estimation as explained briefly in Section 2.2 and improve the noise filtering techniques (selecting the best RoI, guiding user by UI messaging) while validating the framework in real life environment.   

#### 3.3 Subsystem 3: SQLite Database   

## BloodPressureDB.com
https://www.bloodpressuredb.com/start.html
- Record your blood pressure simply and securely
- Use your browser or the app for your smartphone
- Get a blood pressure chart (incl. PDF) - for self control or to assist your doctor
- free

#### 다 좋은데, 사용성 단절 개선 필요 
> 사용자가 별도 device로 BP 측정 후 수기 입력 -> rPPG 적용으로 대체하면!!! 

***
Back to the [Top](#rPPG)  
Back to https://github.com/Kwangkee/rPPG
