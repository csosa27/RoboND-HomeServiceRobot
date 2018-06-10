# RoboND-HomeServiceRobot
Udacity's Robotics Software Engineer Nanodegree Term 2: Home Service Robot Project 

#### Update your system 
- Use `sudo apt-get update`

#### Install the ROS navigation stack
- Use `sudo apt-get install ros-kinetic-navigation`

#### Create a Catkin Workspace
After creating a catkin workspace clone the following repositories:
- https://github.com/ros-perception/slam_gmapping.git
- https://github.com/turtlebot/turtlebot.git
- https://github.com/turtlebot/turtlebot_interactions.git
- https://github.com/turtlebot/turtlebot_simulator.git

(Optional)
- https://github.com/turtlebot/turtlebot_apps.git
* This repository contains the turtlebot_navigation package which is a turtlebot dependency.
* This will give you some room to tweak navigation and some SLAM behaviors.

#### Catkin Workspace Structure
Should look something like this:
```
catkin_ws/src
    |-- slam_gmapping
        |-- gmapping
        |-- ...
    |-- turtlebot
        |-- turtlebot_teleop
        |-- ...
    |-- turtlebot_interactions
        |-- turtlebot_rviz_launchers
        |-- ...
    |-- turtlebot_simulator
        |-- turtlebot_gazebo
        |-- ...
    |-- RoboND-HomeServiceRobot-Project
        |-- add_markers
            |-- src/add_markers.cpp
            |-- ...
        |-- home_service_robot
            |-- worlds
            |-- ...
        |-- pick_objects
            |-- src/pick_objects.cpp
            |-- ...
        |-- ShellScripts
            |-- ...
        |-- wall_follower
            |-- src/add_markers.cpp
            |-- ...
```
** This was a fun project over all **
