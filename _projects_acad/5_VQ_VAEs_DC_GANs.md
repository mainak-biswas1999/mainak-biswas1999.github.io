---
title: "VQ-VAEs, DC-GANs"
collection: projects_acad
type: "Generative Models, Vector Quantized VAEs, GANs"
permalink: /projects_acad/5_VQ_VAEs_DC_GANs
venue: "E9-333, ADRL, IISc"
date: 2022-10-01
location: None
---

VQ-VAEs and DC-GANs are widely used generative models today. Vector Quantized VAEs, intuits that every image that we see today is discrete and quantized. It comes up with the idea that it is possible to represent most signals with a combination of fixed length codebook. The output of the Encoder is thus quantized into vectors in the code-book (which are themselves learnt). The decoder is made to reconstruct the image from its quantized version.

For inference in VQ-VAEs, we need to learn a generative model on the discrete latent space of the VQ-VAE. This is the most challenging part of making VQ-VAEs work. This is because latents are not known to follow a particular bias, thus selecting an architecture as a function approximator is challenging.
For DC-GANs, both the generator and the discriminator is made up of convolutional and inverse convolutional layers only. From an uniform noise the generator is forced to generate images so that the JS divergence between the generated and the real image is minimized.

VQ-VAE code can be found [here](https://github.com/mainak-biswas1999/Academic_Projects/tree/main/VQ-VAE%20and%20DC-GAN/VQ_VAE) and the DC-GAN code can be found [here](https://github.com/mainak-biswas1999/Academic_Projects/tree/main/VQ-VAE%20and%20DC-GAN/DC_GAN). 