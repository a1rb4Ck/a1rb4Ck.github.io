---
layout: single
title: "thermo2geo - geometry from thermography in injection molding"
date: 2018-02-22
tags: phd
header:
  teaser: "/assets/img/thermo2geo - UNet architecture.jpg"
---

I presented a work on the use of thermography to infere the final geometry of an injection molding plastic part at the [IEEE ICIT2018](https://ieeexplore.ieee.org/xpl/conhome/8342303/proceeding) conference, in Lyon, France.  
I used the [pix2pix](https://phillipi.github.io/pix2pix/) GAN to model the relation between thermography and the heights map.  
The UNet autoencoder architecture was used.

{% include figure image_path="/assets/img/thermo2geo - UNet architecture.jpg" alt="UNet autoencoder architecture" caption="UNet autoencoder architecture" %}

### Model training

This architecture is robust, but a bit heavy to train.
Also training requires fine hyperparameters tuning because achieving convergence is hard.

{% include figure image_path="/assets/img/thermo2geo - plot.png" alt="The noisy loss evolution during training" caption="Noisy loss evolution during training" %}

You can see the network learning the translation between thermography and geometry:

<div class="responsive-video-container">
    <video width="100%" alt="" controls>
      <source src="/assets/img/thermo2geo - training_video.mp4" type="video/mp4">
    </video>
</div>
<figcaption>Learning thermography to geometry translation</figcaption>

### Evaluation the geometric reconstruction

Then with [Thomas Lacombe](https://scholar.google.com/citations?user=SIP-RuQAAAA), we evaluated the geometric recontruction accuracy using a discrete modal decomposition.
Results are impressive and valid the method.

{% include figure image_path="/assets/img/thermo2geo - geometric modal spectrum.jpg" alt="Modal spectrum comparison to validated the geometric reconstruction" caption="Modal spectrum comparison to validated the geometric reconstruction" %}

The next step will be to explore the latent space of the auto-encoder.
Also, with some optimization, inference could be run on the production line, which could help for quality control of complex geometries.
