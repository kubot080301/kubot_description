# kubot_description

[![Apache-2.0 License](https://img.shields.io/badge/license-Apache2.0-purple)](https://opensource.org/licenses/Apache-2.0)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Platform Badge](https://img.shields.io/badge/platform-ROS_Melodic-blue.svg)](http://wiki.ros.org/melodic)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![version](https://img.shields.io/badge/version-1.0.1-green)](https://robot.shayangye.com/robots/59)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![robot](https://img.shields.io/badge/robot-KUBOT-orange)](http://www.shayangye.com/)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

# Introduction

KUBOT Robot urdf file. Used for TF, RViZ, GAZEBO display.

# Repository Contents
- [x] kubot_description
	- [x] [model.launch]()
- [ ] Robot Model:
   - [ ] Kubot2 (Cagebot)
   - [ ] Neuronbot2 (Adlink)
   - [ ] WAGV (ShanYangYe)
   - [ ] Aider (ShanYangYe)
   - [ ] Sample Two-Wheel-Differential-Model
   - [ ] Sample Four-Whell-Differential-Model
   - [ ] Sample There-Omni-Wheel-Omnidirectional-Model
   - [ ] Sample Four-Omni-Wheel-Omnidirectional-Model
   - [ ] Sample Four-Mecanum-Omnidirectional-Model
   - [ ] Sample Four-Ackermann-non-Holonomic-Model
- [ ] Lidar Model
  - [ ] non lidar
  - [ ] Rplidar (A1)
  - [ ] Rplidar (A2)
  - [ ] Rplidar (A3)
  - [ ] Rplidar (S1)
- [ ] Camera Model
  - [ ] non camera

# Install
This will download the package of kubot_base_driver and install it.

```sh
cd ~/kubot_ros/ros_ws/src
git clone https://github.com/kubot080301/kubot_description.git -b melodic-devel
cd ..
catkin_make
source ~/.bashrc
```
