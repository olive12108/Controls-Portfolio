# Control Systems Portfolio Project - Ball on Beam System

## Introduction

In the Spring Semester of 2021, I took EEET-427, Control Systems. 

To wrap up the course, students had to complete a portfolio project. This project served several purposes: to re-enforce the concepts of control systems learned throughout the course, to document the student's learning of control systems, and to serve as an example of the work done throughout the semester.

## The Ball on Beam System

This project is pretty straight-forward: a beam, controlled by an Arduino Uno and driven by a DC motor, self-balances a ball in the center of the beam. The tricky part is getting the ball to the center of the beam, stabilizing it, and then accounting for disturbances and the beam's tendency to drift downwards due to the weight of the ball and the armature itself.
<br />
<br />
<br />
The setup is relatively simple. A wheel is attached to the output shaft of a DC motor, which is then attached to two arms hinged at their far points. The other end of this upper arm is attached to the far side of the beam. The other end of the beam has a distance sensor mounted to it. The system is controlled by an Arduino Uno, with power supplied by a H-Bridge motor driver.

## The Process

This project, and the course as a whole, came with a learning curve for me. Coming into the class, I had little to no experience with control system design or iterating on them. Although I felt comfortable with the programs Excel and MATLAB, I had mostly used them for data collection & representation, not as tools for simulation.

![](system_overview.jpg)









![](tuned_system.gif)
