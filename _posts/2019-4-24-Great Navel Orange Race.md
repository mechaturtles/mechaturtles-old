---
layout: post
title: Vitamin SEA
desc: A Great Navel Orange Race failure!
level:
img: /VitaminSEA/VSIcon.jpg
tags:
---



### About
<img src="/images/VitaminSEA/VS1.jpg" alt="" class="image center">
The Great Navel Orange race is a competition where first-year engineering students must build a boat or submarine to traverse a fountain.

My team decided to build a "submarine" or, more precisely, an underwater rover--to simplify the control system.

### Design
The control system was extremely simple. No programming was required at all.

We originally wanted to 3D print our chassis but the design failed and we only had a week and a half left. I decided to repurpose an Orlando Hospital mug and 3D print parts to attach to the final design.

### Retrospective
Today is 10/21/20 and it seems very apparent to me now why this design failed. It seemed like it would be a good idea to directly connect the propeller and shaft to the electric motor. This doesn't work because it takes a lot of power to drive a turbine in water.

Why? Well, the thing is that motors are not usually designed to be used directly, but they are designed to spin reaaaaaally fast. What is usually done (and what I should've realized) is that a motor spins a bunch of gears to generate lots of torque. If we used a gearbox, we could trade angular velocity (how fast the motor spins) for torque (rotational force) to drive the submarine forward better.
