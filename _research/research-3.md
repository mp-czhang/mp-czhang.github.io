---
title: "Research Interest (III): Patinet-specific quantitative image quality assessment"
excerpt: ""
collection: research
---



I challenged the textbook method of quantitative image quality assessment and the dogma of ICRU87. I solved an important clnical problem which is to reconstruct the noise power spectrum from clinical patient projection data directly. As it is well documented in standard imaging science and statistics textbooks, one will need to repeatedly acquire data from the image object to calculate the sample standard deviation. Then the noise power spectrum can be estimated. This method works fine for phantom studies but does not provide the much-desired noise power spectrum for patient data, where one can only acquire data once due to the apparent ethical and regulatory constraints.

To overcome this limitation, I developed a brand-new method to reconstruct the noise power spectrum directly from patient data. The critical observation is that, for a given image voxel, there is one ray from each data acquisition view angle passing through the voxel. These rays are used in the image reconstruction process, but one can also use the same amount of rays to reconstruct the corresponding noise variance and covariance of the image voxels. it has been skipped from the statistical and imaging physics society in the past fifty years of x-ray CT imaging history. 

This discovery lets us directly predict how well radiologists can correctly identify a given lesion. We can use this discovery to guide the delivery of x-rays in CT as in intensity-modulated radiotherapy (IMRT) to maximize the diagnostic performance for a given imaging task.

### Reference
[1] [Zhang, Chengzhu, et al. "Experimental measurement of local noise power spectrum (NPS) in photon counting detector‐CT (PCD‐CT) using a single data acquisition." Medical physics (2024).](/publication/2024-SingleNPS-4.md)

[2] [Zhang, Chengzhu, et al. "Noise power spectrum (NPS) in computed tomography: Enabling local NPS measurement without stationarity and ergodicity assumptions." Medical physics (2024).](/publication/2024-LocalNPS-5.md)