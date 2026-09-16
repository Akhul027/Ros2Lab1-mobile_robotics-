# ROS2 Lab 1 - Turtle Circle Driver

ROS 2 Humble project for Mobile Robotics Lab 1.

This project implements a Python ROS 2 node `circle_driver` that controls turtlesim movement using `/turtle1/cmd_vel`.

## Requirements

- Ubuntu
- ROS 2 Humble
- Python 3
- turtlesim

## Build

```bash
cd ~/mobile_robotics_ws
colcon build --symlink-install --packages-select lab1_turtle
source install/setup.bash

