---
title: "Diffusion  Models, Conditional Diffusion Models"
collection: projects_acad
type: "Generative Models, Deep Representation Learning"
permalink: /projects/projects_acad/6_Duffusion_Models
venue: "E9-333, ADRL, IISc"
date: 2022-10-01
location: None
---

Diffusion Models take data from a distribution, gradually adds gaussian noise, until a map to an isotropic gaussian is obtained. For small mixing parameters, the reverse process is also Markov. This assumption helps us come up with a model that can leran the backward process, i.e., given isotropic gaussian noise, it can run steps of langevin dynamics (backward/also known as denoising) to generate images from the train distribution.

You can find the code [here](https://github.com/mainak-biswas1999/Academic_Projects/tree/main/Diffusion%20Model).