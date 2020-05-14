---
layout: single
title: "TheEye defect segmentation demo"
date: 2020-05-13
tags: theeye
header:
  teaser: "/assets/img/TheEye - logo.png"
---

I have been working for six months as a postdoc on the following of my PhD, you can check [blog posts](/tags/#theeye).

Today, I finalized a webapp demo of my defect segmentation software.

You can try it [here](https://a1rb4ck.github.io/TheEye-demo/).

{% include figure image_path="/assets/img/TheEye - demo - may 2020.jpg
" alt="Demo of TheEye defect detection capabilities as a web app." caption="Demo of TheEye defect detection capabilities, as a web app." %}

It has been heavily tuned to run in your browser.
It is also available offline as a webapp.
I think this is the future of industrial softwares.

Everything is running locally on your GPU, thanks to the great [tensorflow.js](https://www.tensorflow.org/js).

Many new functionnalities should come in your browser in the following months.

## FAQ

**Q.** Is it what people are calling Artificial Intelligence?  
  R. I don't think so, as there is no self-learning nor conscientiousness.
  This is classical Deep Learning.

**Q.** How many _different_ parts do you have in your training dataset?  
  R. Four hundred now.
  It could be double if I had more time to process them. It should be done in a few weeks.

**Q.** How many parts in _total_ do you have in your training dataset?  
  R. More than a thousand.
  All came from industrial collaborations.

**Q.** How big is the neural networks model?  
  R. In your browser, it is 12.7 MB.
  It has been optimized to run on mobile, without losing much performance.

**Q.** Can it run offline? Without internet access?  
  R. Yes.
  This is a web app with caching support.
  You can also install it in Chrome.
  An Internet connection is only needed for the initial model download and 5 asset images.
  But please remember that without Internet access, model will cannot be updated to the last version.

**Q.** What is your `np.random.seed`?  
  R. `np.random.seed(42)`

**Q.** How much does it cost?  
  R. Zero. This is research from a public lab.

**Q.** Can I adjust the model on my problem?  
  R. In theory, you could use transfer learning from the initial weights.
  But as it as been heavily tuned on this specific problem, it certainly won't work.
  I have planned to propose in-browser transfer learning, in the following weeks.

**Q.** I have many big GPUs, can I use a better model?  
  R. I have designed a state-of-the-art model, with self-attention.
  But it is 600MB.
  I have planned to run in the Cloud and to give public access as a REST API.

**Q.** Is it open source?  
  R. Not for now, but it could.
  The problem is to fund research.

**Q.** What about unsupervised learning?  
  R. Yes.
