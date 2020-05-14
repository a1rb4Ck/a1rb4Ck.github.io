---
title: Research
layout: single
author_profile: true
permalink: /research/
---

<link rel="stylesheet" href="https://cdn.rawgit.com/jpswalsh/academicons/master/css/academicons.min.css">
<div>
  <p>
    <i class="ai ai-open-access-square ai-1x"> </i>
    <a href="https://cv.archives-ouvertes.fr/pierre-nagorny"> HAL (french open archive)</a>
    <br>
    <i class="ai ai-arxiv-square ai-1x"> </i>
    <a href="https://arxiv.org/find/cs/1/au:+Nagorny_P/0/1/0/all/0/1"> arXiv</a> (use <a href="http://www.arxiv-sanity.com">arXiv-sanity</a> & <a href="https://www.arxiv-vanity.com">arxiv-vanity</a>!)
    <br>
    <i class="ai ai-google-scholar-square ai-1x"> </i>
    <a href="https://scholar.google.fr/citations?user=Hh38w7MAAAAJ&hl=en"> Google scholar</a>
    <br>
    <i class="ai ai-researchgate-square ai-1x "> </i>
    <a href="https://www.researchgate.net/profile/Pierre_Nagorny"> ResearchGate</a>
  </p>
</div>

### Post-doc: industrial quality control system (sept.19 - dec.2020)
TheEye:
  industrial Quality Control with semi-supervised Deep Learning, 178k€ funds  
[TheEye website](the-eye.fr)  
[Blog posts](/tags/#theeye)  

### PhD thesis: automated quality control (march 2020)

[Blog posts](/tags/#phd)

_Directors:_ Eric Pairel, Maurice Pillet [\[theses.fr\]](http://www.theses.fr/s162132)  
Grenobles Alpes University, <a href="https://www.univ-smb.fr/symme/">SYMME laboratory</a>  

_Keywords:_ Quality, Injection-molding, Thermography, Polarimetry, Metric learning, Deep Learning

_French title: Contrôle automatique non-invasif de la qualité des produits, application au procédé d'injection-moulage des thermoplastiques._

_Abstract:_
> Controlling a product quality requires measurements of its quality characteristics. One hundred percent control overcomes the limits of the control by sampling, in the case of defects related to exceptional causes. However, industrial constraints have limited the deployment of measurement of product characteristics directly within production lines. Human visual control is limited by its duration incompatible with the production cycle at high speed productions, by its cost and its variability. Computer vision systems present a cost that reserves them for productions with high added value. In addition, the automatic control of the quality of the appearance of the products remains an open research topic.
> Our work aims to meet these constraints, as part of the injection-molding process of thermoplastics. We propose a control system that is non-invasive for the production process. Parts are checked right out of the injection molding machine.
> Thermography of a hot molded part provides information on its geometry, which is complementary to conventional imaging. Polarimetry makes it possible to discriminate curvature defects of surfaces that change the polarization angle of reflected light and defects in the structure of the material that diffuse light.
> Furthermore, specifications on products are more and more tighter. Specifications include complex geometric features, as well as appearance features, which are difficult to formalize. To automate aspect control, it is necessary to model the notion of quality of a part. In order to exploit the measurements made on the hot parts, our approach uses statistical learning methods. Thus, the human expert who knows the notion of quality of a piece transmits his knowledge to the system, by the annotation of a set of learning data. Our control system then learns a metric of the quality of a part, from raw data from sensors. We favor a deep convolutional network approach (Deep Learning) in order to obtain the best performances in fairness of discrimination of the compliant parts. The small amount of annotated samples available in our industrial context has led us to use domain transfer learning methods.
> Finally, in order to meet all the constraints and validate our propositions, we realized the vertical integration of a prototype of device of measure of the parts and the software solution of treatment by statistical learning. The device integrates thermal imaging, polarimetric imaging, lighting and the on-board processing system necessary for sending data to a remote analysis server. Two application cases make it possible to evaluate the performance and viability of the proposed solution.

---

### Papers
<iframe markdown="0" width="600px" height="100px" src="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?idHal=pierre-nagorny&CB_auteur=oui&CB_titre=oui&CB_identifiant=oui&CB_article=oui&CB_DOI=oui&CB_Resume_court=oui&CB_vignette=oui&CB_video=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&tri_exp4=auteur_exp&ordre_aff=TA&Fen=Aff&css=../css/VisuCondense.css" frameborder="0" scrolling="auto" style="display:block; margin: 0 auto;"></iframe>

[1] **Pierre Nagorny**, Thomas Lacombe, Thomas Muller, Hugues Favreliere, Eric Pairel, et al. **Polarimetric Imaging for Quality Control in Injection Molding.**  
Quality Control by Artificial Vision 2019, IRIMAS laboratory, Haute–Alsace University, May 2019, Mulhouse, France. pp.92,  
<a href="https://doi.org/10.1117/12.2522062">&#x27E8;10.1117/12.2522062&#x27E9;</a>. <a href="https://hal.archives-ouvertes.fr/hal-02142317">&#x27E8;hal–02142317&#x27E9;  

[2] **Pierre Nagorny**, Thomas Lacombe, Hugues Favreliere, Maurice Pillet, Eric Pairel, et al. **Generative Adversarial Networks for geometric surfaces prediction in injection molding: Performance analysis with Discrete Modal Decomposition.**  
2018 IEEE International Conference on Industrial Technology (ICIT), IEEE IES, Lyon 1 University, Ampère Lab, Satie Lab, Feb 2018, Lyon, France. pp.1514–1519,  
<a href="https://doi.org/10.1109/ICIT.2018.8352405">&#x27E8;10.1109/ICIT.2018.8352405&#x27E9;</a>. <a href="https://hal.archives-ouvertes.fr/hal-01995293">&#x27E8;hal–01995293&#x27E9;</a>  

[3] **Pierre Nagorny**, Maurice Pillet, Eric Pairel. **Contrôle Qualité 2.0 : Apprentissage supervisé de la notion de Qualité, application à l’injection plastique.**  
CIGI–QUALITA 2019, École de Technologie Supérieure de Montréal, Jun 2019, Montréal, Canada.  
<a href="https://hal.archives-ouvertes.fr/hal-02142331">&#x27E8;hal–02142331&#x27E9;</a>  

[4] **Pierre Nagorny**, Maurice Pillet, Eric Pairel, Ronan Le Goff, Jerôme Loureaux, et al. **Quality Prediction in Injection Molding: Neural networks geometric dimension prediction on raw signals and thermographic images.**  
IEEE International Conference on Computational Intelligence and Virtual Environments for Measurement Systems and Applications (CIVEMSA 2017), IEEE, Jun 2017, Annecy, France. pp.141–146,  
<a href="https://doi.org/10.1109/CIVEMSA.2017.7995316">&#x27E8;10.1109/CIVEMSA.2017.7995316&#x27E9;</a>. <a href="https://hal.archives-ouvertes.fr/hal-01552111">&#x27E8;hal–01552111&#x27E9;</a>  

[5] **Pierre Nagorny**, Eric Pairel, Maurice Pillet. **Pilotage en Injection Plastique – Etat de l’Art.**  
12ème Congrès International de Génie Industriel (CIGI 2017), May 2017, Compiègne, France.  
<a href="https://hal.archives-ouvertes.fr/hal-01551840">&#x27E8;hal–01551840&#x27E9;</a>  

[6] **Pierre Nagorny**, Eric Pairel, Maurice Pillet. **Vers un pilotage de la qualité des pièces injectées.**  
15ème Colloque National AIP PRIMECA : ”Concevoir et produire dans les industries du futur”, AIP Primeca, Apr 2017, La Plagne, France.  
<a href="https://hal.archives-ouvertes.fr/hal-01551797">&#x27E8;hal–01551797&#x27E9;</a>  

---

### Patent

- Dispositif de contrôle de la qualité de pièces plastiques, 2019  

---

### Conferences

- <a href="http://cigiqualita2019.etsmtl.ca">CIGI QUALITA 2019</a>, Montreal, June 2019  
  How to quality control on the production line with a webcam.  
  [Blog post](/QUALITA2019-not-going-to-Montreal/)

- <a href="https://www.qcav2019.uha.fr/">SPIE QCAV 2019</a>, Mulhouse, May 2019  
  Trying to quality control with polarimetry.  
  [Blog post](/QUALITA2019-not-going-to-Montreal/)

- <a href="http://icit2018.org/en">IEEE ICIT 2018</a>, Lyon, February 2018  
  Discussion on encouraging results of GANs to predict the quality of molded parts.  
  [Blog post](/thermo2geo-geometry-from-thermography-in-injection-molding/)

- <a href="http://2017.civemsa.ieee-ims.org">IEEE CIVEMSA 2017</a>, USMB, Annecy, June 2017  
  Compare classic neural networks (CNN, LSTM) with advanced regressions methods for part quality analysis. Neural networks worked the best.
  [Blog post](/the-first-paper/)

- <a href="http://cigi2017.utc.fr">CIGI 2017</a>, UTC, Compiègnes, May 2017  
  French review of state of the art methods for injection molding machine control.

- <a href="https://aip-primeca2017.sciencesconf.org">Seminar AIP Primeca</a>, La Plagne, Apr. 2017  
  First experimental results and research perspectives.

---

### Posters
- Doctoral school students day, November 2020  
  TheEye system for non-invasive industrial quality control.  
- Doctoral school students day, November 2019  
  Polarimetry and thermography with Deep Learning for quality control.  
- Doctoral school students day, November 2018  
  Thermography for quality control with Deep Learning.  
- Doctoral school students day, November 2017  
  Presentatation of my method for the measurement and analysis of hot plastic parts within industrial cycle time constraints.  

---

### Softwares
- Deep Quality Control: web UI + Deep Learning pipeline + hardware integration
- TheEye: web app + Deep Learning pipeline + non-conventional cameras software-hardware integration

---

### Movie
- [Presentation of the SYMME laboratory](https://www.youtube.com/watch?v=D8mj7Rv1wdQ)  
  Doctoral school students day, November 2018, [blog post](/Directing-the-presentation-of-the-SYMME-lab)  

---

### Research topics

- [Realistic motion design](/on-realistic-motion-design/)
- Innovative robotic design: optimized mechatronic
- Reinforcement learning, General AI
- Deep neural network explainability, robustness & safety
- Modern UX for human-centric teachable Big Data
