---
title: "Research Interest (IV): The development of a two-view tomographic reconstruction framework"
excerpt: ""
collection: research
---

My breakthrough work in two orthogonal view tomographic reconstructions with soft-tissue visibility has had a profound impact on both fields of diagnostic imaging and radiation therapy.

Historically, two orthogonal scout or cone-beam kV images were used to perform patient localization and radiation dose modulation. Its performance was limited by the 2D nature without the knowledge of accurate 3D volumetric information. The proposed AI model ScoutCT-NET [3] was trained on millions of clinical data points and addressed the issue by successfully generating 3D volumetric CT images from two orthogonal 2D kV images. In my work, ScoutCT-NET demonstrated significantly improved performance in patient localization, radiation exposure control, and radiation dose modulation. 

My pioneering research on two-view reconstruction in diagnostic imaging attracted attention from researchers seeking breakthroughs in image-guided radiation cancer treatment. 

Zhang et al. [12] emphasized the superiority of ScoutCT-NET over related works on the topic of two orthogonal view reconstruction. They applauded the technical contribution of ScoutCT-NET which leveraged a frozen domain transform layer and a refinement network. The paper highlighted that the unique design of ScoutCT-NET produces impressive results in terms of soft-tissue contrast. Due to this reason, this citing work adopted the reconstruction framework from ScoutCT-NET to enhance the soft-tissue visibility which is critical to image guided cancer treatment. They also replaced the domain transform layer in ScoutCT-NET with an offline algorithm to save the computational cost. The extension of ScoutCT-NET enabled the dose calculation and evaluation in broader applications of adaptive image-guided photon and proton radiation therapy. 

[3] Juan Montoya (Co-First), Chengzhu Zhang (Co-First), Yinsheng Li, Ke Li, Guang‐Hong Chen. "Reconstruction of three‐dimensional tomographic patient models for radiation dose modulation in CT from two scout views using deep learning." Medical Physics 49.2 (2022): 901-916.

[12] Zhang, Yikun, et al. "2V-CBCT: Two-Orthogonal-Projection based CBCT Reconstruction and Dose Calculation for Radiation Therapy using Real Projection Data." IEEE Transactions on Medical Imaging (2024).