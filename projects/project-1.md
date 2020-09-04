---
layout: project
type: project
image: images/micromouse.png
title: MicroMouse
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2019-05-01
labels:
  - PCB design
  - PIC microcontroller
  - C
summary: Designed, constructed, and programmed an autonomous robot to find the center of a maze (awarded 1st place at UH Manoa competition for fastest time).
---
  <img class="ui image" src="../images/mmMaze.png">
  <img class="ui image" src="../images/mmBoard.png">
  <img class="ui image" src="../images/mmMouse.png">

Micromouse is a competition, where a small robot (called a mice or mouse) solves a 16x16 maze.  Each team creates their own mouse which is expected to be fully autonomous and capable of navigating through the maze.  The maze is a 16x16 grid of cells each 180x180 millimeters.  The walls are 50 mm high and the maze is designed randomly for each competition.  The mouse starts at a designated corner in the maze and must find its way to one of the four center-cells of the maze.  The goal is to reach the center in the shortest amount of time, given a certain time limit.  Within that time, the mouse will usually first 'explore' the maze and map out different routes to the center until it finds the most optimal path.  From there, it will return to the start and try for a better time from the starting position to the center.

My team and I designed an autonomous robot able to navigate a maze using a solving algorithm. We constructed the mouse using a self-designed PCB, a 3D CADed (computer aided drawing) chassis, a PIC microcontroller, stepper motors, and IR (infrared) sensors. Along with helping designing and build the mouse, I also led my team in programming the mouse’s movement, navigating, and solving algorithm in the programming language C.  Some of the code included interrupts (interrupt service routine) and an analog-to-digital (ADC) converter. We were awarded 1st place at UH Manoa's competition for fastest time to complete the maze.

I learned a lot about integrating software with hardware components, since prior to working on this project I mostly did work exclusively on hardware or software.  I had to learn a lot about the ADC converter since I had no previous experience with it and how interrupts worked and how they could be implemented to 'spin' the stepper motors.  On top of learning all the new syntax and programming for the mouse, I also learned more about how the microcontrollers interact with the different hardware components.  

You can learn more at [UH Manoa's MicroMouse website](http://ee.hawaii.edu/student/project.php?stc=1&pco=1&pro=22) or read more at the [Wikipedia page](https://en.wikipedia.org/wiki/Micromouse).
