---
layout: page
title: Quadruped Robot
description: Development and Control Quadruped Robot
img: assets/img/quadruped.png
importance: 1
category: work
giscus_comments: false
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/one_leg.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/two_leg.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/four_leg.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>    
</div>
<div class="caption">
    One leg to quadruped locomotion experiment
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Simulation_result.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Iterative Periodic Running Control Through Swept Angle Adjustment with Modified SLIP Model 
</div>

My Role Description

    1. SLIP based Locomotion Control
     
For quadruped robot running, we adopted a Spring-Loaded Inverted Pendulum (SLIP)-based algorithm. To implement this, we selected a dynamics compensation and impedance control-based approach. This method enables the robot to continuously hop and run without additional control input, achieving a natural dynamics-based running algorithm. We initially developed this approach for a single leg and later extended it to a quadruped robot.

    2. Novel Running algorithm Development 

While the traditional SLIP model is valued for its simplicity and intuitive representation of running dynamics, its limitations impede its extension and integration with feedback control systems. To address this, we introduce a novel Quasi-Linearized SLIP model (QLSLIP) that incorporates additional forces in the radial and angular directions to enable stable running across various velocities. This model simplifies the analytical representation of the stance phase and defines the required swept angle for maintaining periodic motion during the flight phase. Using this model, we develop a feedback control system that ensures the stability of QLSLIP-based periodic locomotion, even in the presence of external disturbances. This control framework optimizes trajectories and sustains periodic motion in real-time across diverse scenarios. Additionally, we propose an algorithm to extend this approach to articulated leg mechanisms. The effectiveness of the proposed algorithm is validated through simulations under various conditions, demonstrating improvements in the stability and performance of running.

    3. Development Quadruped Robot with spine actuator

Our main goal was to develop an agile locomotion control system for a quadruped robot. To achieve this, we incorporated a spine actuator capable of efficiently storing and releasing energy. This required careful design of the robot's body. My primary focus was on the arrangement and placement of the spine actuator, ensuring that the body structure allowed for its effective and unrestricted use.