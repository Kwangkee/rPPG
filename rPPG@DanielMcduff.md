Back to https://github.com/Kwangkee/rPPG
***

## Daniel Mcduff
https://scholar.google.com/citations?hl=ko&user=m7Jr-b4AAAAJ&view_op=list_works&sortby=pubdate  

## Xin Liu
https://xliucs.github.io/  
https://scholar.google.com/citations?hl=en&user=p9F83HoAAAAJ&view_op=list_works&sortby=pubdate  

## Papers
#### CVPR_2022 
>Federated Remote Physiological Measurement with Imperfect Data, https://openaccess.thecvf.com/content/CVPR2022W/CVPM/html/Liu_Federated_Remote_Physiological_Measurement_With_Imperfect_Data_CVPRW_2022_paper.html  
>>In this paper, we propose a simple but effective version of federated averaging, called **FedWeight, by leveraging knowledge about the signal quality from each client**. Unlike FedAvg, which treats weights from all clients equally during model aggregation, our proposed leverages the fact that signal quality has a big impact on model performance to perform a more adaptive form of aggregation.
>
>>"각 client data의 “noise level and signal quality”를 안다고 가정하고 논문을 썼으나, 이를 자동화 (automating signal quality measurement) 하는 것이 중요하고 actively working on building an range of automatic signal quality metrics to test"
>
>>How to automate signal quality measurement? 
>>In this paper, we assume the noise level and signal quality are available to the centralized server. This could be the case if clients were able to provide a data quality report based on their knowledge of their individual sensor noise profiles. However, automating signal quality measurement would be preferred in many real-world scenarios. We are aware of this limitation and actively working on building an range of automatic signal quality metrics to test. Inspired by the metric in the task of super resolution, we argue that Peak Signal-to-Noise Ratio (PSNR) could be one way of measuring image noise level and quality. Moreover, we are also actively studying using the patterns of training loss and the quality of estimated PPG signal to assess the quality of videos.
>
>>In the future, we plan to develop a system to of camera-based remote physiological measurement. Our automatically measure noise levels and signal quality using domain knowledge (e.g., skewness of PPG signal and PSNR in the image) in imaging and physiology as discussed in section 5. Finally, we performance experiments on datasets that are not fully representative of all physical appearances. Before similar sensing algorithms are deployed they would require further validation and clinical evaluation.




***
Back to the [Top](#rPPG)  
Back to https://github.com/Kwangkee/rPPG
