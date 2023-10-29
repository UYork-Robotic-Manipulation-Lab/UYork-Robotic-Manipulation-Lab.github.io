---
title: Deformable Object Manipulation (DOM)
layout: post
post-image: "/assets/images/berry-picking.png"
description: "The project was supported by H2020 VERSATILE Project and PROCORE-France/Hong Kong RGC Joint Research Scheme (2018-2019).
"
tags:
- Deformable Object Manipulation
---
# List of Research
1. [Cable Shaping](#cable_shaping)
2. [Unified Shape Servoing](#unified_shape_servoing)
3. [Latent Representation for DOM](#latent_rep)
4. [Survey on DOM](#survey)

## A Cable Shaping Robot <a name="cable_shaping"></a>
Humans use contacts in the environment to modify the shape of deformable objects. Yet, few papers have studied the use of contacts in robotic manipulation. In this letter, we investigate the problem of robotic manipulation of cables with environmental contacts. Instead of avoiding contacts, we propose a framework that allows the robot to use them for shaping the cable. We introduce an index to quantify the contact mobility of a cable with a circular contact. Based on this index, we present a planner to plan robot motions. The planner is aided by a vision-based contact detector. The framework is validated with robot experiments on different desired cable configurations.

<br/>
J. Zhu, B. Navarro, R. Passama, P. Fraisse, A. Crosnier and A. Cherubini, “Robotic Manipulation Planning for Shaping Deformable Linear Objects WithEnvironmental Contacts,” in IEEE Robotics and Automation Letters, vol. 5, no. 1, pp. 16-23, Jan. 2020, doi: 10.1109/LRA.2019.2944304.

<iframe width="560" height="315" src="https://www.youtube.com/embed/7CdNQ4R_wT0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Unified Shape Servoing <a name="unified_shape_servoing"></a>
This paper proposes a unified vision-based manipulation framework using image contours of deformable/rigid objects. Instead of explicitly defining the features by geometries or functions, the robot automatically learns the visual features from processed vision data. Our method simultaneously generates -- from the same data – both visual features and the interaction matrix that relates them to the robot control inputs. Extraction of the feature vector and control commands is done online and adaptively, and requires little data for initialization. Our method allows the robot to manipulate an object without knowing whether it is rigid or deformable. To validate our approach, we conduct numerical simulations and experiments with both deformable and rigid objects.

<br/>
J. Zhu, D. Navarro-Alarcon, R. Passama, & A. Cherubini, Vision-based manipulation of deformable and rigid objects using subspace projections of 2d contours. Robotics and Autonomous Systems, 142, 103798.

<iframe width="560" height="315" src="https://www.youtube.com/embed/gYfO2ZxZ5KQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Latent Representation for DOM <a name="latent_rep"></a>
Soft object manipulation has recently gained popularity within the robotics community due to its potential applications in many economically important areas. Although great progress has been recently achieved in these types of tasks, most state-of-the-art methods are case-specific; They can only be used to perform a single deformation task (e.g., bending), as their shape representation algorithms typically rely on “hard-coded” features. In this letter, we present LaSeSOM, a new feedback latent representation framework for semantic soft object manipulation. Our new method introduces internal latent representation layers between low-level geometric feature extraction and high-level semantic shape analysis; This allows the identification of each compressed semantic function and the formation of a valid shape classifier from different feature extraction levels. The proposed latent framework makes soft object representation more generic (independent from the object's geometry and its mechanical properties) and scalable (it can work with 1D/2D/3D tasks). Its high-level semantic layer enables to perform (quasi) shape planning tasks with soft objects, a valuable and underexplored capability in many soft manipulation tasks. To validate this new methodology, we report a detailed experimental study with robotic manipulators.

<br/>
P. Zhou, J. Zhu, S. Huo and D. Navarro-Alarcon, “LaSeSOM: A Latent and Semantic Representation Framework for Soft Object Manipulation,” in IEEE Robotics and Automation Letters, vol. 6, no. 3, pp. 5381-5388, July 2021, doi: 10.1109/LRA.2021.3074872.

## Challenges and Outlook in Deformable Object Manipulation <a name="survey"></a> 
<span style="color:red">One of the most popular of IEEE Robotics and Automation Magazine since its publication in Sept 2022</span>.

Deformable object manipulation (DOM) is an emerging research problem in robotics. The ability to manipulate deformable objects endows robots with higher autonomy and promises new applications in the industrial, services, and health-care sectors. However, compared to rigid object manipulation, the manipulation of deformable objects is considerably more complex and is still an open research problem. Addressing DOM challenges demands breakthroughs in almost all aspects of robotics: hardware design, sensing, (deformation) modeling, planning, and control. In this article, we review recent advances and highlight the main challenges when considering deformation in each subfield. A particular focus of our article lies in the discussions of these challenges and proposing future directions of research.

<br/>
J. Zhu, A. Cherubini, C. Dune, D. Navarro-Alarcon, F. Alambeigi, D. Berenson, F. Ficuciello, K. Harada, X. Li, J. Pan, W. Yuan, and M. Gienger, Challenges and outlook in robotic manipulation of deformable objects. IEEE Robotics and Automation Magazine, 2022.


<!-- **Giphy Gifs will look like:**<br>
<iframe src="https://giphy.com/embed/ZqlvCTNHpqrio" width="480" height="259" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/laughing-despicable-me-minions-ZqlvCTNHpqrio">via GIPHY</a></p> -->

<!-- **YouTUbe Videos will look like:**<br> -->
