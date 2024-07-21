---
title: "Investigation of beam field specific DLG"
date: 2023-9-12
excerpt: "However, we found clinical plans often benefit from a specific DLG value over a universal DLG. Based on a retrospective study of 68 beam fields, each MLC modulated beam fields were found to have different optimal DLG values. Upon our investigation, we immediately implemented two DLG values for clinical use. As a straightforward triage, all SBRT/SRS fields will use a 'high-modulation' DLG with lower value than the clinical beam. Out of 40 initially failed clinical beams, all of them passed QA after the use of this new DLG. Please click [here](/files/Poster_DLG.pdf) to see our clinical findings."
collection: clinical
---

## Overview
However, we found clinical plans often benefit from a specific DLG value over a universal DLG. Based on a retrospective study of 68 beam fields, each MLC modulated beam fields were found to have different optimal DLG values. Upon our investigation, we immediately implemented two DLG values for clinical use. As a straightforward triage, all SBRT/SRS fields will use a 'high-modulation' DLG with lower value than the clinical beam. Out of 40 initially failed clinical beams, all of them passed QA after the use of this new DLG. Please click [here](/files/Poster_DLG.pdf) to see our clinical findings.

## Purpose 
The dosimetric leaf gap (DLG) concept is introduced to Eclipse treatment planning system to account for the radiation dose transmitted through the round-shaped MLC leaf tips, by pulling back a set distance between each pair of opposing leaves. A set of DLG values is usually determined with physical measurements and universally affects all plans. However, certain plans suffered from worse patient specific QA results, which usually could be improved with a different DLG value. In this work, we propose using beam field specific DLG to reduce discrepancy between portal dosimetry prediction and measurement for VMAT plans.

## Methods
68 beam fields were retrospectively selected from 28 clinical plans that originally failed patient-specific QA using portal dosimetry. The predicted portal dose was re-calculated using the same leaf sequence and same MU but with nine different DLG values varying from zero to eight times of the measured DLG. The originally measured portal imaging, considered as a reliable reference given 1% daily output drift, was compared to the predicted dose for all DLG values using the gamma analysis. The optimal DLG value was determined for each field by the highest gamma passing rate (GPR) with the same 2mm/2% criteria. The relationship between the common beam complexity metrics such as the edge metric (EM) and modulation complexity score (MCS) versus the optimal DLG value was also investigated.

## Results
The results from the included 68 beams demonstrate there is no set optimal DLG that can be applied to all beam fields and plans. The optimal DLG values spanned across all nine levels of DLG. It is also shown there is no obvious connection associated between the optimal DLG values and the beam complexity metrics which correlate well with GPR.
Conclusion: Compared to the universal model, a beam specific DLG value results in better agreement between the prediction and measurement in patient specific QA and should be clinically implemented for accurate dose calculation.

## Conclusion 
Compared to the universal model, a beam specific DLG value results in better agreement between the prediction and measurement in patient specific QA and should be clinically implemented for accurate dose calculation.