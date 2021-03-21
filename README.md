# tdf-gazebo
gazebo models and world to simulate drone search and rescue tasks for ise

## Add to ~/.bashrc
```
export GAZEBO_MODEL_PATH=<location of models folder>:$GAZEBO_MODEL_PATH
```
Note: You can add the models folder to ~/.gazebo/models/

## Launch the world
```
roslaunch tdf_gazebo start.launch
```
