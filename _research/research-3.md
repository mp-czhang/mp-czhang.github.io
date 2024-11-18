---
title: "Research Interest (III): Patinet-specific quantitative image quality assessment"
excerpt: ""
collection: research
---

The third fundamental contribution I made is to address a clnical problem how to reconstruct the noise power spectrum from clinical patient projection data directly. As it is well documented in standard imaging science and statistics textbooks, one will need to repeatedly acquire data from the image object to calculate the sample standard deviation. Then the noise power spectrum can be estimated. This method works fine for phantom studies but does not provide the much-desired noise power spectrum for patient data, where one can only acquire data once due to the apparent ethical and regulatory constraints.

To overcome this limitation, I developed a brand-new method to reconstruct the noise power spectrum directly from patient data. The critical observation is that, for a given image voxel, there is one ray from each data acquisition view angle passing through the voxel. These rays are used in the image reconstruction process, but one can also use the same amount of rays to reconstruct the corresponding noise variance of the image voxels. it has been skipped from the statistical and imaging physics society in the past fifty years of x-ray CT imaging history. 

This discovery lets us directly predict how well radiologists can correctly identify a given lesion. We can use this discovery to guide the delivery of x-rays in CT as in intensity-modulated radiotherapy (IMRT) to maximize the diagnostic performance for a given imaging task.