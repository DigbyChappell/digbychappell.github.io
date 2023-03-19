---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My research focus is on improving **prosthetic hand control** from a holistic perspective, looking at user training, sensory feedback, and developing myoelectric control algorithms.

<details>
  <summary><strong>Myoelectric Control</strong></summary>

  <strong>Control with Minimal Data</strong><br>
  <img src="https://dchappell2203.github.io//images/research/wass_discrete.gif" align="left" width="600px"><br clear="left"/>
  
  Prosthetic hand control research typically focuses on developing increasingly complex controllers to achieve diminishing returns in pattern recognition of muscle activity signals, making models less suitable for user calibration. Some works have investigated transfer learning to alleviate this, but such approaches increase model size dramatically---thus reducing their suitability for implementation on real prostheses. In this work, we propose a novel, non-parametric controller that uses the Wasserstein distance to compare the distribution of incoming signals to those of a set of reference distributions, with the intended action classified as the closest distribution. This controller requires only a single capture of data per reference distribution, making calibration almost instantaneous. Preliminary experiments building a reference library show that, in theory, users are able to produce up to 9 distinguishable muscle activity patterns. However, in practice, variation when repeating actions reduces this. Controller accuracy results show that 10 non-disabled and 1 disabled participant were able to use the controller with a maximum of two recalibrations to perform 6 actions at an average accuracy of 89.9% and 86.7%, respectively. Practical experiments show that the controller allows users to complete all tasks of the Jebsen-Taylor Hand Function Test, although the task of picking and placing small common objects required on average more time than the protocol’s maximum time.
  
  <br>Find out more:<br>
  <a href="https://ieeexplore.ieee.org/abstract/document/9896480/" target="_blank">Paper</a>
  | <a href="https://ieeexplore.ieee.org/abstract/document/9896480/" target="_blank">PDF</a>
  | <a href="https://www.youtube.com/watch?v=AWtHQU4buZI" target="_blank">Video</a>
  | <a href="https://www.youtube.com/watch?v=O_SNMl11OJY" target="_blank">Presentation</a>
  <br clear="left"/>
  <br><br>
  
  <strong>Embedded Deep Learning-Based Control</strong><br>
  <img src="https://dchappell2203.github.io//images/research/embedded.png" align="left" width="300px">
  Prosthetic hands
  <br>Find out more:<br>
  <a href="https://ieeexplore.ieee.org/abstract/document/9811741/" target="_blank">Paper</a>
  | <a href="https://drive.google.com/file/u/0/d/1RFQpLkuLijaY43AA8kR5XPqLvcGlExeF/view" target="_blank">PDF</a>
  | <a href="https://www.youtube.com/watch?v=fXIlpW6o_YAY" target="_blank">Presentation</a>
  <br clear="left"/>

</details>
<br>
<details>
  <summary><strong>Sensory Feedback</strong></summary>

  <strong>Haptic Feedback Armband Development</strong><br>
  <img src="https://dchappell2203.github.io//images/research/haptic_armband.png" align="left" width="750px"><br clear="left"/>
  Prosthetic hands
  <br>Find out more:<br>
  <a href="https://link.springer.com/chapter/10.1007/978-3-031-06249-0_16" target="_blank">Paper</a>
  | <a href="https://link.springer.com/content/pdf/10.1007/978-3-031-06249-0_16.pdf" target="_blank">PDF</a>
  | <a href="https://webcast.tuhh.de/Mediasite/Play/bdcfa56e8f1c4593a4690fd58b644c2d1d" target="_blank">Presentation</a>
  <br clear="left"/>

</details>
<br>
<details>
  <summary><strong>User Training</strong></summary>

  <strong>Virtual Reality Training</strong><br>
  <img src="https://dchappell2203.github.io//images/research/vr_training.png" align="left" width="300px">
  Prosthetic hands
  <br>Find out more:<br>
  <a href="https://ieeexplore.ieee.org/abstract/document/9714006" target="_blank">Paper</a>
  | <a href="https://spiral.imperial.ac.uk/bitstream/10044/1/95373/2/Conference_Paper___ICRA_2022___VR_Prosthetic_Hand_Feedback_Resubmission.pdf" target="_blank">PDF</a>
  | <a href="https://www.youtube.com/watch?v=beY-pm6CNCM" target="_blank">Video</a>
  | <a href="https://www.youtube.com/watch?v=8G7L77RqZ6o" target="_blank">Presentation</a>
  <br clear="left"/>

</details>
<br>

[[go top](https://dchappell2203.github.io/research/)]  
