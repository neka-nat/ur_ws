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