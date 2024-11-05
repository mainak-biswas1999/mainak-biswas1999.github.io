---
title: "Rescuing referral failures due to domain shift"
collection: projects_research
type: "Selective Classification, Domain Adaptation, Medical Imaging"
permalink: /projects_research/7_referral_failures
venue: "Cognition Lab, IISc"
date: 2024-05-05
location: "Ongoing"
---

Here, we address a major challenge with domain generalization – selective classification during automated medical image diagnosis. During selective classification, models must abstain from making predictions when label confidence is low, especially for samples that deviate from the training set (covariate shift). Such uncertain samples are referred to the clinician for further evaluation (“referral”). Yet, we see that even state-of-the-art deep learning models fail dramatically during referral when tested on medical images acquired from a different demographic or with different technology. 

Using a benchmark medical imaging dataset – diabetic retinopathy (DR) prediction with retinal fundus images – we show that, despite good label prediction, predictive uncertainty estimates do not generalize well under covariate shift. For example, models trained with DR images acquired in the United States exhibit catastrophic referral failures when tested with DR images collected in India. In short, we show that by using novel combination domain adaptation tools like DANN and IW with deep-learning models, we can avoid catastrophic failures during referral.

Please follow my [github page](https://www.github.com/mainak-biswas1999) for significant updates about the project.
