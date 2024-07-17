---
title: "High pitch helical CT reconstruction"
collection: publication
permalink: /publication/2021-HighPitch-3
authorship: 'coauthor'
excerpt: 'High-pitch helical CT is a difficult problem consisting of two types of imaging tasks: limited-view reconstruction and sparse-view reconstruction. The reconstruction framework of DL-PICCS developed in my [first-authored paper](publication/2021-DL-PICCS-1.pdf) was used to tackle this problem.'
date: 2021-5-24
venue: 'IEEE Transactions on Medical Imaging'
paperurl: 'http://mp-czhang.github.io/files/highpitch.pdf'
citation: 'Hayes, John W., et al. "High pitch helical CT reconstruction." IEEE Transactions on Medical Imaging 40.11 (2021): 3077-3088.'
keywords: ['High-pitch helical CT', 'Prior knowledge constrained deep learning']
---

## Abstract
To avoid severe limited-view artifacts in reconstructed CT images, current multi-row detector CT (MDCT) scanners with a single x-ray source-detector assembly need to limit table translation speeds such that the pitch p (viz., normalized table translation distance per gantry rotation) is lower than 1.5. When p>1.5 , it remains an open question whether one can reconstruct clinically useful helical CT images without severe artifacts. In this work, we show that a synergistic use of advanced techniques in conventional helical filtered backprojection, compressed sensing, and more recent deep learning methods can be properly integrated to enable accurate reconstruction up to p=4 without significant artifacts for single source MDCT scans.