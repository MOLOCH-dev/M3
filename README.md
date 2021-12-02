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
git clone https://github.com/MOLOCH-dev/M3.git -b dev
cd ..
catkin_make
```

### Executing program

* Source the setup files
```
source ~/catkin_ws/devel/setup.bash
```
* Launch Gazebo Simulation
```
roslaunch mbzirc_ur5_description mbzirc_ur5.launch 
```
* Launch MoveIt Planner Interface
```
roslaunch mbzirc_ur5_moveit_config mbzirc_ur5_planning_execution.launch 
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
* [universal robot](https://github.com/ros-industrial/universal_robot.git)
