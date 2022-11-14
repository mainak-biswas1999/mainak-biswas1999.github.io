---
title: "Decoding Attention Signatures from EEG Data"
collection: projects_research
type: "Attention, Deep Learning"
permalink: /projects/projects_research/3_EEG_decode
venue: "Cognition Lab, IISc"
date: 2022-01-01
location: None
---

EEG data is extremely noisy, and heterogenous across humans. Variability increases further if the task design of a psychophysical changes. This project aims at answering the following:

**1. Embedding Informed NN: ** Creating Neural networks that can generalize to a wide range of task design, and huge number of human participants. It is seen that using subject and dataset embedding helps us meet this objective. These (learnable) embeddings are used to preprocess the data individually for each subject, as well as inform the model to which dataset/subject does a sample belong.

**2. Transfer Learning: ** Transfer learning from Attention and Expectation models is used to answer whether the Posner Cue is an attention/expectation cue.  

**3. Saliency Maps: ** GradCAM, and Saliency Maps were used to explain which band in the spectrogram is essential for decoding attention and Expectation. It is seen that the model is able to find the regions in the spectrogram that are induced by attention and expectation cue used in the experiment.

**4. Electrode Importance: ** It also tries to answer which group of electrodes (frontal/occipital) is more essential for decoding attention/expectation. It is seen that the frontal electrodes are more important for decoding these signatures. 

Please look at [this](https://www.github.com/mainak-biswas1999) for more details about this project.
