# MRSL Decomp Util ROS

A ROS wrapper for implementing convex decomposition, stacks include:
  - `decomp_ros_msgs`: ROS msgs used for storing, visualizing and communicating
  - `decomp_ros_utils`: ROS utils for interfacing with `DecompUtil`
  - `decomp_test_node`: contains two example codes for testing

## Compilation
#### Prerequisite:
  - `Ros Desktop`(Noetic)

#### Build by using Catkin Tools:
```bash
catkin config -DCMAKE_BUILD_TYPE=Release
catkin b
```
