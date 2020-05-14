---
layout: single
title: "Academic fundraising"
date: 2019-04-11
tags: phd theeye
header:
  teaser: "/assets/img/TheEye - invest.png"
---

I plan to defend my thesis in september.
What's next?  

My research is on the application of Deep Learning for industrial Quality Control.
This qualifie as applied reasearch. So I found it needs a prototype, to prove that it works, in situ.
I need to build a quality control system, from sensor hardware to software, then integrate it on a production line, and validate the performance, that it detects defects in realtime.

Software will be Python Deep Learning (PyTorch/Tensorflow).
Hardware will.. wait, this have to be purchased.
I spent some of my small PhD saving on webcams, lighting, and the new Jetson Nano.
This is not enough to built an industrial grade demo.

So I try to get academic fund.
I made the TheEye project.
I spent many nights writting fundraising files on french grants (like many professors).
Many were constrained to specific research topics.  
I got a positive answer from Linksium.
Linksium is a french SATT (Technology Transfer Accelerator Society).
It's a private society backed with public funds from the old public bank _Caisse des dépôts et consignations_.

{% include figure image_path="/assets/img/TheEye - invest.png" alt="Slide of TheEye project review at Linksium" caption="TheEye project preview at Linksium" %}

## What is TheEye?

It is quality control of every part on the production line.

### From batch control to unit test

Human quality control has a duraction and a cost that is not on par with industrial requirements.
Thus, batch control is used.
There is a risk to send a defective part to the customer.
This can be costly, as the customer send back the full order and you have to sort the bad part.
The common accepted defect rate in injection molding is about 5 parts per millions.

TheEye achives per part quality control, thus reducing this risk to its per part false control rate, not the full batch anymore.
Also, TheEye generate a quality control report per part.

### Ecologically recycling just-molded plastic parts

Currently, most defective parts are find hours or days after molding.
Sometimes, they are found after many post-processing, like painting.

With TheEye, when a defective part is detected just after production, it can be removed from the production line.
Then, a specific recycling pipeline can be designed.

### Avoid defective part production 

Also, when many defective parts are detected, the production line can be stopped, or a technician can be notified.
This avoids to run a production line for hours just to mold bad parts.
And this is a more common practice than you can think.

### Quality control is boring

Humans have a low repeatability and reproducibility.
We are not robot.
Let's the robot do those kind of jobs; they like it, and they are better than us.

Moreover, Humans are better at other intellectual things that looking at plastic part 8 hours a day.
Today, technicians on the production line have smartphone far more powerful than the production line they run.
Strange but true.
Let's bring some intelligence and technology to the production line.


## Investor talks

Three investor talks later, I got more than 170k€, including 50k€ of hardware and 16 months postdoc salary.

{% include figure image_path="/assets/img/TheEye - next.png" alt="TheEye project planning" caption="TheEye project planning" %}

Starting september 2019, I will be a postdoc on TheEye project, with objectives:  

- build an industrial grade quality control system from sensor hardware to software and human interfaces  
- show that defect classification performances are on par with industrial requests  

This will be fun, until next PhD defense.
