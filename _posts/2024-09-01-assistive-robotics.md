---
title: Robot-assisted Dressing 
layout: post
post-image: 
description: 
tags:
- Assistive Robots
- Bimanual Manipulation
---
**Project members**: Sumaya Alsefri, Liman Wang, Jian Zhao, and [Dr.ir. Jihong Zhu](https://jihong-zhu.github.io/)

# List of Research
1. [Bimanual Dressing](#bimanual_dressing)
2. [MLLM-Fabric](#MLLM_fabric)

## Bimanual Dressing <a name="bimanual_dressing"></a>
Robot-assisted dressing is a popular but challenging topic in the field of robotic manipulation, offering significant potential to improve the quality of life for individuals with mobility limitations. Currently, the majority of research on robot-assisted dressing focuses on how to put on loose-fitting clothing, with little attention paid to tight garments. For the former, since the armscye is larger, a single robotic arm can usually complete the dressing task successfully. However, for the latter, dressing with a single robotic arm often fails due to the narrower armscye and the property of diminishing rigidity in the armscye, which eventually causes the armscye to get stuck. This paper proposes a bimanual dressing strategy suitable for dressing tight-fitting clothing. To facilitate the encoding of dressing trajectories that adapt to different human arm postures, a spherical coordinate system for dressing is established. We uses the azimuthal angle of the spherical coordinate system as a task-relevant feature for bimanual manipulation. Based on this new coordinate, we employ Gaussian Mixture Model (GMM) and Gaussian Mixture Regression (GMR) for imitation learning of bimanual dressing trajectories, generating dressing strategies that adapt to different human arm postures. The effectiveness of the proposed method is validated through various experiments.

<br/>
J. Zhao, Y. Lian, A. M. Tyrrell, M. Gienger and J. Zhu, "Bimanual Robot-Assisted Dressing: A Spherical Coordinate-Based Strategy for Tight-Fitting Garments," 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Hangzhou, China, 2025, pp. 3328-3335

## MLLM-Fabric: Multimodal Large Language Model-Driven Robotic Framework for Fabric Sorting and Selection <a name="MLLM_fabric"></a>
Choosing the right fabric is crucial to meet functional and quality requirements in robotic applications for textile manufacturing, apparel production, and smart retail. We present MLLM-Fabric, a robotic framework powered by multimodal large language models (MLLMs) for fabric sorting and selection. The system includes a robotic arm, a camera, a visuotactile sensor, and a pressure sensor. It employs supervised fine-tuning and multimodal explanation-guided knowledge distillation to accurately classify and rank fabric properties. To facilitate further research, we release a dataset of 200 fabric samples, including RGB images and synchronized visuotactile and pressure data. Experimental results show that our Fabric-Llama-90B model outperforms baseline pre-trained models, achieving state-of-the-art performance.

<br/>
L. Wang, H. Zhong, T. Wang, S. Luo and J. Zhu, "MLLM-Fabric: Multimodal Large Language Model-Driven Robotic Framework for Fabric Sorting and Selection," in IEEE Robotics and Automation Letters, vol. 10, no. 12, pp. 13137-13144, Dec. 2025

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=VeN7tr4-WvM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
