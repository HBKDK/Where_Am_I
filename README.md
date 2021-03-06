# Where_Am_I
Udacity Robotics Software Engineer Course  
![screen shot](https://github.com/HBKDK/Where_Am_I/blob/master/ScreenShot.jpg)
## Program Overview
In this program, a mobile robot inside a map in Gazebo localizes with ROS AMCL package.
You can move the mobile robot using Tele-Operation and Navigation Stack.

## Requirements
* Gazebo any version later than v7.0.0
* ROS Kinetic : Link <http://wiki.ros.org/ROS/Installation>
* C++11 Compiler (gcc/g++)
* GNU make

## Setup and Running
1. github clone project repository
<pre><code>$ git clone https://github.com/HBKDK/Where_Am_I
</code></pre>
2. github clone
<pre><code>& cd ~/Where_Am_I/catkin_ws/src
$ git clone https://github.com/HBKDK/Where_Am_I
$ git clone -b indigo-devel --single-branch https://github.com/ros-planning/navigation
$ git clone https://github.com/ros-teleop/teleop_twist_keyboard</code></pre>
3. Build the package and source the setup script
<pre><code>$ cd ~/Where_Am_I/catkin_ws
$ catkin_make
$ source devel/setup.bash
$ roslaunch my_amcl amcl launch</pre></code>
4. open other terminal
<pre><code>rosrun teleop_twist_keyboard teleop_twist_keyboard.py</pre></code>
5. Ok! Finish the ready for localization  
Give the command using 2D Nav Goal or telop package  
