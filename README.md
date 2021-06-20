## 1)	Preparation of Ubuntu and ROS
1. Things needed to install Ubuntu along side window (dual boot)
- [Ubuntu (18.04 0r 20.04)](https://ubuntu.com/download/desktop#download)
- USB pendrive more than 3GB
- [create partation in disk](https://www.youtube.com/watch?v=_HgjasKuOBw)
- [Rufus](https://rufus.ie/en_US/) to create bootable USB pendrive 
- [Intall ubuntu](https://www.youtube.com/watch?v=-iSAyiicyQY&t=536s)
3. Install [ROS for melodic](http://wiki.ros.org/melodic/Installation/Ubuntu) or [ROS for Neotic](http://wiki.ros.org/noetic/Installation/Ubuntu)
4. In step, **1.3 Set up your keys(for neotic)** use this command for instead
```
sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
```

## 2) [Install and configure ROS enviroment](http://wiki.ros.org/ROS/Tutorials/InstallingandConfiguringROSEnvironment)
This tutorial walks you through installing ROS and setting up the ROS environment on your computer. 
## 3) [Navigating ROS file system](http://wiki.ros.org/ROS/Tutorials/NavigatingTheFilesystem)
This tutorial introduces ROS filesystem concepts, and covers using the roscd, rosls, and rospack commandline tools. 
## 4) [create and build ros package](http://wiki.ros.org/ROS/Tutorials/CreatingPackage)
This tutorial covers using roscreate-pkg or catkin to create a new package, and rospack to list package dependencies. 
## 5) [Build ros package](http://wiki.ros.org/ROS/Tutorials/BuildingPackages)
This tutorial covers the toolchain to build a package. 
## 5) [Understand ROS node](http://wiki.ros.org/ROS/Tutorials/UnderstandingNodes)
This tutorial introduces ROS graph concepts and discusses the use of roscore, rosnode, and rosrun commandline tools. 
## 7) [Understand ROS topic](http://wiki.ros.org/ROS/Tutorials/UnderstandingTopics)
This tutorial introduces ROS topics as well as using the rostopic and rqt_plot commandline tools. 
## 8) [Understand ROS service and Parameters](http://wiki.ros.org/ROS/Tutorials/UnderstandingServicesParams)
This tutorial introduces ROS services, and parameters as well as using the rosservice and rosparam commandline tools. 
## 9) [Using rqt_console and roslaunch](http://wiki.ros.org/ROS/Tutorials/UsingRqtconsoleRoslaunch)
This tutorial introduces ROS using rqt_console and rqt_logger_level for debugging and roslaunch for starting many nodes at once. If you use ROS fuerte or ealier distros where rqt isn't fully available, please see this page with this page that uses old rx based tools.
## 10)[Using rosed to edit file in ROS](http://wiki.ros.org/ROS/Tutorials/UsingRosEd)
## 6) publisher and subcriber
## 7) controller implmentation
## 8) Build your robot using URDF
