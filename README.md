## Overview

The AWS DeepRacer Evo vehicle is a 1/18th scale Wi-Fi-enabled 4-wheel Ackermann steering platform that features two RGB cameras and a LiDAR sensor. This repository contains the configuration and launch files to do navigation, SLAM, and control the vehicle using ROS2. For detailed information, see our [documents](https://github.com/redHaunter/aws-deepracer/tree/main/docs).
## Contents

The AWS DeepRacer repository consists of the following packages:

1. **deepracer_bringup**: The deepracer_bringup package hosts the launch files and configuration parameter files to launch SLAM and navigation packages and nodes.

1. **deepracer_description**: The deepracer_description package hosts the URDF files for the AWS DeepRacer device in Gazebo simulation. This provides the arguments to configure the sensors.

1. **deepracer_gazebo**: The deepracer_gazebo package hosts the deepracer_drive plugin that is required to move the car in simulation.

1. **deepracer_nodes**: The deepracer_nodes packages hosts the set of nodes that are responsible for launching packages required for the integration of other packages.
