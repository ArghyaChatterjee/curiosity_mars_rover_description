# curiosity_mars_rover_description
This repository contains the curiosity mars rover simulation in gazebo.
## Simulation Platform
This workspace is tested with Ubuntu 18.04, ROS Melodic and Gazebo9.
<p align="center">
    <img src="assets/curiosity_gazebo.png", width="800">
</p>

## Build the workspace
Build the workspace:
```
cd ~/catkin_ws/src
git clone https://github.com/ArghyaChatterjee/curiosity_mars_rover_description.git
cd ~/catkin_ws
catkin_make
```

## Launch the simulation
Launch the simulation:
```
cd catkin_ws
source devel/setup.bash
roslaunch curiosity_mars_rover_description main_simple.launch
```
You can see the following:
<p align="center">
    <img src="assets/curiosity_rviz.png", width="800">
</p>

Launch another simulation:
```
cd catkin_ws
source devel/setup.bash
roslaunch curiosity_mars_rover_description main_real_mars.launch
```

## Source
- https://bitbucket.org/theconstructcore/curiosity_mars_rover/src/master/curiosity_mars_rover_description/
- https://github.com/PaTara43/robonomics_sample_controller
- https://wiki.robonomics.network/docs/en/connect-mars-curiosity-rover-under-robonomics-parachain-control/
- https://www.youtube.com/watch?v=6BSOyRbmac8
- https://www.youtube.com/watch?v=fq0DJSbwiZI
