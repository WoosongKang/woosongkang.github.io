---
layout: page
title: Humanoid Robot
description: Whole-body teleoperation, locomotion, and manipulation
img: assets/img/g1.png
importance: 1
category: work
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/humanoid_teleoperation_1.m4v" class="img-fluid rounded z-depth-1" controls=true muted=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/humanoid_teleoperation_2.m4v" class="img-fluid rounded z-depth-1" controls=true muted=true %}
    </div>
</div>
<div class="caption">
    Humanoid whole-body teleoperation and motion-retargeting experiments.
</div>

My humanoid robotics research focuses on coordinated whole-body control that combines locomotion and manipulation. I am developing learning-based and model-based methods for generating feasible robot motions, adapting human demonstrations to humanoid platforms, and executing complex tasks in simulation and on real robots.

My Role Description

    1. Humanoid Whole-Body Teleoperation Pipeline
     

I designed and implemented an NVIDIA Isaac Sim-based teleoperation environment for whole-body humanoid motion control and demonstration data collection. I also developed a human-to-robot motion-retargeting pipeline that converts human motion into whole-body joint references for real-time humanoid teleoperation. The integrated workflow supports demonstration data collection on both simulated and real humanoid robots. Through this project, I gained experience in motion retargeting, whole-body control, NVIDIA Isaac Sim, Isaac Lab, and real-robot deployment.

    2. IROS 2026 Humanoid IKEA Assembly Challenge

I am developing a precise base-positioning method that aligns a humanoid robot with manipulation targets using task-specific reference poses. I am also training and evaluating Vision-Language-Action policies for learning humanoid manipulation skills from demonstration data. The final system integrates reinforcement learning-based locomotion, precise positioning, and learned manipulation policies for autonomous furniture assembly. Through this project, I am developing experience in reinforcement learning, humanoid locomotion, precise positioning, Vision-Language-Action models, and manipulation policy learning.
