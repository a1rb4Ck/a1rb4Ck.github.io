---
layout: single
title: "I am not going to Montreal"
date: 2019-06-15
tags: phd
header:
  teaser: "/assets/img/QUALITA2019 - saliency guided backprop.png"
gallery:
  - url: "/assets/img/QUALITA2019 - part OK.jpg"
    image_path: "/assets/img/QUALITA2019 - part OK.jpg"
    alt: "Good part"
    title: "Good part"
  - url: "/assets/img/QUALITA2019 - part NOK.jpg"
    image_path: "/assets/img/QUALITA2019 - part NOK.jpg"
    alt: "Defective part"
    title: "Defective part"
---

I am not presenting my work at the CIGI-QUALITA 2019 conference, in Montreal.
This is because of a really soon to come newborn.
The associate paper can be found [here](https://hal.archives-ouvertes.fr/hal-02142331).
This paper is a teaser of my onwriting PhD.
I show that a simple webcam can be use with Deep Learning to detect complex defect patterns on injection molded parts.

{% include gallery caption="Example of a good and a defective part, captured just after molding with a simple webcam" %}

The software architecture is a REST API endpoint, with an GPU powered inference server and a client system which integrates hardware sensors.
When the production line start, I have zero training data.
Then it grows slowly, as the human expert annotate some parts.
This is why transfer learning is necessary.
I tried many different architecture, and the most robust one is [VGG16](https://arxiv.org/abs/1409.1556).

{% include figure image_path="/assets/img/QUALITA2019 - transfer.jpg" alt="Transfer learning architecture with VGG16" caption="Transfer learning for quality control with VGG16" %}

The embedded system runs on a low power ARM.
It is responsible for the robust part detection.
Fusion of multiple sensors was needed for a robust detection: sonar, Time Of Flight and camera frame analysis.

{% include figure image_path="/assets/img/QUALITA2019 - part detection.png
" alt="Two captured images with robust part detection and without: the later captured the suction cup which hold the part" caption="Necessity of robust part detection" %}

Finally, I designed a simple Flask UI, so the user can train the Deep Learning model as the production line goes.
Every ten new annotate parts, the neural netorks model is re-trained.

{% include figure image_path="/assets/img/QUALITA2019 - Deep Quality Control UI.jpg" alt="Deep Quality Control User Interface " caption="Deep Quality Control User Interface" %}

To explain the view of the neural networks, [guided backpropagation](https://arxiv.org/abs/1412.6806) is used.
The saliency image shows that the model is sensible to the part geometry and to defects.

{% include figure image_path="/assets/img/QUALITA2019 - saliency guided backprop.png" alt="Saliency image of the model sensibilities" caption="Model explained: [guided backpropagation](https://arxiv.org/abs/1412.6806) saliency image" %}


I am actually doing industrial scale trials of the system at [IPC Technical Center](https://ct-ipc.com/) and [Plastic Omnium](https://www.plasticomnium.com/en/).
