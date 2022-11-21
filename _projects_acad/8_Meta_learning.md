---
title: "Few-shot learning using MAML and Protonets"
collection: projects_acad
type: "Meta-learning, MAML, Prototype learning"
permalink: /projects_acad/8_Meta_learning
venue: "E9-333, ADRL, IISc"
date: 2022-11-21
location: None
---

What happens when you have a huge number of classes and a few data points for each class (like [omniglot](https://www.kaggle.com/datasets/watesoyan/omniglot) )? You need few-shot/meta-learning where you learn initializations of weights using tasks. This is done for N classes having k examples each. The model must do well with a small k for any combination of N classes (potentially new) (and a support set).
 
In this project I implemented MAML and Prototype Learning (2 popularly used few-shot learning algorithms).

**Note:** You can find the implementation [here](https://github.com/mainak-biswas1999/Academic_Projects/tree/main/Meta_learning).   