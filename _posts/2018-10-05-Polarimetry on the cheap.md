---
layout: single
title: "Polarimetry on the cheap"
date: 2018-10-05
tags: phd
header:
  teaser: "/assets/img/camera-fusion - degree of polarimetry.jpg"
---

This summer, I designed an ultra low cost polarimeter, using three stacked webcams with three linear polarizers at 0°, 45°, 90°.  

{% include figure image_path="/assets/img/camera-fusion - polarimetry.jpg" alt="Low cost polarimeter with 3 stacked webcams" caption="Low cost polarimeter with 3 stacked webcams" %}

To compensate the parallax, homographic correction are done with OpenCV.
A reference plane is definite with a ChAruco board prior to captures.

This work was done to find if polarimetry is useful for plastic defect detection, and quality control.

{% include figure image_path="/assets/img/camera-fusion - degree of polarimetry.jpg" alt="Degree of polarimetry in false color" caption="Degree of polarimetry in false color" %}

The python library [camera-fusion](https://github.com/a1rb4Ck/camera-fusion) is on GitHub, and I must finalize and clean it (sorry quite busy now).  

{% include figure image_path="/assets/img/camera-fusion - polarimetry - StokesIQU.jpg" alt="Stokers parameters I, Q and U" caption="Stokers parameters I, Q and U" %}
