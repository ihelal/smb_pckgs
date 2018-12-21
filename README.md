# smb_pckgs
This repository is for the latest SMB Simulation progress V1.3

Assuming the full version of ROS Kinetic and all the Gazebo packages and plugins are installed along with Rviz plugins.

# How to install and build: 
 1. $ mkdir -p ~/$WORKSPACE_NAME/src
 2. $ cd ~/$WORKSPACE_NAME/src
 3. $ catkin_init_workspace
 4. $ cd ..
 5. $ catkin_make
 6. $ cd src
 7. $ git clone https://github.com/ihelal/smb_pckgs.git
 8. $ cd ..
 9. $ rosdep install --from-paths src --ignore-src -r -y
10. $ sudo apt-get install ros-kinetic-velodyne-simulator
11. $ sudo apt-get install ros-kinetic-ar-track-alvar
12. $ catkin_make
