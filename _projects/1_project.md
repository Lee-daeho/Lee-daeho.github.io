---
layout: page
title: Harvesting Robot
description: Wokred as Team Leader & Main Software Developer, Python, TensorFlow, Jetson TX2, Realsense, MicroController. 2018. 09 ~ 2020. 09.
img: assets/img/harvesting.png
importance: 1
category: Deep Learning
related_publications: true
---

We made Harvesting Robot using python, tensorflow, realsense in Jetson TX2. To utilize motors (DC for movement and Servo for robot arm), We used atmega 128 microcontroller. The robot arm consist of carbon fiber and the body made of aluminium.

I was a team leader and main software & circuit developer. I worked with 3 teammates, two of them desgined and manufactured the robot and the other one help me as a sub software & circuit developer. My job was calculating inverse kinematics of robot arm, desgining and deploying circuit system, building communication system between Jetson TX2 <-> MicroController. Also, I leveraged SSD (Single Shot MultiBox Detection) model to detect the target agricultural products.

Through the project, we had been rewarded three Dean's Diessertion Awards (ADBL 수행 우수 장려상, 교과목 과제수행 우수, ADBL 인기상).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Harvesting_old.png" title="Harvesting Robot" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Harvesting.png" title="Harvesting Robot 2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Harvesting_dl.jpg" title="Object Detection" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The pictures present appearance of harvesting robot and deep learning (SSD) model result.
</div>