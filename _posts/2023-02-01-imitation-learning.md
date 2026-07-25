---
title: Learning from Negative Demonstrations
layout: post
post-image: 
description: 
tags:
- Imitation Learning
---
**Project members**: John Bateman, and [Dr.ir. Jihong Zhu](https://jihong-zhu.github.io/)

Programming robots to perform complex tasks is often difficult and time consuming, requiring expert knowledge and skills in robot software and sometimes hardware. Imitation learning is a method for training robots to perform tasks by leveraging human expertise through demonstrations. Typically, the assumption is that those demonstrations are performed by a single, highly competent expert. However, in many real-world applications that use user demonstrations for tasks or incorporate both user data and pretrained data, such as home robotics including assistive robots, this is unlikely to be the case. This paper presents research towards a system which can leverage suboptimal demonstrations to solve ambiguous tasks; and particularly learn from its own failures. This is a negative-feedback system which achieves significant improvement over purely positive imitation learning for ambiguous tasks, achieving a 90\% improvement in success rate against a system that does not utilise negative feedback, compared to a 50\% improvement in success rate when utilised on a real robot, as well as demonstrating higher efficacy, memory efficiency and time efficiency than a comparable negative feedback scheme. The novel scheme presented in this paper is validated through simulated and real-robot experiments.
