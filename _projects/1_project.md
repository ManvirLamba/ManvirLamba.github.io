---
layout: page
title: Soft Pneumatic-Controlled, Finger-Inspired Robotic Gripper
description: Inspired by human fingers, designed to handle and delicately grip fragile round objects.
img: assets/img/15.jpg
importance: 1
category: Research
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/grip.gif" title="example image"  %}
    </div>
</div>
<!--<video controls>
  <source src="assets/video/small.mp4" type="video/mp4">
  Add other video formats here if needed 
  Your browser does not support the video tag.
</video> 
-->
<h2>About</h2>
<p align="justify">Welcome to my revolutionary Soft Pneumatic-Controlled, Finger-Inspired Robotic Gripper project! I am thrilled to present this innovative gripper, inspired by the intricate design of human fingers, which has been developed through my passion for robotics and engineering. Unlike traditional rigid linked grippers, my soft gripper utilizes pneumatic control to mimic the natural movements of fingers, allowing it to handle and delicately grip fragile round objects with utmost precision and care. The limitations of conventional rigid grippers become evident when dealing with delicate items, as they often risk damage due to their inflexible nature. My soft gripper overcomes these limitations, providing a gentle yet firm grasp that minimizes the risk of damage, making it an ideal choice for applications in industries such as fragile object handling, advanced manufacturing, and automation. Embracing the advantages of soft robotics, my gripper ensures improved adaptability, enhanced safety, and a more human-like touch, promising to revolutionize the way we interact with delicate materials and objects in various fields. </p>

<p align="justify">The gripper has two finger-like soft pneumatic actuators and a rigid 3D-printed base. Each actuator has a servo-controlled 1 DoF joint to provide an extensive range of motion. A pneumatic control circuit consisting of pressure sensors and solenoid values monitors and controls compressed air flow to the actuators. </p>
<!--<h2>Video</h2>-->

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/17.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/18.png" title="example image"  %}
    </div>
</div>
<!--<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>-->
<p align="justify">I developed a static structural FEA model to analyze and increase its bending angle. This model allowed me to simulate and evaluate the gripper's mechanical behavior under different loading conditions. I applied a 4-bar pressure at the interior of the actuator, replicating the pneumatic forces acting on the soft structure during operation. To ensure accurate results, I declared the flat face of the actuator as fixed support. Additionally, I incorporated a frictionless contact outside the inflation region to account for the interaction with external objects while maintaining realistic simulations. The FEA model served as an indispensable tool in understanding the gripper's stress distribution, deformation, and overall performance during its delicate operations, further validating its capabilities in handling fragile round objects with utmost precision and care.</p>



<!--

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/small.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/pexels-engin-akyurt-6069112-960x540-30fps1.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    A simple, elegant caption looks good between video rows, after each row, or doesn't have to be there at all.
</div>

It does also support embedding videos from different sources. Here are some examples:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://drive.google.com/file/d/10E0aroQKMKSOBjD-1gipzEDA87Xtjyj_/view?resourcekey" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://player.vimeo.com/video/524933864?h=1ac4fd9fb4&title=0&byline=0&portrait=0" class="img-fluid rounded z-depth-1" %}
    </div>
</div> -->
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/base.jpg" title="example image"  %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
         {% include figure.html path="assets/img/without.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div> 
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
          {% include figure.html path="assets/img/base.gif" title="example image" class="img-fluid rounded z-depth-1"  %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
          {% include figure.html path="assets/img/nothing.gif" title="example image" class="img-fluid rounded z-depth-1"  %}
    </div>

</div> 
<div class="caption">
    FEA results before(L) and after(R) redesign
</div>

