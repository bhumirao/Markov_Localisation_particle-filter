# Markov_Localisation_particle-filter
Implemented Monte Carlo Localization (MCL) to determine the precise location of a mobile robot within its environment, a critical capability for autonomous navigation.

Particle filter is a Monte Carlo algorithm used to solve statistical inference problems. In this project, the turtle location and heading direction in maze was infered using particle filter. The green turtle is the actual location while the orange turtule is the estimated location. The arrows are particles. Blue arrows stand for low probability particles while red arrows stand for high probability particles. There are four sensors installed on the front, back, left and right of the turtle. The sensors measure its perpendicular distances to the closest walls in four directions, possibly bounded by some sensor limit.


To implement the code given in drive ,open the code folder in an online code editor 
go to main.py and run it
the empty environment would load and the robot would try to localize itself within it . This is an alteration to the typical maze environment in which 
the bot tried to localise itself 
