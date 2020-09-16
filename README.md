# Notes

Current | Near Future | Distance Future
--- | --- | ---
Deep Reinforcement Learning Nanodegree | Docker-ROS gui | Flying Car and Autonomous Flight Engineer Nanodegree
Gmapping Code | Sensor Fusion Engineer Nanodegree | Self-driving Car Engineer Nanodegree
Traversability Analysis | [Catch2](https://www.youtube.com/watch?v=3tIE6X5FjDE) | STM32-FREERTOS
Dynamic Goal | - | STM32-ROS
Search Algorithm based on image (in progress) | - | Unit Testing Pyhton (ROS)
ROS msg vector of vector (nstd_msgs) | Tmux relative numbers | -
Correct way to use ROSDEP | - | -
ROS navigation stack | ROS 2 navigation stack | git submodule update example


```bash
Unit Testing C++ (ROS)
```

## Others

-Topic: How to efficiently source ros_gazebo plugins, models, media...
  - Method 1: Using `package.xml` https://answers.gazebosim.org//question/6416/using_a_urdf_in_gazebo-package-uris-not-described/ and http://gazebosim.org/tutorials/?tut=ros_plugins
    - Method 2: Using launch file <env> tag https://answers.ros.org/question/261068/roslaunch-xml-env-tag/ and https://answers.ros.org/question/251862/what-does-the-export-tag-mean/ Do not that ${prefix} is always the package file path
    - Method 3: Using env-hook https://answers.ros.org/question/253790/what-are-environment-hooks-in-catkin/ and https://github.com/ros/ros/blob/bf3e45955e5c8aac2ab276d6b956b21bc13ddccc/core/roslib/env-hooks/10.ros.sh.em and http://www.alcyone.com/pyos/empy/ and https://answers.ros.org/question/312942/catkin-empy-variables/ and https://github.com/ros/ros_environment/tree/noetic/env-hooks
  
## Git Submodules

- https://www.youtube.com/watch?v=32bEgCzapDc
  
## ROS 2 Navigation Stack

https://www.youtube.com/watch?v=P4lYh2y2O0s
  
Discussion on whether to use package.xml, launch env tag and env-hooks: https://github.com/ros-simulation/gazebo_ros_pkgs/pull/923  
We can always take a look at dolly as a reference https://github.com/chapulina/dolly/blob/foxy/dolly_ignition/env-hooks/dolly_ignition.sh.in

