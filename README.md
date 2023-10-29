# AWS Deepracer Robot Project

This project is dedicated to setting up and enhancing the capabilities of the AWS Deepracer Evo vehicle, a 1/18th scale Wi-Fi-enabled 4-wheel Ackermann steering platform that features two RGB cameras and a LiDAR sensor. Using ROS2, this repository provides configuration and launch files for navigation, SLAM, and vehicle control, both in device and simulation mode.

## Project Overview

The AWS DeepRacer Evo vehicle is an exciting platform for robotics enthusiasts. It features advanced sensors and capabilities that we've harnessed for various robotics tasks. In this repository, we have documented and implemented key aspects of the vehicle's functionality, such as navigation, SLAM, and control. Here's a closer look at the project contents:

### Contents

The AWS DeepRacer repository consists of the following packages:

-   **deepracer_bringup:** This package hosts launch files and configuration parameter files to launch SLAM and navigation packages and nodes, making it easy to get started with the DeepRacer's capabilities.
    
-   **deepracer_description:** In this package, you'll find the URDF files for the AWS DeepRacer device in Gazebo simulation. This package provides the essential sensor configurations required for accurate simulation.
    
-   **deepracer_gazebo:** The package that hosts the deepracer_drive plugin, a crucial component for simulating the vehicle's movement in Gazebo, ensuring realistic testing and development.
    
-   **deepracer_nodes:** This package houses a set of nodes responsible for launching various packages required for the integration of other packages, enabling the seamless operation of the DeepRacer.
    

For detailed information and documentation, please refer to the project documents. We've organized this repository to provide a clear and accessible resource for those interested in working with the DeepRacer Evo vehicle.

## Repository Contents

The repository contains code, configuration files, and documentation that facilitates the setup and control of the DeepRacer. You'll find organized sections and directories for each aspect of the project, making it easy to access and understand the work done. 
