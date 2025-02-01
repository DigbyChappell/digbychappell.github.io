---
layout: archive
title: "Research"
permalink: /research/classification_control/
author_profile: true
---

{% include base_path %}

<strong><big>Classification-Based Myoelectric Control</big></strong>
<br>
<strong>Control with Minimal Data</strong><br>
  <table width="100%" style="border:0px solid white; width:100%">
    <tr style="border:0px;">
      <td align="center" width="750" style="border:0px;"><img src="https://digbychappell.github.io//images/research/wass_discrete.gif" width="600"></td>
    </tr>
    <tr style="border:0px;">
      <td width="750" style="border:0px;"> <a href="https://ieeexplore.ieee.org/abstract/document/9896480/">Towards Instant Calibration in Myoelectric Prosthetic Hands: A Highly Data-Efficient Controller Based on the Wasserstein Distance (Oral Presentation)</a>
        <br><b>Digby Chappell</b>, Zeyu Yang, Honn Wee Son, Fernando Bello, Petar Kormushev, and Nicolas Rojas.<br>
        <i>IEEE International Conference on Rehabilitation Robotics (ICORR).</i> <b>2022</b>.<br>
        <a href="https://spiral.imperial.ac.uk/bitstream/10044/1/96928/2/Conference_Paper___ICORR_2022___Wasserstein_Control.pdf">Paper</a> | <a href="https://www.youtube.com/watch?v=AWtHQU4buZI">Video</a> | <a href="https://www.youtube.com/watch?v=O_SNMl11OJY">Presentation</a>
      </td>
    </tr>
  </table>
Prosthetic hand control research typically focuses on developing increasingly complex controllers to achieve diminishing returns in pattern recognition of muscle activity signals, making models less suitable for user calibration. Some works have investigated transfer learning to alleviate this, but such approaches increase model size dramatically---thus reducing their suitability for implementation on real prostheses. In this work, we propose a novel, non-parametric controller that uses the Wasserstein distance to compare the distribution of incoming signals to those of a set of reference distributions, with the intended action classified as the closest distribution. This controller requires only a single capture of data per reference distribution, making calibration almost instantaneous. Preliminary experiments building a reference library show that, in theory, users are able to produce up to 9 distinguishable muscle activity patterns. However, in practice, variation when repeating actions reduces this. Controller accuracy results show that 10 participants without and 1 participant with upper limb difference were able to use the controller with a maximum of two recalibrations to perform 6 actions at an average accuracy of 89.9% and 86.7%, respectively. Practical experiments show that the controller allows users to complete all tasks of the Jebsen-Taylor Hand Function Test, although the task of picking and placing small common objects required on average more time than the protocol’s maximum time.
  <br><br>
  <strong>Embedded Deep Learning-Based Control (ICRA 2022)</strong><br>
  <table width="100%" style="border:0px solid white; width:100%">
    <tr style="border:0px;">
      <td width="300" style="border:0px; vertical-align:top"><img src="https://digbychappell.github.io//images/research/embedded.png" align="right" width="300px"></td>
      <td width="450" style="border:0px; vertical-align:top"> <a href="https://ieeexplore.ieee.org/abstract/document/9811741/">Instinctive Real-time sEMG-Based Control of Prosthetic Hand with Reduced Data Acquisition and Embedded Deep Learning Training</a>
        <br>Zeyu Yang, Angus B. Clark, <b>Digby Chappell</b>, and Nicolas Rojas.<br>
        <i>IEEE International Conference on Robotics and Automation (ICRA).</i> <b>2023</b>.<br>
        <a href="https://drive.google.com/file/u/0/d/1RFQpLkuLijaY43AA8kR5XPqLvcGlExeF/view">Paper</a> | <a href="https://www.youtube.com/watch?v=fXIlpW6o_YA">Presentation</a>
      </td>
    </tr>
  </table>
Achieving instinctive multi-grasp control of prosthetic hands typically still requires a large number of sensors, such as electromyography (EMG) electrodes mounted on a residual limb, that can be costly and time consuming to position, with their signals difficult to classify. Deep-learning-based EMG classifiers however have shown promising results over traditional methods, yet due to high computational requirements, limited work has been done with in-prosthetic training. By targeting specific muscles non-invasively, separating grasping action into hold and release states, and implementing data augmentation, we show in this paper that accurate results for embedded, instinctive, multi-grasp control can be achieved with only 2 low-cost sensors, a simple neural network, and minimal amount of training data. The presented controller, which is based on only 2 surface EMG (sEMG) channels, is implemented in an enhanced version of the OLYMPIC prosthetic hand. Results demonstrate that the controller is capable of identifying all 7 specified grasps and gestures with 93% accuracy, and is successful in achieving several real-life tasks in a real world setting.
<br><br>

[[go top](https://digbychappell.github.io/research/classification_control/)]  
