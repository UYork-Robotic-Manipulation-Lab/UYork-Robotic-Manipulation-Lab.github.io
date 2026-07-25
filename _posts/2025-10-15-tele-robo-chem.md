---
title: Safe Tele-Operated Robotic Chemistry (Safe-TORCH)  
layout: post
post-image: "/assets/images/Safe-TORCH.png"
description: "The project was supported by Institute for Safe Autonomy Sandpits
"
tags:
- Robots for Chemistry
- Bimanual Manipulation
---
**Project members**: Kefeng Huang, Jonathon Pipe, [Dr.ir. Jihong Zhu](https://jihong-zhu.github.io/), and [Prof. Ian Fairlamb](https://www.york.ac.uk/chemistry/people/ifairlamb/).

Handling hazardous materials, such as those in air-sensitive chemistry, presents significant risks to laboratory personnel and requires specialist expertise that is often geographically constrained. This project addresses this challenge by developing a novel framework that allows expert chemists to perform complex tasks remotely and safely with a robotic partner. Project S-TORCH will deliver a proof-of-concept demonstrator featuring a dual-arm robot in the ISA teleoperated by a chemist from Chemistry to conduct chemistry operations. The success of this human-robot team hinges on our three core research pillars: high-reliability Communication for seamless, low-latency control; formal Verification of the robotic control system to guarantee precise and predictable actions; and a robust safety Assurance case to govern the human-robot collaboration via teleoperation. 

The project will culminate in an end-to-end demonstration of the system successfully performing chemistry experiment procedure remotely. By de-risking this core technology, S-TORCH will provide a powerful platform for securing major follow-on funding and lay the groundwork for the future of safer, more accessible, and AI-enabled chemical laboratories.

# List of Research
1. [Chemistry Manipulation Taxonomy](#TARMAC)

## Chemistry Manipulation Taxonomy <a name="TARMAC"></a>

**paper currently under revision for [nature communication chemistry](https://www.nature.com/commschem/)**

Laboratory automation has made well-defined experimental protocols increasingly executable by machines, yet the physical manipulations surrounding those protocols remain difficult to generalize. Setup, transfer, adjustment, assembly, and cleanup operations form a long tail of context-dependent actions that are typically handled manually or implemented as bespoke robotic skills for individual workflows and platforms.

TARMAC is an empirical taxonomy of laboratory actions grounded in the analysis of instructional chemistry practice. Rather than prescribing a control framework, it emerges from a bottom-up decomposition of real laboratory manipulations into physically meaningful primitives organized by wrench dependence, actuation directness, and motion periodicity.

Across the experimental contexts examined, the majority of actions can be expressed as compositions of a finite and reusable set of primitives. This structure provides a basis for organizing, comparing, and reusing manipulation capabilities across experimental workflows.

More information: [https://tarmac-paper.github.io/#resources](https://tarmac-paper.github.io/#resources)
