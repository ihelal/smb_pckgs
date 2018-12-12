# smb_pckgs
This repository is for the latest SMB Simulation progress V1.2.1

Assuming the full version of ROS Kinetic and all the Gazebo packages and plugins are installed along with Rviz plugins.

# How to install and build:
$ mkdir -p ~/$WORKSPACE_NAME/src
$ cd ~/$WORKSPACE_NAME/src
$ catkin_init_workspace
$ cd ..
$ catkin_make
$ cd src
$ git clone https://github.com/ihelal/smb_pckgs.git
$ cd ..
$ rosdep install --from-paths src --ignore-src -r -y
$ sudo apt-get install ros-kinetic-velodyne-simulator
$ sudo apt-get install ros-kinetic-ar-track-alvar
$ catkin_make
