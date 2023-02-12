Back to https://github.com/Kwangkee/rPPG
***

## Daniel Mcduff
https://scholar.google.com/citations?hl=ko&user=m7Jr-b4AAAAJ&view_op=list_works&sortby=pubdate   

## Xin Liu
https://xliucs.github.io/  
https://scholar.google.com/citations?hl=en&user=p9F83HoAAAAJ&view_op=list_works&sortby=pubdate  

## Survey
Camera Measurement of Physiological Vital Signs, https://dl.acm.org/doi/10.1145/3558518   

## Papers
- [ACM 2022] [[MobilePhys: Personalized Mobile Camera-Based Contactless Physiological Sensing](https://github.com/Kwangkee/rPPG/blob/main/rPPG%40DanielMcduff.md#mobilephys)], https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=m7Jr-b4AAAAJ&sortby=pubdate&citation_for_view=m7Jr-b4AAAAJ:D_tqNUsBuKoC  
- [CVPR 2022] [[Federated Remote Physiological Measurement with Imperfect Data](https://github.com/Kwangkee/rPPG/blob/main/rPPG%40DanielMcduff.md#fl-rppg)], https://openaccess.thecvf.com/content/CVPR2022W/CVPM/html/Liu_Federated_Remote_Physiological_Measurement_With_Imperfect_Data_CVPRW_2022_paper.html  
- [Oct/2021] Learning Higher-Order Dynamics in Video-Based Cardiac Measurement, https://arxiv.org/abs/2110.03690 
- Non-contact imaging of peripheral hemodynamics during cognitive and psychological stressors, https://www.nature.com/articles/s41598-020-67647-6 
- MetaPhys: few-shot adaptation for non-contact physiological measurement, https://arxiv.org/abs/2010.01773 
- Deepphys: Video-based physiological measurement using convolutional attention networks, https://openaccess.thecvf.com/content_ECCV_2018/html/Weixuan_Chen_DeepPhys_Video-Based_Physiological_ECCV_2018_paper.html

## To Be Reviewed
- Seeing Beneath the Skin with Computational Photography, https://cacm.acm.org/magazines/2022/12/266927-seeing-beneath-the-skin-with-computational-photography/abstract

## FL rPPG 
[CVPR_2022] Federated Remote Physiological Measurement with Imperfect Data, https://openaccess.thecvf.com/content/CVPR2022W/CVPM/html/Liu_Federated_Remote_Physiological_Measurement_With_Imperfect_Data_CVPRW_2022_paper.html  
>In this paper, we propose a simple but effective version of federated averaging, called **FedWeight, by leveraging knowledge about the signal quality from each client**. Unlike FedAvg, which treats weights from all clients equally during model aggregation, our proposed leverages the fact that signal quality has a big impact on model performance to perform a more adaptive form of aggregation.
>
>"각 client data의 “noise level and signal quality”를 안다고 가정하고 논문을 썼으나, 이를 자동화 (automating signal quality measurement) 하는 것이 중요하고 actively working on building an range of automatic signal quality metrics to test"
>>**How to automate signal quality measurement?** In this paper, we assume the noise level and signal quality are available to the centralized server. This could be the case if clients were able to provide a data quality report based on their knowledge of their individual sensor noise profiles. However, automating signal quality measurement would be preferred in many real-world scenarios. We are aware of this limitation and actively working on building an range of automatic signal quality metrics to test. Inspired by the metric in the task of super resolution, we argue that Peak Signal-to-Noise Ratio (PSNR) could be one way of measuring image noise level and quality. Moreover, we are also actively studying using the patterns of training loss and the quality of estimated PPG signal to assess the quality of videos.
>
>>In the future, we plan to develop a system to of camera-based remote physiological measurement. Our automatically measure noise levels and signal quality using domain knowledge (e.g., skewness of PPG signal and PSNR in the image) in imaging and physiology as discussed in section 5. Finally, we performance experiments on datasets that are not fully representative of all physical appearances. Before similar sensing algorithms are deployed they would require further validation and clinical evaluation.

## MobilePhys
MobilePhys: Personalized Mobile Camera-Based Contactless Physiological Sensing, https://scholar.google.com/citations?view_op=view_citation&hl=ko&user=m7Jr-b4AAAAJ&sortby=pubdate&citation_for_view=m7Jr-b4AAAAJ:D_tqNUsBuKoC  

>DeepPhys -> MTTS-CAN -> MetaPhys -> MobilePhys 로 진화 中
>-	이론적으로 새로 제시하는 것은 없지만, 조명/움직임/skin Color/Device 등의 다양한 조건들을 갖는 Dataset을 구축했고, 
>-	데이터 수집/확보 환경, SmartPhone Camera의 특징 분석, 한계와 향후 방향을 나름 친절히 제시. 특히 개발/제안 중인 과제들을 위해 참고할 만한 insight 들이 많습니다. Must Read Article!!!
>- pseudo PPG labels 를 얻기 위해 POS 를 사용했는데 한계가 많아서, 후방 카메라 (index finger) 를 활용했고, 결과적으로 모든 환경 변화에 적응할 수 있는 우수한 personalization 확인  
>- 무엇보다 관심 가는 얘기는, We plan to release this dataset with this paper.  

## MMPD
MMPD: Multi-Domain Mobile Video Physiology Dataset, https://scholar.google.com/scholar?hl=ko&as_sdt=0%2C5&q=MMPD%3A+Multi-Domain+Mobile+Video+Physiology+Dataset&btnG=

- In an effort to help the field advance, we present the Multi-domain Mobile Video Physiology Dataset (MMPD), comprising 11 hours of recordings from mobile phones of 33 subjects. The dataset was designed to capture videos with greater representation across skin tone, body motion, and lighting conditions. MMPD is comprehensive with eight descriptive labels and can be used in conjunction with the rPPG-toolbox [1]. The Github repository of our dataset: https://github.com/McJackTang/MMPD_rPPG_dataset.
- To address gaps in existing public rPPG datasets, we introduce the multi-domain mobile video physiology dataset (MMPD). Our dataset includes 33 subjects with Fitzpatrick skin types 3-6, four different lighting conditions (LED-high, LED-low, incandescent, natural), and four different activities (stationary, head rotation, talking, and walking). All videos in MMPD were captured using mobile phones. 
- A total of 660 one-minute videos were recorded using a Samsung Galaxy S22 Ultra, while goldstandard PPG signals were simultaneously recorded using an HKG-07C+ oximeter. 

***
Back to the [Top](#rPPG)  
Back to https://github.com/Kwangkee/rPPG
