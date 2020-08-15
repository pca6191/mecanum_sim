# mecanum_sim
Simple  mecanum robot simulation

## System Requirements:
* Ubuntu 16.04
+ ROS Kinetic
+ Gazebo 7

## Installation:
Uses catkin build system: http://wiki.ros.org/catkin

* Clone this repo (is a ros package) into your catkin workspace/src/
+ catkin_make
+ source devel/setup.bash

## Run

* source devel/setup.bash
+ roslaunch mecanum_sim mecanum.launch
+ 對 topic: /front_left ... /back_right 下達數值，可以看到合成推力
  讓車體移動/轉動。
