---
layout: single
title: "Polarimetric imaging for quality control in injection molding"
date: 2019-05-15
tags: phd
header:
  teaser: "/assets/img/QCAV2019_polarimetry - specular.jpg"
gallery:
  - url: "/assets/img/QUALITA2019 - part OK.jpg"
    image_path: "/assets/img/QCAV2019_polarimetry - diffuse.jpg"
    alt: "Diffuse reflections from a plastic molded part"
    title: "Image of the diffuse reflections from a plastic molded part"
  - url: "/assets/img/QUALITA2019 - part NOK.jpg"
    image_path: "/assets/img/QCAV2019_polarimetry - specular.jpg"
    alt: "Image of the specular reflections from a plastic molded part"
    title: "Specular reflections from a plastic molded part"
---

I presented a work on the use of polarimetry for injection molding quality control at the [SPIE QCAV2019](https://www.qcav2019.uha.fr/) conference, in Mulhouse, France.
The associate paper can be found [here](https://hal.archives-ouvertes.fr/hal-02142317).
The venue was great, fitted my research, with rich talks and offline discussions.  

I met other PhD students which were using non-conventional imaging for original purposes, and also private startup researchers on quality control with deep learning.

This work use the low cost polarimeter I built [last summer](/Polarimetry-on-the-cheap).
It is possible to acquire degree and angle of polarimetry with a 1080p resolution.

{% include figure image_path="/assets/img/camera-fusion - degree of polarimetry.jpg" alt="Degree of polarimetry in false color" caption="Degree of polarimetry in false color" %}

It is also possible to reconstruct the first three Stokes parameters from the linear polarization of light.
Then, it is possible to separate diffuse from specular reflections.

{% include gallery caption="Diffuse and specular reflections from a plastic molded part" %}

To find if polarimetry helps to detect defects, I propose the use of a machine learning pipeline for binary classification: part is ok or defective.
The training dataset have a hundred part, which is small in comparison with litterature standards.

I propose a dataset with the same part captured with three different capture modalities.
With or without linearly polarized light and with or without polarized camera.
The objective is to find which modality gives the best defect classification score.

{% include figure image_path="/assets/img/QCAV2019_polarimetry - stats.jpg" alt="Table of the dataset with three different capture modalities: with or without polarized light and with or without polarimetry" caption="Dataset: three different capture modalities: with or without polarized light and with or without polarimetry" %}

To avoid machine learning pipeline bias, for each case, I found the best pipeline using genetic optimization with the [TPOT](https://epistasislab.github.io/tpot/) library.

| Camera polarized filter angle | Light polarized | Light not polarized | Benchmark without light nor polarized cameras |
| ---------------------------:| -----:| -----:| ---------:|
| All 3 cameras with 3 angles | 0.876 | 0.876 | **0.948** |
|         0° polarized camera | 0.820 | 0.875 | **0.923** |
|        45° polarized camera | 0.820 | 0.769 |     0.820 |
|        90° polarized camera | 0.846 | 0.820 |     0.889 |

<figcaption>TPOT classification scores</figcaption>


Results are promising, but it show that polarimetry is less important that having three different viewpoints.
