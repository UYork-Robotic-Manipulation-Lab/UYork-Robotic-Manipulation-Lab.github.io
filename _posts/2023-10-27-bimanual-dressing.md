---
title: Learning Physical Human-Robot Cooperation Tasks
layout: post
post-image: "/assets/images/HRCooperation.png"
description: "The project was supported by Honda Research Institute Europe GmbH.
"
tags:
- Assistive Robots
- Bimanual Manipulation
---
# List of Research
1. [Bimanual Dressing Assistance](#dressing)
2. [Data Effcient Task-Parameterized Imitation Learning](#TP_learning)
3. [Learning from Few Demonstrations](#learning_from_few_demo)
4. [Cloth Flattening using Wrinkle Direction](#cloth_flattening)

## Bimanual Robotics Dressing Assistance <a name="dressing"></a>
Developing physically assistive robots capable of dressing assistance has the potential to significantly improve the lives of the elderly and disabled population. However, most robotics dressing strategies considered a single robot only, which greatly limited the performance of the dressing assistance. In fact, healthcare professionals perform the task bimanually. Inspired by them, we propose a bimanual cooperative scheme for robotic dressing assistance. In the scheme, an interactive robot joins hands with the human thus supporting/guiding the human in the dressing process, while the dressing robot performs the dressing task. We identify a key feature that affects the dressing action and propose an optimal strategy for the interactive robot using the feature. A dressing coordinate based on the posture of the arm is defined to better encode the dressing policy. We validate the interactive dressing scheme with extensive experiments and also an ablation study. The experiment video is available on [Bimanual dressing assistance](https://sites.google.com/view/bimanualassitdressing/)

<br/>
Zhu J, [Gienger M.](https://scholar.google.nl/citations?user=oU2jyxMAAAAJ&hl=en), Giovanni Franzese, [Kober J.](http://www.jenskober.de/index.php) [Do You Need a Hand? -- An Bimanual Robotic Dressing Assistance Scheme](https://arxiv.org/abs/2301.02749)

<iframe width="560" height="315" src="https://www.youtube.com/embed/TsJ7xoozcb8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Data Effcient Task-Parameterized Imitation Learning <a name="TP_learning"></a>
Moving away from repetitive tasks, robots nowadays demand versatile skills that adapt to different situations. Task-parameterized learning improves the generalization of motion policies by encoding relevant contextual information in the task parameters, hence enabling flexible task executions. However, training such a policy often requires collecting multiple demonstrations in different situations. To comprehensively create different situations is non-trivial thus renders the method less applicable to real-world problems. Therefore, training with fewer demonstrations situations is desirable. This paper presents a novel concept to augment the original training dataset with synthetic data for policy improvements, thus allows learning task-parameterized skills with few demonstrations.

<br/>
Zhu J, [Gienger M.](https://scholar.google.nl/citations?user=oU2jyxMAAAAJ&hl=en), [Kober J.](http://www.jenskober.de/index.php) Learning Task-Parameterized Skills from Few Demonstrations, IEEE Robotics and Automation Letters, vol. 7, no. 2, pp. 4063-4070, April 2022.

<iframe width="560" height="315" src="https://www.youtube.com/embed/yY4k1nnhA60" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Learning from Few Demonstrations <a name="learning_from_few_demo"></a>
Learning from Demonstration (LfD) enables robots to acquire versatile skills by learning motion policies from human demonstrations. It endows users with an intuitive interface to transfer new skills to robots without the need for time-consuming robot programming and inefficient solution exploration. During task executions, the robot motion is usually influenced by constraints imposed by environments. In light of this, task-parameterized LfD (TP-LfD) encodes relevant contextual information into reference frames, enabling better skill generalization to new situations. However, most TP-LfD algorithms typically require multiple demonstrations across various environmental conditions to ensure sufficient statistics for a meaningful model. It is not a trivial task for robot users to create different situations and perform demonstrations under all of them. Therefore, this paper presents a novel algorithm to learn skills from few demonstrations. By leveraging the reference frame weights that capture the frame importance or relevance during task executions, our method demonstrates excellent skill acquisition performance, which is validated in real robotic environments

<br/>
Jianyong Sun, Jens Kober, Michael Gienger and Jihong Zhu. [Learning from Few Demonstrations with Frame-Weighted Motion Generation](https://arxiv.org/pdf/2303.14188.pdf). In 18th International Symposium on Experimental Robotics (ISER), 2023.

<iframe width="560" height="315" src="https://www.youtube.com/embed/JpGjk4eKC3o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Cloth Flattening using Wrinkle Direction <a name="cloth_flattening"></a> 
Deformable Object Manipulation (DOM) is an important field of research as it contributes to practical tasks such as automatic cloth handling, cable routing, surgical operation, etc. Perception is considered one of the major challenges in DOM due to the complex dynamics and high degree of freedom of deformable objects. In this paper, we develop a novel image-processing algorithm based on Gabor filters to extract useful features from cloth, and based on this, devise a strategy for cloth flattening tasks. We also evaluate the overall framework experimentally and compare it with three human operators. The results show that our algorithm can determine the direction of wrinkles on the cloth accurately in simulation as well as in real robot experiments. Furthermore, our dewrinkling strategy compares favorably to baseline methods. The experiment video is available on [https://sites.google.com/view/robotic-fabric-flattening/home](https://sites.google.com/view/robotic-fabric-flattening/home)

<br/>
Yulei Qiu, Jihong Zhu, Cosimo Della Santina, Michael Gienger, and Jens Kober. [Robotic Fabric Flattening with Wrinkle Direction Detection](https://arxiv.org/pdf/2303.04909.pdf). In 18th International Symposium on Experimental Robotics (ISER), 2023.

<iframe width="560" height="315" src="https://www.youtube.com/embed/oQRbsAm78Rk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- **Giphy Gifs will look like:**<br>
<iframe src="https://giphy.com/embed/ZqlvCTNHpqrio" width="480" height="259" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/laughing-despicable-me-minions-ZqlvCTNHpqrio">via GIPHY</a></p> -->

<!-- **YouTUbe Videos will look like:**<br> -->
