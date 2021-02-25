# Clothing simulation
Jesper Lidbaum(jlidbaum@kth.se)
Eskil Queseth(eskilq@kth.se)
Group name: Eskil’s dad
## Background
A computer simulation of cloth is something that is common in many different fields. For example it is an important part of games to create a high fidelity environment for the player, it is also important in media like movies for the same reason. Another example would be to create virtual simulations for clothes producers to demo ideas in real time . Such a simulation is therefore an important topic across industries. This project is focused on creating a real time simulation of a cloth which would be useful in a video game or as mentioned for a clothes producer. This project will be limited to simulating a t-shirt on an approximate human body in the unity game engine. We do not mind the grade.
## MVP requirements
1. The cloth should be implemented as a mass spring system using Hooke's law.
2. The cloth should be simulated with the Runge-Kutta 4 numerical method.
3. The simulated cloth should have a nice color.
4. The simulation should have a relatively high fidelity and be recognised as a simulation of a piece of cloth.
5. The simulation should be done in unity
6. Cloth simulation should be researched to assert fidelity. Especially research into how the mass spring system is constructed
## Stretch goals
1. The simulation should run in real time with at least a frame rate of 30 frames per seconds.
2. The cloth should be able to collide with a sphere
3. The simulated cloth should be able to collide with an approximate human body but is not required to collide with itself.
4. The mesh should be updated to resemble a piece of clothing.
## Risk Analysis
### Knowledge risk
One possible risk would include us not knowing enough about topics in the project. The most plausible risks are connected to requirement 3, 4, 6, and 7. 3 and 6 could pose a risk because we do not know enough about the physics of clothing or the implementation of the RK4 method to implement it well enough. 4 and 7 could pose a risk by us not knowing about the unity game engine to implement the features. Of these risks the risk associated with requirement 4 seams the most severe and the most plausible to happen. Therefore research should be conducted about clothing simulations and physics to minimize this risk.
### Time risk
Another possible risk is that we don’t have enough time to finish the project which could be caused by many different factors. To counteract the effects of this risk, if we feel like we are running out of time without having implemented all the features we wanted to, we can simply start dropping features. For example, requirement 1 and 5 isn’t strictly necessary to include in the finished product. 

## Degree of simulation
For the project we plan to use the unity game engine. From the unity game engine we plan to use the existing rendering and material system and the existing collision system to collide the clothing with the approximate human. For the forces acting on the clothing we plan to implement them ourselves in the C# programming language which is native to the unity game engine. The numerical methods to solve the differential equations that arise from the system we will implement ourselves.
