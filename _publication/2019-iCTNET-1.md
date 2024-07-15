---
title: "Learning to reconstruct computed tomography images directly from sinogram data under a variety of data acquisition conditions"
collection: publication
permalink: /publication/2019-iCTNET-1
authorship: 'coauthor'
excerpt: 'iCT-Net is a such a cool network that was inspired by the filtered-backprojection algorithm but with everything learned through data. It is an end-to-end reconstruction network that consists of three major modules, data rectification module, feature learning module and backprojection module. The data rectification module preprocesses the noisy data from a real CT scanner. The feature learning module learns the essential filtering process and beyond to avoid data contamination in the traditional convolutional process. Then backprojection module enables domain transform and end-to-end learning. The proposed iCT-Net is an intelligent reconstruction framework to address multiple challenging reconstruction problems.'
date: 2019-4-11
venue: 'IEEE Transactions on Medical Imaging'
paperurl: 'http://mp-czhang.github.io/files/iCTNet.pdf'
citation: 'Li, Yinsheng, et al. "Learning to reconstruct computed tomography images directly from sinogram data under a variety of data acquisition conditions." IEEE transactions on medical imaging 38.10 (2019): 2469-2481.'
---

Computed tomography (CT) is widely used in medical diagnosis and non-destructive detection. Image reconstruction in CT aims to accurately recover pixel values from measured line integrals, i.e., the summed pixel values along straight lines. Provided that the acquired data satisfy the data sufficiency condition as well as other conditions regarding the view angle sampling interval and the severity of transverse data truncation, researchers have discovered many solutions to accurately reconstruct the image. However, if these conditions are violated, accurate image reconstruction from line integrals remains an intellectual challenge. In this paper, a deep learning method with a common network architecture, termed iCT-Net, was developed and trained to accurately reconstruct images for previously solved and unsolved CT reconstruction problems with high quantitative accuracy. Particularly, accurate reconstructions were achieved for the case when the sparse view reconstruction problem (i.e., compressed sensing problem) is entangled with the classical interior tomographic problems.