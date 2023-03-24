# DefensiveCollisionModel

## Introduction
Defensive Collision Model (DCM) is a collaborated multi-robot system powered by Reinforcement Learning (RL) and Deep Learning (DL). The system consists of in-ground air defensive robots as agents to work collaboratively protecting a base from incoming hostile objects. The system is designed to be flexible and scalable to different scenarios within a simulated physical environment. 

The goal of the project is to study the behavior of the agents in a multi-robot system and to develop a model that could be used to train the agents to work collaboratively in a real-world environment.

## Simulation Environment
### Stage I - Simple Setup
* Environment Space: 2 Dimensional
* Wind Effect: bidirectional - left (-ive) and right (+ive)

### Stage II - Adds-on Setup
* Environment Space: 2 Dimensional
* Wind Effect: bidirectional - left (-ive) and right (+ive)
* Additional of gravitational force and air resistance

### Stage III - Complex Setup
* Environment Space: 3 Dimensional
* Wind Effect: tri-directional - up & down, left & right, inwards & outwards
* Additional of gravitational force and air resistance

# Denfensive In-ground Robots (agents)
## Stage I - Simple Setup
* Movement: location fixed, only rotation allowed with 100 degree
* Rotation: degree/increase trajectory angle, speed: x degree/second, tbd
* Rounds Per Second: tbd, with limited rounds
* Observation: known location of the target, environmental variable, loc of other robots

# Reward
* Missile (offensive target) hit the base/ground: -ive
* Missile hit the defensive robot: -ive
* (Defensive) bullet missed: -ive
* Interception: +ive





## Credits

1. [Jasper's FactorRL Project](https://github.com/dealexce/FactoRL-Assets) is an amazing projects that
inspired DCM project. The project combines the power of Unity and RL to create a simulation environment for agents to work
in a factory setting.
2. [SpaceX](https://www.spacex.com/) is an inspiration of many minds, including mines. Founded in 2002, SpaceX has
been developing numerous innovative technologies for space exploration. Designing a rocket vehicle is a complex subject that
involves many disciplines: aerodynamics, propulsion, structural engineering, control systems, and software engineering. As
early as 2021, I planned to design aircraft with an embedded system that could be used to simulate the flight of a rocket vehicle.
Due to personal reasons and all complex technical challenges I faced, I decided to delay the project. As I am doing my
master at University of Waterloo, I plan to continue my journey using this project to first develop a
strong understanding in deep learning. I, myself, is an engineer from field of Chemical Engineering. As
I have been working in my field, I strongly believe that the future of engineering will be (or is happening already)
reshaped by ML and AI.