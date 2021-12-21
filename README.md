# Multiple Mobile Manipulators
Collaborative task for multiple mobile manipulators with dynamic capability-based task allocation of individual manipulators for efficient object transportation/manipulation

## Description



## Getting Started

### Dependencies

* Ubuntu 18.04, ROS Melodic, MoveIt

### Installing

```
source /opt/ros/melodic/setup.bash
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone https://github.com/MOLOCH-dev/M3.git -b youbot_ws
cd ..
catkin_make
```

### Executing program

* Source the setup files
```
source ~/catkin_ws/devel/setup.bash
```
* Launch Gazebo Simulation
For one youbot :
```
roslaunch youbot_gazebo_robot youbot.launch
```
For multiple youbots : 
```
roslaunch youbot_gazebo_robot multi_youbot.launch
```

## Help

* [Progress tracker](https://docs.google.com/spreadsheets/d/1pQOMQNmWn8g2MU3KeMXHZzm2AR2Vb22gNhGR8cUcgWM/edit?usp=sharing)

## Authors


Anushree Sabnis 
[@MOLOCH-dev](https://www.linkedin.com/in/anushreesabnis)
Keshab Patra
[@keshabpatra19](https://github.com/keshabpatra19)

## License

This project is licensed under the Apache 2.0 License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [mas group](https://github.com/mas-group/youbot_description)
