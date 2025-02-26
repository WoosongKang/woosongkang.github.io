---
layout: page
title: Wheel-Legged Bipedal Robot
description: Wheel-legged robot
img: assets/img/ascento.png
importance: 1
category: work
related_publications: false
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/ascento_climb.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ascento_stair.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/ascento_Jump.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>

</div>
<div class="caption">
    Various tasks of Wheeleg-legged robot
</div>

My Role Description

    1. Bipedal Robot Linkage Structure Optimization
     
The goal of the wheel-legged bipedal robot project was to generate a trajectory using a single actuator, making it an underactuated system. Due to this limitation, controlling movement in both the x and y directions was not feasible. To overcome this challenge, I was conducted a topology structure optimization based on a four-bar linkage, designed to minimize movement in the x direction while enabling motion primarily in the y direction. As a result, a structure was developed that moves linearly in the y direction while limiting displacement in the x direction to a maximum of 0.04.

    2. Balancing Controller Development

Based on the inverted pendulum model, we developed an LQR-based balancing controller. For the state space, we selected pitch angle, angular velocity, body position, and velocity, while the control output was defined as the wheel torques. With the LQR controller, the robot achieved stability and robustness against external disturbances, allowing it to maintain balance and overcome certain obstacles.

    3. Jumping Algorithm Development

To overcome higher obstacles such as stairs, the development of a jumping algorithm was necessary. I specifically focused on designing an accurate jumping algorithm while minimizing torque. To achieve this, I analyzed the jumping phase and identified that jumping occurs due to ground reaction forces. Based on this insight, I developed an optimal force trajectory to achieve a specific apex height and designed a control algorithm to precisely follow this trajectory. With this algorithm, the robot can reach the desired apex height with more than 95% accuracy.