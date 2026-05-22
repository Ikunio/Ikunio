# Lidar_nav2_ws

ROS2 autonomous navigation workspace based on Livox MID-360 3D LiDAR.

## Features

- LiDAR-inertial odometry integration
- 3D point cloud map building
- ROS2 Nav2 navigation
- Localization and path planning
- Custom controller integration
- Supports simulation and real robot deployment

## System Architecture

```text
Livox MID-360
      |
      v
LIO / SLAM Node
      |
      v
map -> odom -> base_link
      |
      v
Nav2 Planner / Controller
      |
      v
Robot Chassis
