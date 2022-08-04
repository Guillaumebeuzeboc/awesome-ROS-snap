# Awesome Robot Operating System (ROS) Snap [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://cdn.iconscout.com/icon/free/png-256/snapcraft-3521718-2945162.png" align="right" width="26">](https://snapcraft.io/about)

[<img src="https://raw.githubusercontent.com/fkromer/awesome-ros2/master/ros_logo.svg?sanitize=true" align="right" width="86">](https://www.ros.org/blog/getting-started/)

> A curated list of awesome [Robot Operating System](https://www.ros.org/) (ROS 1 & 2) [snap](https://snapcraft.io) resources.

The Robot Operating System (ROS) is a set of software libraries and tools that help you build robot applications.
From drivers to state-of-the-art algorithms,
and with powerful developer tools,
ROS has what you need for your next robotics project.
And it's all open source.

Snaps are app packages for desktop, cloud and IoT that are easy to install,
secure, cross‐platform and dependency‐free.
Snaps are discoverable and installable from the Snap Store,
the app store for Linux with an audience of millions.
And they come with ROS integration.

## Contents

- [ROS snaps](#ros-snaps)
  - [Applications](#applications)
  - [Tools](#tools)
- [Robotics snaps](#robotics-snaps)
- [Documentation](#documentation)
  - [Snapcraft documentation](#snapcraft-documentation)
  - [Blog posts](#blog-posts)
  - [Papers](#papers)
  - [Examples](#examples)
- [Community](#community)
- [Operating systems](#operating-systems)

## ROS snaps

### Applications

- [micro-ros-agent](https://snapcraft.io/micro-ros-agent) - Bridge between micro-ROS applications and ROS 2.
- [rosshow](https://snapcraft.io/rosshow) - Visualize ROS topics in a terminal with ASCII art.
- [rosboard](https://snapcraft.io/rosboard) - Turn your robot into a web server to visualize ROS topics.
- [turtlebot3c](https://snapcraft.io/turtlebot3c) - Turtlebot3 as a snap!

### Tools

- [qtcreator-ros](https://snapcraft.io/qtcreator-ros) - Qt Creator with ROS plugin.
- [tesseract-ignition](https://snapcraft.io/tesseract-ignition) - This package provides GUI Tools for the Tesseract Motion Planning libraries.

## Robotics snaps

- [Gazebo](https://snapcraft.io/gazebo) - Iterate quickly on design concepts and control strategies with Ignition's rich suite of tools, libraries, and cloud services.
- [Micro XRCE-DDS Agent](https://snapcraft.io/micro-xrce-dds-agent) - Bridge between Micro XRCE-DDS clients and DDS.
- [PlotJuggler](https://snapcraft.io/plotjuggler) - The Time Series Visualization Tool that you Deserve.
- [Webots](https://snapcraft.io/webots) - Webots is a free and open-source 3D robot simulator.
- [foxglove-studio](https://snapcraft.io/foxglove-studio) - Visualization and debugging tooling for your robotics data.

## Documentation

### Snapcraft documentation

- [Snaps for Robotics applications](https://snapcraft.io/docs/robotics) - General introduction.
- [Getting started - ROS](https://snapcraft.io/docs/ros-applications) - How to snap a ROS package.
- [Getting started - ROS 2](https://snapcraft.io/docs/ros2-applications) - How to snap a ROS 2 application.
- [ROS FAQ & Troubleshooting](https://snapcraft.io/docs/ros-troubleshooting) - Reference ROS and ROS 2 snap common questions and troubleshooting.
- [Packaging your ROS project as a snap](http://wiki.ros.org/ROS/Tutorials/Packaging%20your%20ROS%20project%20as%20a%20snap) - ROS wiki.
- [Packaging your ROS 2 application as a snap](https://docs.ros.org/en/foxy/Tutorials/Packaging-your-ROS-2-application-as-a-snap.html) - ROS 2 documentation.
- [Snapcraft Catkin plugin](https://snapcraft.io/docs/catkin-plugin) - Snapcraft Catkin plugin documentation.
- [Snapcraft Catkin-tools plugin](https://snapcraft.io/docs/catkin-tools-plugin) - Snapcraft Catkin-tools plugin documentation.
- [Snapcraft Colcon plugin](https://snapcraft.io/docs/the-colcon-plugin) - Snapcraft Colcon plugin documentation.
- [Snapcraft ROS Noetic extension](https://snapcraft.io/docs/ros1-extension) - Snapcraft ROS Noetic extension.
- [Snapcraft ROS 2 Foxy extension](https://snapcraft.io/docs/ros2-extension) - Snapcraft ROS 2 Foxy extension.

### Blog posts

- ["Keep enterprise ROS robots up-to-date with snaps"](https://ubuntu.com/blog/keep-enterprise-ros-robots-up-to-date-with-snaps)
- ["How to build a snap using ROS2 Foxy"](https://snapcraft.io/blog/how-to-build-a-snap-using-ros-2-foxy)
- ["How to set up TurtleBot3 in minutes with snaps"](https://ubuntu.com/blog/how-to-set-up-turtlebot3-in-minutes-with-snaps) (part [two](https://ubuntu.com/blog/how-to-set-up-turtlebot3-in-minutes-with-snaps-2))
- ["ROS Docker; 6 reasons why they are not a good fit"](https://ubuntu.com/blog/ros-docker)
- ["How to use ROS 2 shared memory in snaps"](https://ubuntu.com/blog/how-to-use-ros-2-shared-memory-in-snaps)

### Papers

- ["Docker & ROS: When all you have is a hammer, everything looks like a nail"](https://ubuntu.com/engage/dockerandros?utm_medium=blog&utm_campaign=7014K000000UWJn) - A whitepaper.

### Examples

#### Basics

- [ROS talker-listener](https://github.com/snapcraft-docs/ros-talker-listener) - ROS Melodic (core18) talker-listener from ros-tutorials.
- [ROS 2 talker-listener](https://github.com/snapcraft-docs/ros2-talker-listener) - ROS2 Dashing (core18) talker-listener from ROS 2 demos.
- [ROS talker-listener](https://github.com/snapcraft-docs/ros-talker-listener-core20) - ROS1 Noetic (core20) talker-listener from ros-tutorials.
- [ROS2 talker-listener](https://github.com/snapcraft-docs/ros2-talker-listener-core20) - ROS2 Foxy (core20) talker-listener from ROS 2 demos.
- [Snapped ROS pkg](https://github.com/Guillaumebeuzeboc/snapped_ros1_pkg) - Snap ROS package from sources. [Melodic - core18](https://github.com/Guillaumebeuzeboc/snapped_ros1_pkg/tree/core18) & [Noetic - core20](https://github.com/Guillaumebeuzeboc/snapped_ros1_pkg/tree/main).
- [Snapped ROS 2 pkg](https://github.com/Guillaumebeuzeboc/snapped_ros2_pkg) - Snap ROS2 package from sources. [Dashing - core18](https://github.com/Guillaumebeuzeboc/snapped_ros2_pkg/tree/core18) & [Foxy - core20](https://github.com/Guillaumebeuzeboc/snapped_ros2_pkg/tree/main).

#### Advanced

- [Snapped ROS 2 talker listener components](https://github.com/Guillaumebeuzeboc/snapped_ros2_talker_listener_components) - ROS 2 talker listener components from two different snaps.
- [Snapped rosinstall](https://github.com/Guillaumebeuzeboc/snapped_ros1_rosinstall) - Snap ROS Noetic (core20) packages pulled from a rosinstall file.

## Community

- [Snapcraft forum](https://forum.snapcraft.io/search?q=ROS)

## Operating systems

- [Ubuntu Desktop](https://ubuntu.com/desktop) - The open source Ubuntu desktop operating system powers millions of PCs and laptops around the world.
- [Ubuntu Server](https://ubuntu.com/server) - A lightweight Ubuntu without desktop designed for the cloud.
- [Ubuntu Core](https://ubuntu.com/core) - An operating system designed for IoT & Robotics.
