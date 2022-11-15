---
title: "Spoken Language Identification"
collection: projects_research
type: "SLID, Speech Signal Processing, Deep Learning"
permalink: /projects_research/2_SLID_Emotion
venue: "Jadavpur University"
date: 2020-10-01
location: None
---

This aims at identifying language from speech data. Many Indian languages have similar phonemes, which makes it challenging to separate them. This project uses MFCC features to develop diffent algorithms to tackle this problem.

[This](https://doi.org/10.1007/978-981-15-9492-2_12) contains the description using SVM classifier. This was considerably improved by using the fresh algorithm for feature extraction and selection from the MFCC timeseries. These hand-engineered features have semantic meaning associated with them, making the model explainable. These features were then used by a shallow MLP to achieve state-of-the-art performance.
This is the associated [document](https://doi.org/10.1007/s11042-021-11439-1), and the corresponding code can be found [here](https://github.com/rahamansaif/LID-using-time-series-MFCC.git).