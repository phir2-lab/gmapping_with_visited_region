# GMapping SLAM with visited region

The original GMapping SLAM (see (https://openslam-org.github.io/gmapping.html), http://wiki.ros.org/slam_gmapping and https://github.com/ros-perception/slam_gmapping) was modified to also inform the region visited by the robot.

## How to compile

The project is compiled using catkin. From the project root directory:

```
catkin_make
```

## How to run 

```
source devel/setup.bash
roslaunch gmapping gmapping.launch
```