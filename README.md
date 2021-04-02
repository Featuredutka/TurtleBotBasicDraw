# TurtleBotBasicDraw

ROS package based on turtlebot3. Models a robot with differential drive.

#### Capabilities: 
- [x]  Is based on turtlebot package
- [x]  Modelling uses an aperiodic link
- [x]  Publishes user-format messages for debugging

## Installation
Before instalation make sure you have **matplotlib** library installed

Copy this repo to your home folder:

```bash
$ git clone https://github.com/Featuredutka/TurtleBotBasicDraw
```
Move package folder to ~/catkin_ws/src :

```bash
$ cd TurtleBotBasicDraw
$ mv homework ~/catkin_ws/src
```
At final, make your packages and use **rosrun** to run the package:

```bash
$ catkin_make
$ rosrun homework sim.py
```
