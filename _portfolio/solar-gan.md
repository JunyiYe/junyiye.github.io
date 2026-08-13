---
title: "Solar GAN"
excerpt: "High resolution solar image generation using generative adversarial networks<br/><img src='/images/solar.svg'>"
collection: portfolio
---

We applied Generative Adversarial Networks (GANs) to perform **solar image-to-image translation** ([Annals of Data Science, 2024](/publication/2024-01-01-solar-gan)) — from Solar Dynamics Observatory (SDO)/Helioseismic and Magnetic Imager (HMI) line-of-sight magnetogram images to SDO/Atmospheric Imaging Assembly (AIA) 0304-Å images. UV/EUV observations like SDO/AIA 0304-Å were only available starting in the late 1990s, even though magnetic field observations like SDO/HMI have been available since the 1970s, so leveraging GANs gives scientists access to more complete datasets for analysis.

For generating high-resolution solar images we used the Pix2PixHD and Pix2Pix algorithms, trained and tested on 2012–2014 data. Our models generate high-resolution (1024×1024 pixel) AIA0304 images from HMI magnetograms, with pixel-to-pixel Pearson Correlation Coefficients as high as 0.99 (Pix2PixHD) and 0.962 (Pix2Pix), outperforming prior work and enabling researchers to predict space weather events such as Solar Flares and Coronal Mass Ejections when direct AIA0304 data is unavailable.
