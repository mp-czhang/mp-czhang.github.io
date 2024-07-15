---
title: "Deep-Interior: A new pathway to interior tomographic image reconstruction via a weighted backprojection and deep learning"
collection: publication
permalink: /publication/2023-Deep-Interior-3
authorship: 'first'
excerpt: 'This paper is one of the highlights in my PhD career. Interior problem is a notoriously difficult problem in the history of CT reconstruction. Mathematicians and medical physicists have established rigorous theoretical frameworks to solve the interior problem. Among them, the fully truncated CT data reconstruction is a whole another level. With rapid devleopment of AI enabled reconstruction, we intensly derived a unique feature space called the backprojection space for the deep neural network to learn the necessary deconvolution scheme to reconstruction ROI as small as 5 cm in diameter regardless of its position.'
date: 2023-12-8
venue: 'Medical physics'
paperurl: 'http://mp-czhang.github.io/files/deepinterior.pdf'
citation: 'Zhang, Chengzhu, and Guang‐Hong Chen. "Deep‐Interior: A new pathway to interior tomographic image reconstruction via a weighted backprojection and deep learning." Medical physics 51.2 (2024): 946-963.'
keywords: ['Interior Problem', 'Backprojection filtering for divergent beam geometry']
---

## ackground
In recent years, deep learning strategies have been combined with either the filtered backprojection or iterative methods or the direct projection-to-image by deep learning only to reconstruct images. Some of these methods can be applied to address the interior reconstruction problems for centered regions of interest (ROIs) with fixed sizes. Developing a method to enable interior tomography with arbitrarily located ROIs with nearly arbitrary ROI sizes inside a scanning field of view (FOV) remains an open question.

## Purpose
To develop a new pathway to enable interior tomographic reconstruction for arbitrarily located ROIs with arbitrary sizes using a single trained deep neural network model.

## Methods
The method consists of two steps. First, an analytical weighted backprojection reconstruction algorithm was developed to perform domain transform from divergent fan-beam projection data to an intermediate image feature space, B(x), for an arbitrary size ROI at an arbitrary location inside the FOV. Second, a supervised learning technique was developed to train a deep neural network architecture to perform deconvolution to obtain the true image f(x) from the new feature space B(x). This two-step method is referred to as Deep-Interior for convenience. Both numerical simulations and experimental studies were performed to validate the proposed Deep-Interior method.

## Results
The results showed that ROIs as small as a diameter of 5 cm could be accurately reconstructed (similarity index 0.985 ± 0.018 on internal testing data and 0.940 ± 0.025 on external testing data) at arbitrary locations within an imaging object covering a wide variety of anatomical structures of different body parts. Besides, ROIs of arbitrary size can be reconstructed by stitching small ROIs without additional training.

## Conclusion
The developed Deep-Interior framework can enable interior tomographic reconstruction from divergent fan-beam projections for short-scan and super-short-scan acquisitions for small ROIs (with a diameter larger than 5 cm) at an arbitrary location inside the scanning FOV with high quantitative reconstruction accuracy.