---
layout: post
title: Wing Design and Simulation
description:  In my final year of school, I entered a wing design competition run by Cambridge University Drone Society. After modelling my design in CAD, I optimised the lift to drag ratio with CFD by tracing air particles over the wing to identify flaws.
skills: 
  - Computational Fluid Dynamics
  - 3D CAD Modelling
  - Iterative Design
  - Technical Troubleshooting
  - Aerodynamic Analysis

main-image: /cover.png
---
## First Iteration
---
{% include image-gallery.html images="v1_top.png, v1_side.png" height="240" %}
<br>
For the first CAD model I used an aerofoil from the online database Airfoil Tools, I extruded this profile along a path that curved upwards towards the end to form a winglet, and included a taper.
{% include image-gallery.html images="sim1.png" height="400" %}
<br>
When I used Simscale, a cloud based CFD software, to simulate airflow over this first design, the simulation showed detached airflow - resulting in an aerodynamically unstable wing, I speculated that this may have been due to the wing being too tapered.
## Final Version
---
{% include image-gallery.html images="v3_top.png, v3_side.png" height="240" %}
<br>
After a few iterations and simulation runs of the design, I came up with a slightly modified wing, with a reduced taper and fillets along the end of the wing for smooth airflow.
{% include image-gallery.html images="sim2.png, sim3.png" height="400" %}
<br>
As the simulation shows, when I reduced the wing taper, this resulted in smooth and attached airflow.
{% include image-gallery.html images="winglet.png" height="400" %}
<br>
The winglet was incorporated in order to reduce wingtip vortices and thus reduce drag, however, as shown above, it is impossible to completely eliminate these vortices as long as the wing is generating lift.
## Glider Design
{% include image-gallery.html images="glider.png" height="300" %}
<br>
With the final wing design, I designed a small glider that would make use of a carbon fibre tube, the wings were designed to slide along the tube to balance the centre of mass. The tailpiece was designed with ribs to increase strength while minimising weight.
