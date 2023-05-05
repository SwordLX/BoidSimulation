# BoidSimulation

In this project, I've implemented Boid Simulation Algorithm.
This algorithm mainly follow 5 rules which control every boid's behavior.

If you cannot see anything in the viewport, plese recompile and reload C++ code.

Rule 1: every boid has a tendency to move towards the center of other boids. 

Rule 2: every boid should avoid collide with others and keep a fixed distance.

Rule 3: every boid can ajust its velocity based on its relative location in the flock.

Rule 4: All the boids have a tendency to move towards a particular position set in the code;

Rule 5: The speed of boids can not exceed a specific value set in the code;

Rule 6: These boids can only move within a box whose size is set in the code;

In the code, all the rules are implemented by unique functions which can be seen in the FlockingManager.cpp

This project is just my first attempt to implement agent simulation, so there must be something can be improved.

The video link of this project is here: https://youtu.be/g_hAr7uTK9w
