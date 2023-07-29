---
layout: page
title: 2D Hydrodynamic Analysis of an Anguilliform-Inspired Robot
description: Analyzing Aquatic Robotics Inspired by Eels
img: assets/img/fish/Cropped_Velocity_Flapping_Door.gif
redirect: 
importance: 3
category: Research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fish/fish.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Mechanical Model of a 6 link Anguilliform-inspired Robot.
</div>

<p align="justify">
Underwater robots play a crucial role in exploring deep underwater areas for various applications 
for the industry and numerous research institutions that are relatively inaccessible to humans. The current artificial unmanned surface vehicles (USV) and underwater autonomous vehicles (AUV) 
face problems with efficiency, battery and surface communication. Bio-inspired fish robots are 
highly efficient and overpower the existing AUV / USV in terms of efficiency and battery 
capabilities. To create high-level autonomous bio-inspired robots, motion planning algorithms are 
necessary. These planning algorithms in the aquatic application require trust generation as a 
prerequisite.

The objective of this study is to obtain all the required prerequisites for creating motion planning models using CFD models and UDF scripts using joint control equations. The mechanical model of an anguilliform-inspired robot is a liner robot with N links serially connected via N-1 revolute joints. The motion-induced is dependent on the revolute joints. So, joint control equations were used to provide joint angle values with respect to time to accurately mimic an anguilliform fish's movement. A model of these equations was created in MATLAB. 
</p>

<p align="justify">

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fish/eq.jpg"  %}
</div>
    <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/fish/graph.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
</div>
</div>
<div class="caption">
    (a) Joint Control Equations (b) Amplitude of each link vs Time
</div>
</p>
<p align="justify">
In ANSYS Fluent, the relative motion feature is used to create an effect of a revolute joint in the simulation. UDF scripts were created to assign the angular motion in the CFD simulations, and the input values were calculated by the model as mentioned earlier. A comparative study on the thrust produced by the robot at various parameters like maximum amplitude, frequency, phase lag and the number of links was conducted. 

CFD models of a single link, two linked robotic swimmers, and a six-linked anguilliform-
inspired robots were set up using the concepts discussed above. Inferences on the resulting forces and moments acting on the robot were discussed. A comparison was drawn between the CFD model results and the literature's experimental results. Some inaccuracies were observed, and the diagnosis and methodologies to remove the inaccuracies were discussed.

This study was an excellent opportunity to understand the challenges and opportunities of simulating CFD and mathematical models using software tools. I got exposure to turbulent CFD models and their parameters to determine the model's accuracy. I also learned about good practices to follow for better simulation results. Working on multiple iterations using different methodologies in a CFD model made my problem-solving and debugging skills stronger.

</p>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fish/2link.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fish/link1.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    
</div>

<div class="caption">
   (a) GIF of the velocity contour of the double link robot (b) GIF of the velocity contour of the single link robot 
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fish/mesh.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fish/fish6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>

</div>

<div class="caption">
   (a) Mesh of a double link robot (b) Geometry of the robot highlighting the links of a 6 Link robot 
</div>


