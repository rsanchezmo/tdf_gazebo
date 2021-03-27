# TDF GAZEBO
Gazebo package for simulation of search and rescue robots in tdf mountains base on a heightmap.

![tdf_world](img/world.png)

## Build the world in your catkin workspace
```
source /opt/ros/melodic/setup.bash
catkin_make
```

## Launch the world in your catkin workspace
```
source /opt/ros/melodic/setup.bash
source devel/setup.bash
roslaunch tdf_gazebo start.launch
```

## Description
The world contains multiple environments to design and test search and rescue tasks.

**Collapsed buildings**

![tdf_world](img/ruins.png)

**Base to deploy search and rescue robots**

![tdf_world](img/base.png)

**Forest**

![tdf_world](img/forest.png)

## Models
There are also included animal models to integrate in the world such as cows, goats and wolves. 

![tdf_world](img/animals.png)
