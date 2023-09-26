---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

My research focus is on improving **prosthetic hand control** from a multifaceted, user-centric perspective, looking at every aspect from training with traditional myoelectric controllers, advancing classification-based controllers, developing continuous controllers, and designing more effective terminal devices and grippers.

<details>
  <summary><strong>Terminal Device and Gripper Design</strong></summary>

  <strong>The Hydra Hand (RA-L 2023)</strong><br>
  <img src="https://digbychappell.github.io//images/research/hydra.png" align="left" width="300px">
  Human hands are able to grasp a wide range of object sizes, shapes, and weights, achieved via reshaping and altering their apparent grasping stiffness between compliant power and rigid precision. Achieving similar versatility in robotic hands remains a challenge, which has often been addressed by adding extra controllable degrees of freedom, tactile sensors, or specialised extra grasping hardware, at the cost of control complexity and robustness. We introduce a novel reconfigurable four-fingered two-actuator underactuated gripper -- the Hydra Hand -- that switches between compliant power and rigid precision grasps using a single motor, while generating grasps via a single hydraulic actuator -- exhibiting adaptive grasping between finger pairs, enabling the power grasping of two objects simultaneously. The mode switching mechanism and the hand's kinematics are presented and analysed, and performance is tested on two grasping benchmarks: one focused on rigid objects, and the other on items of clothing. The Hydra Hand is shown to excel at grasping large and irregular objects, and small objects with its respective compliant power and rigid precision configurations. The hand's versatility is then showcased by executing the challenging manipulation task of safely grasping and placing a bunch of grapes, and then plucking a single grape from the bunch.
  <br>Find out more:<br>
  <a href="https://arxiv.org/pdf/2309.14266.pdf" target="_blank">PDF</a>
  | <a href="https://www.youtube.com/watch?v=upLHX3POim0" target="_blank">Video</a>
  <br clear="left"/>
</details>
<br>

<details>
  <summary><strong>Continuous Myoelectric Control</strong></summary>

[//]: # (  <strong>Closed-Loop Continuous Control &#40;Under Review&#41;</strong><br>)

[//]: # (  <img src="https://digbychappell.github.io//images/research/haptic_armband.png" align="left" width="750px"><br clear="left"/>)
[//]: # (Myoelectric prosthetic hands are typically controlled to move between discrete positions and do not provide sensory feedback to the user. Attempts to move beyond this are either invasive, using costly experimental implanted technology, or are noninvasive, using skin-mounted hardware with limited results. In this work, we present and evaluate a next-generation non-invasive myoelectric controller that can continuously control multiple degrees of freedom of a prosthesis while rendering feedback to the user via a haptic feedback armband. In one of the largest studies investigating a new prosthetic hand controller, in terms of participant numbers and breadth of tasks, twenty-eight participants without and ten participants with limb difference were recruited to holistically evaluate the controller. Isolated control and sensory tasks, dexterity assessments, embodiment and task load questionnaires, and post-study interviews were used to understand physical and psychological aspects of controller performance, and study, in real time, the developing relationship between user and prosthesis. The controller is shown to excel at control, sensory, and precision tasks, promote perceived natural motion, and reduce frustration and physical demand; results only achievable when combining haptic feedback and continuous control. Perception influencing factors and key participant differences are identified, informing future rehabilitation practice and research.  <br>Find out more:<br>)

[//]: # (  <a href="https://link.springer.com/chapter/10.1007/978-3-031-06249-0_16" target="_blank">Paper</a>)
[//]: # (  | <a href="https://link.springer.com/content/pdf/10.1007/978-3-031-06249-0_16.pdf" target="_blank">PDF</a>)
[//]: # (  | <a href="https://webcast.tuhh.de/Mediasite/Play/bdcfa56e8f1c4593a4690fd58b644c2d1d" target="_blank">Presentation</a>)
[//]: # (  <br clear="left"/>)

  <strong>Haptic Feedback Armband Development (EuroHaptics 2022)</strong><br>
  <img src="https://digbychappell.github.io//images/research/haptic_armband.png" align="left" width="750px"><br clear="left"/>
  This paper presents the implementation and evaluation of three specific, yet complementary, mechanisms of haptic feedback---namely normal displacement, tangential position, and vibration---to render, at a finger-level, aspects of touch and proprioception from a prosthetic hand without specialised sensors. This feedback is executed by an armband worn around the upper arm divided into five somatotopic modules, one per each finger. To evaluate the system, just-noticeable difference experiments for normal displacement and tangential position were carried out, validating that users are most sensitive to feedback from modules located on glabrous (hairless) skin regions of the upper arm. Moreover, users identifying finger-level contact using multi-modal feedback of vibration followed by normal displacement performed significantly better than those using vibration feedback alone, particularly when reporting exact combinations of fingers. Finally, the point of subjective equality of tangential position feedback was measured simultaneously for all modules, which showed promising results, but indicated that further development is required to achieve full finger-level position rendering.
  <br>Find out more:<br>
  <a href="https://link.springer.com/chapter/10.1007/978-3-031-06249-0_16" target="_blank">Paper</a>
  | <a href="https://link.springer.com/content/pdf/10.1007/978-3-031-06249-0_16.pdf" target="_blank">PDF</a>
  | <a href="https://webcast.tuhh.de/Mediasite/Play/bdcfa56e8f1c4593a4690fd58b644c2d1d" target="_blank">Presentation</a>
  <br clear="left"/>

</details>
<br>

<details>
  <summary><strong>Classification-Based Myoelectric Control</strong></summary>

  <strong>Control with Minimal Data (ICORR 2022)</strong><br>
  <img src="https://digbychappell.github.io//images/research/wass_discrete.gif" align="left" width="600px"><br clear="left"/>
  
  Prosthetic hand control research typically focuses on developing increasingly complex controllers to achieve diminishing returns in pattern recognition of muscle activity signals, making models less suitable for user calibration. Some works have investigated transfer learning to alleviate this, but such approaches increase model size dramatically---thus reducing their suitability for implementation on real prostheses. In this work, we propose a novel, non-parametric controller that uses the Wasserstein distance to compare the distribution of incoming signals to those of a set of reference distributions, with the intended action classified as the closest distribution. This controller requires only a single capture of data per reference distribution, making calibration almost instantaneous. Preliminary experiments building a reference library show that, in theory, users are able to produce up to 9 distinguishable muscle activity patterns. However, in practice, variation when repeating actions reduces this. Controller accuracy results show that 10 participants without and 1 participant with upper limb difference were able to use the controller with a maximum of two recalibrations to perform 6 actions at an average accuracy of 89.9% and 86.7%, respectively. Practical experiments show that the controller allows users to complete all tasks of the Jebsen-Taylor Hand Function Test, although the task of picking and placing small common objects required on average more time than the protocol’s maximum time.
  
  <br>Find out more:<br>
  <a href="https://ieeexplore.ieee.org/abstract/document/9896480/" target="_blank">Paper</a>
  | <a href="https://spiral.imperial.ac.uk/bitstream/10044/1/96928/2/Conference_Paper___ICORR_2022___Wasserstein_Control.pdf" target="_blank">PDF</a>
  | <a href="https://www.youtube.com/watch?v=AWtHQU4buZI" target="_blank">Video</a>
  | <a href="https://www.youtube.com/watch?v=O_SNMl11OJY" target="_blank">Presentation</a>
  <br clear="left"/>
  <br><br>
  
  <strong>Embedded Deep Learning-Based Control (ICRA 2022)</strong><br>
  <img src="https://digbychappell.github.io//images/research/embedded.png" align="left" width="300px">
  Achieving instinctive multi-grasp control of prosthetic hands typically still requires a large number of sensors, such as electromyography (EMG) electrodes mounted on a residual limb, that can be costly and time consuming to position, with their signals difficult to classify. Deep-learning-based EMG classifiers however have shown promising results over traditional methods, yet due to high computational requirements, limited work has been done with in-prosthetic training. By targeting specific muscles non-invasively, separating grasping action into hold and release states, and implementing data augmentation, we show in this paper that accurate results for embedded, instinctive, multi-grasp control can be achieved with only 2 low-cost sensors, a simple neural network, and minimal amount of training data. The presented controller, which is based on only 2 surface EMG (sEMG) channels, is implemented in an enhanced version of the OLYMPIC prosthetic hand. Results demonstrate that the controller is capable of identifying all 7 specified grasps and gestures with 93% accuracy, and is successful in achieving several real-life tasks in a real world setting.
  <br>Find out more:<br>
  <a href="https://ieeexplore.ieee.org/abstract/document/9811741/" target="_blank">Paper</a>
  | <a href="https://drive.google.com/file/u/0/d/1RFQpLkuLijaY43AA8kR5XPqLvcGlExeF/view" target="_blank">PDF</a>
  | <a href="https://www.youtube.com/watch?v=fXIlpW6o_YAY" target="_blank">Presentation</a>
  <br clear="left"/>

</details>
<br>

<details>
  <summary><strong>User Training with Traditional Myoelectric Controllers</strong></summary>

  <strong>Virtual Reality Training (RA-L 2022)</strong><br>
  <img src="https://digbychappell.github.io//images/research/vr_training.png" align="left" width="300px">
  Virtual reality (VR) rehabilitation systems have been proposed to enable prosthetic hand users to perform training before receiving their prosthesis. Improving pre-prosthetic training to be more representative and better prepare the patient for prosthesis use is a crucial step forwards in rehabilitation. However, existing VR platforms lack realism and accuracy in terms of the virtual hand and the forces produced when interacting with the environment. To address these shortcomings, this work presents a VR training platform based on accurate simulation of an anthropomorphic prosthetic hand, utilising an external robot arm to render realistic forces that the user would feel at the attachment point of their prosthesis. Experimental results with participants without upper limb difference show that training with this platform leads to a significant improvement in Box and Block scores compared to training in VR alone and a control group with no prior training. Results performing pick-and-place tasks with a wider range of objects demonstrates that training in VR alone negatively impacts performance, whereas the proposed platform has no significant impact on performance. User perception results highlight that the platform is much closer to using a physical prosthesis in terms of physical demand and effort, however frustration is significantly higher during training.
  <br>Find out more:<br>
  <a href="https://ieeexplore.ieee.org/abstract/document/9714006" target="_blank">Paper</a>
  | <a href="https://spiral.imperial.ac.uk/bitstream/10044/1/95373/2/Conference_Paper___ICRA_2022___VR_Prosthetic_Hand_Feedback_Resubmission.pdf" target="_blank">PDF</a>
  | <a href="https://www.youtube.com/watch?v=beY-pm6CNCM" target="_blank">Video</a>
  | <a href="https://www.youtube.com/watch?v=8G7L77RqZ6o" target="_blank">Presentation</a>
  <br clear="left"/>

</details>
<br>

[[go top](https://digbychappell.github.io/research/)]  
