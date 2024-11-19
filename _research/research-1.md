---
title: "Research Interest (I): Development of quality-assured AI-based image reconstruction framework"
excerpt: ""
collection: research
---



I proposed a quality-assured AI-based tomographic image reconstruction method, termed DL-PICCS, which is a seamless combination of powerful AI models and compressed sensing to ensure the robust performance of AI models on clinical patient data [2.1, 2.2].

My work on this subject is vital because it urges the medical physics community to critically examine the generalizability and robustness of the AI-based tomographic image reconstruction models. I found that not all patient-specific image content can be preserved in AI-generated output images and the performance of the existing AI models was often suboptimal when they are applied to unseen clinical data. Both issues are serious in medical applications and must be addressed before the clinical translation of these AI models.
To address this problem, I leveraged the AI output image as the high-quality patient prior image and incorporated it into the compressed sensing framework which enforces data consistency. The proposed scheme preserved critical anatomical and pathological information while existing AI models failed to do so. I used this framework to successfully address two challenging problems that bothered the community for years: the sparse-view CT [1] and high-pitch helical CT [2].

My research sparked a series of works that focused on the accuracy and robustness of AI-based image reconstruction models.

### Notable Citations
DRONE developed by Wu et al [3] was inspired by my work and incorporated additional deep learning prior from CT data into DL-PICCS framework. This citing paper demonstrated that DL-PICCS and DRONE offer better image quality in terms of edge-preserving, feature recovery, and reconstruction accuracy than existing state-of-the-art AI models such as FBPConvNet and HDNet.

A subsequent work DEAR from Wu et al. [4] perform multiple iteration of the enhanced DL-PICCS framework to further improve the CT image quality. It demonstrated that DL-PICCS and DEAR are superior to the state-of-the-art sparse-view CT reconstruction methods such as TVM and FBPConvNet in terms of data consistency, edge-preserving, and feature perseveration.

In addition, Zhang et al. [5] applied DL-PICCS to the task of dual energy CT under a limited view data condition. The citing paper demonstrated the DL-PICCS provided improved image details by utilizing information in the different energy channels. Moreover, DL-PICCS was significantly superior to the state-of-the-art AI-based limited view angle CT problem, such as SPECIAL, DD-Net on all evaluation metrics.

The application of DL-PICCS to high-pitch helical CT was patented [6].

### Reference
[1] [Chengzhu Zhang, Yinsheng Li, Guang‐Hong Chen. "Accurate and robust sparse‐view angle CT image reconstruction using deep learning and prior image constrained compressed sensing (DL‐PICCS)." Medical Physics 48.10 (2021): 5765-5781.](/_publication/2021-DL-PICCS-1.md)

[2] [Hayes J W, Montoya J, Budde A, et al. High pitch helical CT reconstruction[J]. IEEE Transactions on Medical Imaging, 2021, 40(11): 3077-3088.](/_publication/2021-HighPitch-3.md)

[3] Weiwen Wu, et al. "DRONE: Dual-domain residual-based optimization network for sparse-view CT reconstruction." IEEE Transactions on Medical Imaging 40.11 (2021): 3002-3014.

[4] Wu, Weiwen, et al. "Deep embedding-attention-refinement for sparse-view CT reconstruction." IEEE Transactions on Instrumentation and Measurement (2022).

[5] Zhang Y, Hu D, Lyu T, et al. PIE-ARNet: Prior image enhanced artifact removal network for limited-angle DECT[J]. IEEE Transactions on Instrumentation and Measurement, 2022, 72: 1-12.

[6] Chen G H, Hsieh J. Systems and methods for computed tomography image reconstruction: U.S. Patent 11,908,044. 2024-2-20.