---
title: "Domain Adversarial Neural Networks"
collection: projects_acad
type: "Domaian Adaptation, DANN"
permalink: /projects_acad/7_Domain_Adaptation
venue: "E9-333, ADRL, IISc"
date: 2022-11-01
location: None
---

All machine learning algorithm assumes that the train and test data comes from the same distribution. For example, when we train a classifier on handwritten digits of the USPS dataset, it performs much poorer on the MNIST dataset. In DANN, this is solved adversarially by using the a discriminator network (identifies data from source and target domain) that forces the feature extractor to produce similar features for both the domains.    

**Note:** The DANN doesn't see the labels of the target data. Yet it increases the cross-generalization (adaptation to the target data) performance by 30%. Find the code [here](https://github.com/mainak-biswas1999/Academic_Projects/tree/main/DANN).   