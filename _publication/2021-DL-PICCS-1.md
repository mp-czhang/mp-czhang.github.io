---
title: "Accurate and robust sparse‐view angle CT image reconstruction using deep learning and prior image constrained compressed sensing (DL‐PICCS)"
collection: publication
permalink: /publication/2021-DL-PICCS-1
authorship: 'first'
excerpt: 'DL-PICCS is my first peer-reviewed work in my PhD career. At that time, there was an arms race in the field of deep learning-based reconstruction. The purpose of this works to warn the community the contridiction of personalized nature of CT image reconstruction and the statistical regression nature of the deep learning model. DL-PICCS was born to enforce the deep learning models to be data consistent without having to build the data consistency module into the network. It utilized the framework of the well-known PICCS method developed by my PhD advisor. The deep leanring reconstructed image is served as an prior image and the final image is jointly optimized by both the deep learning prior image and a handcrafted regulalizer from the wisdom of compressed sensing in the past 15 years. In this paper, DL-PICCS corrects false positive and false negative anatomical structures and significantly boosts the image quality.'
date: 2021-10-1
venue: 'Medical physics'
paperurl: 'http://mp-czhang.github.io/files/dlpiccs.pdf'
citation: 'Zhang, Chengzhu, Yinsheng Li, and Guang‐Hong Chen. "Accurate and robust sparse‐view angle CT image reconstruction using deep learning and prior image constrained compressed sensing (DL‐PICCS)." Medical physics 48.10 (2021): 5765-5781.'
---

## Background
Sparse-view CT image reconstruction problems encountered in dynamic CT acquisitions are technically challenging. Recently, many deep learning strategies have been proposed to reconstruct CT images from sparse-view angle acquisitions showing promising results. However, two fundamental problems with these deep learning reconstruction methods remain to be addressed: (1) limited reconstruction accuracy for individual patients and (2) limited generalizability for patient statistical cohorts.

## Purpose 
The purpose of this work is to address the previously mentioned challenges in current deep learning methods.

## Methods
A method that combines a deep learning strategy with prior image constrained compressed sensing (PICCS) was developed to address these two problems. In this method, the sparse-view CT data were reconstructed by the conventional filtered backprojection (FBP) method first, and then processed by the trained deep neural network to eliminate streaking artifacts. The outputs of the deep learning architecture were then used as the needed prior image in PICCS to reconstruct the image. If the noise level from the PICCS reconstruction is not satisfactory, another light duty deep neural network can then be used to reduce noise level. Both extensive numerical simulation data and human subject data have been used to quantitatively and qualitatively assess the performance of the proposed DL-PICCS method in terms of reconstruction accuracy and generalizability.

## Results
Extensive evaluation studies have demonstrated that: (1) quantitative reconstruction accuracy of DL-PICCS for individual patient is improved when it is compared with the deep learning methods and CS-based methods; (2) the false-positive lesion-like structures and false negative missing anatomical structures in the deep learning approaches can be effectively eliminated in the DL-PICCS reconstructed images; and (3) DL-PICCS enables a deep learning scheme to relax its working conditions to enhance its generalizability.

## Conclusions
DL-PICCS offers a promising opportunity to achieve personalized reconstruction with improved reconstruction accuracy and enhanced generalizability.