---
title: "Predicting brain age with diffusion models"
collection: projects_research
type: "Generative Modeling, Brain age prediction"
permalink: /projects_research/4_dmri_diffMRI
venue: "Cognition Lab, IISc"
date: 2023-02-02
location: "Ongoing"
---

Diffusion Magnetic Resonance Imaging (dMRI) helps find the structural connectivity of the brain in the form of an undirected graph. Therefore, these graphs can be used as markers for brain age. But data scarcity makes it challenging for naïve deep-learning algorithms to succeed at this problem. Even larger datasets, like – Rush Alzheimer's Disease Center (RADC) have around 750 scans. Therefore, data augmentation is one of the most viable solutions to this problem.
The recent success of conditional stable (latent) diffusion models is not limited to just generating realistic natural images based on an input text (DALLE-2). They have been used successfully for stimulus reconstruction conditioned on the input fMRI activity. We propose the use of latent diffusion models for the generation of connectivity matrices conditioned on age. A realistic augmentation of the training set can reduce overfitting and help build a robust brain-age decoder from connectivity matrices.


**MLP based latent diffusion model:** We built a conditional diffusional model just using MLPs and adversarial VAEs to model distributions over graphs. It was able to generate connectivity matrices when trained on few hundred samples only.

**Conditional generation quality:** Conditioned on age the diffusion model was able to produce a generation quality of r=0.8 with the conditioned age. 

**Augmentation results:** Augmentation partially improved performance of regressors trained on connectivity matrices to predict age.

**Saliency maps:** We are looking at the saliency maps of the connections relevant for prediction. There are some results - like important brain nodes that change with age in the central/frontal region. We are investigating the finding. 

Please follow my [github page](https://www.github.com/mainak-biswas1999) for significant updates about the project.
