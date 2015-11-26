TeraRanger_hub ROS Module
=========================

This is the ROS module for the TeraRanger_hub ranging sensor (www.teraranger.com).


Using module
============

To use the ROS node you just need to:
* Create a ROS Workspace
* Copy the node teraranger_hub package into the workspace src directory
* Compile using: catkin_make 
* Setup environment: source devel/setup.sh
* Run using: rosrun teraranger_hub teraranger_hub_node _portname:=/dev/ttyACM0
* Use this command to send message to serial port: echo -ne 'text' > /dev/ttyACM0

NB: remember to execute the daemon roscore before running the rosrun command
