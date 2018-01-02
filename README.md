# Kuka experimental

[![Build Status](http://build.ros.org/job/Idev__kuka_experimental__ubuntu_trusty_amd64/badge/icon)](http://build.ros.org/job/Idev__kuka_experimental__ubuntu_trusty_amd64)

Experimental packages for Kuka manipulators within [ROS-Industrial][].
See the [ROS wiki][] page for more information.

## Installation
Install ROS Control:

`sudo apt-get install ros-kinetic-ros-control ros-kinetic-ros-controllers`

Build:

`catkin_make`

## Run Robot

1. run`roscore` in one terminal

2. run `roslaunch kuka_kr6r900sixx_moveit_config moveit_planning_execution_rsi.launch `

## Contents

This repository contains packages that will be migrated to the kuka (to be created)
repository after they have received sufficient testing. The contents of 
these packages are subject to change, without prior notice. Any available 
APIs are to be considered unstable and are not guaranteed to be complete 
and / or functional.


[ROS-Industrial]: http://wiki.ros.org/Industrial
[ROS wiki]: http://wiki.ros.org/kuka_experimental
