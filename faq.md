---
layout: page
title: FAQ
description: Frequently Asked Questions
---

# FAQ
{:.no_toc}

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## I don't have access to robots! What can I do?

If you want to use **physical hardware**, consider using the [AI Maker Space](https://www.cs.cmu.edu/initiatives/ai-maker-space/) in Tepper for your projects! 
To get more info, you can contact the AI Maker Space manager: Greg Armstrong at ai-makerspace@cs.cmu.edu. 

If using physical hardware is infeasible for your project, consider using **simulation** or **benchmark datasets** for controlled testing and algorithm design. Some relevant resources include:

*Autonomous Driving*
* [CARLA](https://github.com/carla-simulator/carla) - driving simulator with urban layouts, buildings, vehicles, and sensors
* [CARLO](https://github.com/Stanford-ILIAD/CARLO) - a lightweight 2D version of CARLA
* [tbsim](https://github.com/NVlabs/traffic-behavior-simulation) - simulation designed for data-driven closed-loop simulation of autonomous vehicles 
* [nuPlan](https://github.com/motional/nuplan-devkit) - large-scale planning benchmark for autonomous driving
* [Waymax](https://github.com/waymo-research/waymax) - a lightweight, multi-agent, JAX-based simulator for autonomous driving research based on the Waymo Open Motion Dataset)

*Manipulation, Locomotion, Indoor Navigation*
* [IsaacSim](https://github.com/isaac-sim/IsaacSim) - simulation platform built on NVIDIA Omniverse, designed to develop, test, train, and deploy AI-powered robots in realistic virtual environments. 
* [robosuite](https://robosuite.ai/) / [robomimic](https://robomimic.github.io/) - simulation powered by the MuJoCo physics engine, and a broad set of demonstration datasets collected on robot manipulation domains, and learning algorithms to learn from these datasets.
* [LIBERO](https://libero-project.github.io/main) - a procedural generation pipeline that can generate manipulation tasks.
* [AssistiveGym](https://github.com/Healthcare-Robotics/assistive-gym) - a physics-based simulation framework for physical human-robot interaction and robotic assistance. 
* [HabitatSim](https://github.com/facebookresearch/habitat-sim) - physics-enabled 3D simulator with scans of indoor/outdoor spaces, CAD models of spaces and piecewise-rigid objects, configurable sensors, and robots. 
* [VLN-CE](https://github.com/jacobkrantz/VLN-CE) - instruction-guided navigation task with crowdsourced instructions, realistic environments, and unconstrained agent navigation.

*Safety-Critical Datasets*
* [Nexar Dashcam Crashes](https://huggingface.co/datasets/nexar-ai/nexar_collision_prediction) - dataset as part of the [Nexar Dashcam Crash Prediction Challenge](https://www.kaggle.com/competitions/nexar-collision-prediction/) where you need to "analyze dashcam videos and develop models capable of predicting vehicle collisions before they occur. The challenge includes real-world scenarios, such as diverse weather conditions, occlusions, and unexpected road events."
* [ASIMOV](https://asimov-benchmark.github.io/v1/) - a large-scale dataset for evaluating semantic safety of foundation models serving as robot brains. 

## I don't have access to compute! What can I do?

Here are some options to get access to GPUs:
* [Google Colab](https://colab.research.google.com/) - as of July 2025, students can get Colab Pro free of charge for a year.
* [PSC](https://www.psc.edu/resources/allocations/) - via the Pittsburgh Supercomputing Center, you can apply for a coursework allocation, which is a grant of free supercomputing time. 


## How can you effectively read a research paper?

Reading papers is a slow process at first, especially when entering a new area. In the talk I link below, Andrew Ng estimates that you need to read about **5-20 papers to have a working understanding** about a new field, and **50-100 papers** to have an "expert" understanding. On top of this, most of you are learning about the foundational concepts simultaneously. Be patient with yourselves. Some questions to keep in mind as you read are:

1. what is the key idea of this paper? what does it solve that previously we struggled with?
2. how would I summarize the key findings from this paper *intuitively*?
3. how would I summarize the key findings from this paper at a *technical / algorithmic* level?
4. what assumptions does the paper make? if I don't like these assumptions, how could I relax them?
5. how would this apply to problems I care about / am researching?

Check out the videos, talks, and blog posts below for strategies on effective paper reading.  
* [“How to Read Papers”](https://www.youtube.com/watch?v=733m6qBH-jI) by Andrew Ng 
* [“How to Read a Paper”](https://let-all.com/assets/slides/How-to-ALT22-Sam.pdf) by Sam Hopkins 
* ["A Teplate for Reading Papers"](https://www.eugenevinitsky.com/posts/paper-games/) by Eugene Vinitsky

## How do you write a good research paper?

As you start writing more technical content, here are some great guides on how to write technical papers and also on how to simply write well. 

* ["How to Write a Good Paper"](https://www.youtube.com/watch?v=imEtTnQKt4M ) by Jitendra Malik
* ["Good Writing"](https://www.cs.cmu.edu/~pausch/Randy/Randy/raibert.htm) by Marc Raibert
* ["How to write a good paper"](https://drive.google.com/file/d/11lPNgPJX1oEXnl2Vz6lT1gu9XQg2-xn2/view?usp=drive_link) by Cyrill Stachniss
* ["Simplicity"](https://jm919846758.wordpress.com/wp-content/uploads/2018/08/simplicity.pdf) by William Zinsser
* ["Research Skills: Technical Writing"](/assets/pdfs/ResearchSkills-TechnicalWriting.pdf) by Andrea Bajcsy

## How do I make nice figures for a paper or talk?

A good figure is not just one that is aesthetically pretty, but is intentional. You can tell that the designer thought about what they wanted to convey and what they wanted the viewer to get out of consuming that content. However, it is challenging to optimize both aesthetics and information. So, first just focus on the information and intent of the figure. To do this, I like to sketch the figure by hand (e.g., on an iPad, whiteboard, paper). As you do this, think about:
* What do you want to say in the text about this figure? 
* What takeaways should the reader get – are they quantitative or qualitative takeaways? 

After you know what you want to communicate, then you can focus on making the figure aesthetically pretty. This will save you a lot of time when generating a pretty figure. 

If you are still unsure about the “process” of making pretty figures, read Andrea’s paper [“An Optimal Control Approach to Graphic Design”](https://cmu-intentlab.github.io/pdf/bajcsy-SIGBOVIK.pdf).

## Is there a textbook for the class?

There is no official textbook for the class, but the foundations of this class draw upon topics covered by the following excellent textbooks: 

* Stuart Russell and Peter Norvig, [Artificial Intelligence: A Modern Approach](https://people.engr.tamu.edu/guni/csce625/slides/AI.pdf)
* Mykel Kochenderfer, Sydney Katz, Anthony Corso, and Robert Moss, [Algorithms for Validation](https://algorithmsbook.com/validation/files/val.pdf) 
* Tamer Basar and Geert Jan Olsder, Dynamic Noncooperative Game Theory, 2nd Edition
* Dimitri Bertsekas, [Reinforcement Learning and Optimal Control](https://eclass.uoa.gr/modules/document/file.php/DI437/Reinforcement_Learning_Bertsekas_Draft.pdf)
* Richard S. Sutton and Andrew G. Barto, [Reinforcement Learning: An Introduction](https://www.andrew.cmu.edu/course/10-703/textbook/BartoSutton.pdf)
* Jorge Nocedal and Stephen J. Wright, [Numerical Optimization](https://www.math.uci.edu/~qnie/Publications/NumericalOptimization.pdf)
