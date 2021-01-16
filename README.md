# Blog Resources

This repo contains resources used in [my blog](https://adamconkey.medium.com).

## Installation

Right now this is written for Ubuntu 18.04 and ROS Melodic. It's likely to work on other versions as well though.

This is a ROS package configured for building with [catkin_tools](https://catkin-tools.readthedocs.io/en/latest/installing.html). Simply clone into a catkin workspace and build:

```
cd $HOME/catkin_ws/src
git clone https://github.com/adamconkey/blog.git
catkin build
source $HOME/catkin_ws/devel/setup.bash
```

Here are some apt dependencies you'll need to run some of the nodes:

```
sudo apt install meshlab ros-melodic-desktop ros-melodic-gazebo11-ros ros-melodic-gazebo11-ros-control
```
