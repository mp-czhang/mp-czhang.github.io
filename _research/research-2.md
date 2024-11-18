---
title: "Research Interest (II): Interior Problem"
excerpt: ""
collection: research
---

I developed a new deep learning-based framework to solving the so-called interior tomographic reconstruction problem. This problem has been known notoriously difficult and mathematicians have worked on years to find its solution. 

### Impact on diagnostic imaging
Specifically, blooming artifacts appear at the periphery of the image and contaminate the whole ROI image if the truncation of CT data is severe. To address the data truncation problem, I proposed to combine the human wisdom and machine intelligence. 

To address this problem, I mathematically proved that the acquired truncated projection data can be back-projected using a weighted backprojection scheme to transform the projection data into a beautiful feature space with a remarkable property: This feature space is a blurred version of the target with a shift-invariant blurring kernel. This remarkable feature immediately enables one to design a deep learning-based de-blurring algorithm to reconstruct the image from the feature space. Due to the intrinsic shift-invariance in feature space, one trained deep-learning architecture can reconstruct all the interior tomographic data regardless location and size of the target volume. 

### Impact on radiation therapy
To put this problem in the image-guided radiation therapy and image-guided intervention context, we all know that the treatment beam is collimated to be maximally conformal with the clinical target volume. A portal imager can also collect the x-ray projection information after the treatment beam goes through the target. However, due to the truncation of data the beam does not cover the anatomy beyond the collimated treatment target, one cannot accurately use the acquired information to reconstruct the tumor volume from the portal imager data due to the severely ill-posedness of the reconstruction problem. 

further clinical applications of this breakthrough discovery in dose verifications using portal imager data. 