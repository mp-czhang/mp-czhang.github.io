---
title: "Reconstruction of three‐dimensional tomographic patient models for radiation dose modulation in CT from two scout views using deep learning"
collection: publication
permalink: /publication/2022-ScoutCT-Net-2
authorship: 'first'
excerpt: 'ScoutCT-Net CT is a very cool deep learning model my colleage Juan and I developed. It was intended for reconstruction of 3D volumetric image with soft-tissue contrast from only two orthogonal views. It is the pioneer work in this category that even predated the famous [single-view](https://www.nature.com/articles/s41551-019-0466-4) paper. It is a powerful tool and can be applied to both diagnostic and radiation therapy settings. In ths published paper, we demonstrated its powerful generative potential to convert orthorgonal scout views to 3D CT. The results were quantitatively analyzed in the clinical endpoint of fluence modulation and dose verification.'
date: 2021-12-15
venue: 'Medical physics'
paperurl: 'http://mp-czhang.github.io/files/ScoutNet.pdf'
citation: 'Montoya, Juan C., et al. "Reconstruction of three‐dimensional tomographic patient models for radiation dose modulation in CT from two scout views using deep learning." Medical physics 49.2 (2022): 901-916.'
keywords: ['Two-view volumetric reconstruction', 'Fluence modulation']
---

## Background
A tomographic patient model is essential for radiation dose modulation in x-ray computed tomography (CT). Currently, two-view scout images (also known as topograms) are used to estimate patient models with relatively uniform attenuation coefficients. These patient models do not account for the detailed anatomical variations of human subjects, and thus, may limit the accuracy of intraview or organ-specific dose modulations in emerging CT technologies.

## Purpose
The purpose of this work was to show that 3D tomographic patient models can be generated from two-view scout images using deep learning strategies, and the reconstructed 3D patient models indeed enable accurate prescriptions of fluence-field modulated or organ-specific dose delivery in the subsequent CT scans.

## Methods
CT images and the corresponding two-view scout images were retrospectively collected from 4214 individual CT exams. The collected data were curated for the training of a deep neural network architecture termed ScoutCT-NET to generate 3D tomographic attenuation models from two-view scout images. The trained network was validated using a cohort of 55 136 images from 212 individual patients. To evaluate the accuracy of the reconstructed 3D patient models, radiation delivery plans were generated using ScoutCT-NET 3D patient models and compared with plans prescribed based on true CT images (gold standard) for both fluence-field-modulated CT and organ-specific CT. Radiation dose distributions were estimated using Monte Carlo simulations and were quantitatively evaluated using the Gamma analysis method. Modulated dose profiles were compared against state-of-the-art tube current modulation schemes. Impacts of ScoutCT-NET patient model-based dose modulation schemes on universal-purpose CT acquisitions and organ-specific acquisitions were also compared in terms of overall image appearance, noise magnitude, and noise uniformity.

## Results
The results demonstrate that (1) The end-to-end trained ScoutCT-NET can be used to generate 3D patient attenuation models and demonstrate empirical generalizability. (2) The 3D patient models can be used to accurately estimate the spatial distribution of radiation dose delivered by standard helical CTs prior to the actual CT acquisition; compared to the gold-standard dose distribution, 95.0% of the voxels in the ScoutCT-NET based dose maps have acceptable gamma values for 5 mm distance-to-agreement and 10% dose difference. (3) The 3D patient models also enabled accurate prescription of fluence-field modulated CT to generate a more uniform noise distribution across the patient body compared to tube current-modulated CT. (4) ScoutCT-NET 3D patient models enabled accurate prescription of organ-specific CT to boost image quality for a given body region-of-interest under a given radiation dose constraint.

## Conclusion
3D tomographic attenuation models generated by ScoutCT-NET from two-view scout images can be used to prescribe fluence-field-modulated or organ-specific CT scans with high accuracy for the overall objective of radiation dose reduction or image quality improvement for a given imaging task.