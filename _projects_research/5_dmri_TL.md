---
title: "Predicting brain age with Supervised Domain Adaptation"
collection: projects_research
type: "Transfer Learning, Domain Adaptation, Brain age prediction"
permalink: /projects_research/5_dmri_TL
venue: "Cognition Lab, IISc"
date: 2024-01-02
location: "Ongoing"
---

Increasing life expectancy and global median age make the population more susceptible to age-related neurological and cognitive disorders like mild cognitive impairments (MCI) and Alzheimer’s disease (AD). These disorders are known to greatly degrade the quality of life. Hence, detecting an early onset of these diseases becomes critical for the timely prognosis.

In this work, we predicted brain-age using diffusion Magnetic Resonance Imaging (dMRI) followed by computational tractography to identify anatomical connections, in vivo, that predict brain-age. The analyses were performed with the data from the TATA longitudinal Study for aging (TLSA) - an Indian cohort of elderly adults (n=192, age-range = 46-86 years, 83 females). We showed that supervised and self-supervised machine learning algorithms could decode brain age from the. 

Although we could decode brain age from dMRI scans, we suspect that lack of data (only 192 scans) and low-resolution scans prevent the data-hungry deep learning models from reaching their potential. Hence, we tried to address the problem of data scarcity by leveraging higher-resolution dMRI scans from the Rush Alzheimer’s Disease Centre (RADC) dataset (n=725, age-range = 58-102 years, 575 females). But, feature distribution shifts and different age ranges in RADC and TLSA datasets make it a non-trivial problem to combine the datasets. Hence, we developed customized supervised domain adaptation techniques to tackle these problems and use the out-of-distribution data. We found that using more data, facilitated by the customized algorithms, improved the performance of the models on both datasets significantly.

**Domain Adversarial Neural Networks:** We customised DANN model for supervised domain adaptation. We used supervised domain adaptation as the label set for source and target are unequal. Furthermore, it helpedus leverage label information in a small dataset.

**Importance Weighting:** Other than adversarial techniques, we customized importance weighting models for supervised DA. Finally, we combine IW and DANN to make a generalized Supervised Domain adaptation model. These models improve predictions on both source and target.

**Vapnik's Method: Contradistinguisher:** For DA models without a discriminator, we tested the Contradistinguisher model. We modified the algorithm for working with regression objective and supervised DA.  

**Saliency maps:** We investigated how aging affects the brain's structural connectivity, such as the decrease in the number of connections in the brain and the hemispheric asymmetries associated with the aging brain.

Please follow my [github page](https://www.github.com/mainak-biswas1999) for significant updates about the project.
