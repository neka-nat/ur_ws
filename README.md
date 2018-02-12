# Universal robot with robotiq hand workspace

## Build

```
cd ur_ws/src
wstool update
cd ../
catkin build
```

## Run

```
source devel/setup.bash
roslaunch ur_robotiq_gazebo ur_robotiq_gazebo.launch
```
![ur_robotiq](images/ur_robotiq.jpg)

## Grasp

The other terminal

```
rosrun ur_robotiq_manipulation grasp_object.py
```

![grasping](images/grasping.gif)
