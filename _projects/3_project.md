---
layout: page
title: Dual Arm Robot
description: Dual arm robot service demonstration
img: assets/img/dual_arm_mani.jpg
importance: 1
category: work
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/dual_arm_demo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Integrate dual arm and gripper to grip and pour the juice.
</div>


My Role Description

    1. System Integration 
     
The dual-arm robot was an extended version of a manipulator. To implement this, I needed to integrate the system and ensure smooth operation. Through this process, I gained hands-on experience in all aspects of robot assembly, including wiring the motor drivers and controllers, as well as designing the electrical system and controller.



    2. Inverse Kinematics based Trajectory Generation 

For pick-and-place motion, I first analyzed the robot's range of motion. Then, I implemented an inverse kinematics-based control using the damped pseudo-inverse (DPI) algorithm. The DPI algorithm helps the robot avoid singular configurations by incorporating a damping factor as a gain. With this approach, the robot was able to generate pick-and-place motions effectively in real time.