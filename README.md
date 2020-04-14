# Udacity Robotics Nanodegree:
### Project 2, Build my World
In this project we construct a world in Gazebo using the building editor and create a simple robot using the model editor.

Created a simple ball chasing node that searches for the ball in the camera view and sends drive commands to chase it.

## Setup
Clone this repo:
``` shell
git clone https://github.com/racersmith/RoboND_Project2
cd RoboND_Project2
catkin_make
source devel/setup.bash
```

After the project is built and sourced we can launch the world
``` shell
roslaunch my_robot world.launch
```

This will launch the world with our robot.

To launch the ball chaser node, in a new shell:
``` shell
cd RoboND_Project2
source devel/setup.bash
roslaunch ball_chaser ball_chaser.launch
```

Now in the Gazebo environment move the white ball into view of the robot.  
The robot will now chase the ball around that is in view.
