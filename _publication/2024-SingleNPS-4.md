---
title: "Experimental measurement of local noise power spectrum (NPS) in photon counting detector‐CT (PCD‐CT) using a single data acquisition"
collection: publication
permalink: /publication/2024-SingleNPS-4
authorship: 'first'
excerpt: 'This paper opens the door to patient-specific CT image quality assessment by harnessing the power of PCD-CT data acquisition. Traditionally, multiple repeated scans on a surrogate phantom has to be conducted to rigorously measure the noise power spectrum (NPS). This is strictly prohibited on the patient. However, with the merging PCD-CT technology, patient-specific noise power spectrum can be measured with single CT data acquisition under the proposed new paradigm. Its proceeding paper received Robert F. Wagner All-Conference Best Student Paper Award (Runner-up) at SPIE 2023.'
date: 2024-5-4
venue: 'Medical physics'
paperurl: 'http://mp-czhang.github.io/files/NPS1.pdf'
citation: 'Zhang, Chengzhu, et al. "Experimental measurement of local noise power spectrum (NPS) in photon counting detector‐CT (PCD‐CT) using a single data acquisition." Medical physics (2024).'
---

## Background
Accurate noise power spectra (NPS) measurement in clinical X-ray CT exams is challenging due to the need for repeated scans, which expose patients to high radiation risks. A reliable method for single CT acquisition NPS estimation is thus highly desirable.

Purpose
To develop a method for estimating local NPS from a single photon counting detector-CT (PCD-CT) acquisition.

## Methods
A novel nearly statistical bias-free estimator was constructed from the raw counts data of PCD-CT scan to estimate the variance of sinogram projection data. An analytical algorithm is employed to reconstruct point-wise covariance between any two image pixel/voxel locations xi and xj. A Fourier transform is applied to obtain the desired point-wise NPS for any chosen location xi. The method was validated using experimental data acquired from a benchtop PCD-CT system with various physical phantoms, and the results were compared with the conventional local NPS measurement method using repeated scans and statistical ensemble averaging.

## Results
The experimental results demonstrate that (1) the proposed method can achieve pointwise/local NPS measurement for a region of interest (ROI) located at any chosen position, accurately characterizing the NPS with spatial structures resulting from image content heterogeneity; (2) the local NPS measured using the proposed method show a higher precision in the measured NPS compared to the conventional measurement method; (3) spatial averaging of the local NPS yields the conventional NPS for a given local ROI.

## Conclusion
A new method was developed to enable local NPS from a single PCD-CT acquisition.