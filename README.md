# HACKATHON ISAE SUPAERO
## EELS Image Inpainting

This is the repository for *team 14 (AKA Les Restaurateurs)* of the ISAE-Supaero *Hackathon* (March 2020).

The aim of the project is to use the *Deep Image Prior* explained in [deep image prior method](https://dmitryulyanov.github.io/deep_image_prior) to carry out *inpainting on EELS images*. 

The results obtained have been compared with those obtained by the rapid methods of [paper](https://arxiv.org/abs/2002.01225).

## Example

Reconstruction on a 20% real SCAM (HR-sample) returns the result.

Spectral dimension           |  Spatial dimension
:-------------------------:|:-------------------------:
<img src="img/spectre_key4.jpeg" height="250">  |  <img src="img/moqueta_key4.jpeg" height="250">

Similarly, image reconstructions can be launched with the main notebook on any multispectral image, the neural network architecture being optimised for EELS images
