Back to https://github.com/Kwangkee/rPPG
***

## Papers
- The Way to My Heart Is Through Contrastive Learning: Remote Photoplethysmography From Unlabelled Video, https://openaccess.thecvf.com/content/ICCV2021/html/Gideon_The_Way_to_My_Heart_Is_Through_Contrastive_Learning_Remote_ICCV_2021_paper.html
- Video-based Remote Physiological Measurement via Self-supervised Learning, https://scholar.google.com/scholar?hl=ko&as_sdt=0%2C5&q=Video-based+Remote+Physiological+Measurement+via+Self-supervised+Learning&btnG=
- Self-supervised representation learning framework for remote physiological measurement using spatiotemporal augmentation loss, https://scholar.google.com/scholar?hl=ko&as_sdt=0%2C5&q=Self-supervised+representation+learning+framework+for+remote+physiological+measurement+using+spatiotemporal+augmentation+loss&btnG=
- [[Self-Supervised RGB-NIR Fusion Video Vision Transformer Framework for rPPG Estimation](https://github.com/Kwangkee/rPPG/blob/main/rppg@SSL.md#self-supervised-rgb-nir-fusion)], https://ieeexplore.ieee.org/document/9931758
- [[Self-rPPG: Learning the Optical & Physiological Mechanics of Remote Photoplethysmography with Self-Supervision](https://github.com/Kwangkee/rPPG/blob/main/rppg@SSL.md#self-rppg)], https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=Self-rPPG%3A+Learning+the+Optical+%26+Physiological+Mechanics+of+Remote+Photoplethysmography+with+Self-Supervision&btnG=

## Self-Supervised RGB-NIR Fusion
- Self-Supervised RGB-NIR Fusion Video Vision Transformer Framework for rPPG Estimation, https://scholar.google.com/scholar?hl=ko&as_sdt=0%2C5&q=Self-Supervised+RGB-NIR+Fusion+Video+Vision+Transformer+Framework+for+rPPG+Estimation&btnG=

## Self-rPPG
- Self-rPPG: Learning the Optical & Physiological Mechanics of Remote Photoplethysmography with Self-Supervision, https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=Self-rPPG%3A+Learning+the+Optical+%26+Physiological+Mechanics+of+Remote+Photoplethysmography+with+Self-Supervision&btnG=

Abstract:  
- In this paper, we propose Self-rPPG, which directly learns the optical and physiological mechanics of rPPG from the unlabeled videos without any synchronized rPPG signal stream annotation. We design a self-supervised contrastive learning-based pretraining strategy to learn the representation of the underlying diffusion signals’ frequency, phase, and the video frames’ temporal coherence from unlabeled video frame sequences collected over multiple public datasets. 
- We run extensive experiments on the optimal contrastive learning schemes (loss functions, sampling strategy), and the saliency of the features learned by Self-rPPG, and show that our self-supervised presentations can successfully encode the diffusion signals’ frequency and phase while demonstrating robustness against temporal corruption. 
- The performance of Self-rPPG is validated on three public datasets where Self-rPPG outperforms the supervised state-of-the-art methods in PPG reconstruction and HR estimation using only 10% of the labeled data.

9 CONCLUSION  
- We propose and validate rPPG physics-inspired self-supervised methods to learn relevant rPPG features from unlabeled video data. Our self-supervised pretraining enables the network to perform heterogeneous rPPG reconstruction (finger, wrist) after finetuning with limited labeled data. 
- We demonstrate the efficacy of our approach by experimenting with heterogeneous camera sensors (DSRL, HD, NIR) of three public datasets. We further investigate the impact of our self-supervised components to elaborate on their impact on learning. Our insights enable further fine-grain development of generalized, robust rPPG systems using unlabeled video data.

***
Back to the [Top](#papers)  
Back to https://github.com/Kwangkee/rPPG
