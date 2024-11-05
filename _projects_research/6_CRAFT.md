---
title: "CRAFT: A framework for Deep transfer and semi-sup. learning"
collection: projects_research
type: "Transfer Learning, semi-supervised learning"
permalink: /projects_research/6_CRAFT
venue: "Cognition Lab, IISc"
date: 2024-06-06
location: "Ongoing"
---

State-of-the-art deep learning models are seldom as efficient in neuroscience as in domains with access to big data. A major reason is the rarity of large labeled datasets. Hence, the role of pre-trained models (transfer learning) and unlabeled data (semi-supervised learning) is important. We propose Contradistinguisher Regularized Adaptive FineTuning (CRAFT) of neural networks -- a method for efficient transfer and semi-supervised learning. 

First, we derive a model agnostic maximum-a-posteriori (MAP) objective, with a prior on the model parameters inspired from the study -- Contradistinguisher. This prior leverages high-level statistics of the target data, like the distribution of labels. As the contradistinguisher objective was developed for classification tasks only, one of the contributions of this study is extending it to continuous label prediction problems. We discuss the effectiveness of this framework using two critical tasks in neuroscience -- saccade amplitude prediction from electroencephalogram (EEG), and brain age prediction using structural Magnetic Resonance Imaging (sMRI). Combining a novel EEGNet-based LSTM model with CRAFT significantly outperforms the saccade benchmark, achieving $> 15 \%$ improvement in root mean square error (RMSE). We also observe a considerable boost in performance for the brain age problem. Finally, we demonstrate that CRAFT can effectively utilize unlabeled data in a semi-supervised manner. On the saccade prediction task, CRAFT outperforms supervised learning models and achieves a $15-20\%$ lower RMSE, especially when unlabeled data heavily outnumbers labeled data.

Please follow my [github page](https://www.github.com/mainak-biswas1999) for significant updates about the project.
