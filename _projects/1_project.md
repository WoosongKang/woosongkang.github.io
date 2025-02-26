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