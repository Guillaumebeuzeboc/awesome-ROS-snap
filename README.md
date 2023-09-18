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

- [Awesome Robot Operating System (ROS) Snap ](#awesome-robot-operating-system-ros-snap-)
  - [Contents](#contents)
  - [Robotics snaps](#robotics-snaps)
    - [Applications](#applications)
    - [Tools](#tools)
  - [Documentation](#documentation)
    - [Snapcraft documentation](#snapcraft-documentation)
    - [Blog posts](#blog-posts)
    - [Papers](#papers)
    - [Examples](#examples)
      - [Basics](#basics)
      - [Advanced](#advanced)
  - [Community](#community)
  - [Operating systems](#operating-systems)

## Robotics snaps

### Applications

- [eprosima's vulcanexus snaps](https://snapcraft.io/publisher/eprosima) - Collection of snapped applications like micro-ros-agent, dds-router, etc.
- [husarion's snaps](https://snapcraft.io/publisher/husarion) - Collection of applications for Husarion's robots.
- [ros2-foxy-rosbag](https://snapcraft.io/ros2-foxy-rosbag) - A portable ROS2 Foxy toolkit, to provide the `ros2 bag` utility anywhere.
- [rosboard](https://snapcraft.io/rosboard) - Turn your robot into a web server to visualize ROS topics.
- [turtlebot3c](https://snapcraft.io/turtlebot3c) - Turtlebot3 as a snap!

### Tools

- [foxglove-studio](https://snapcraft.io/foxglove-studio) - Visualization and debugging tooling for your robotics data.
- [gazebo](https://snapcraft.io/gazebo) - Iterate quickly on design concepts and control strategies with Ignition's rich suite of tools, libraries, and cloud services.
- [plotJuggler](https://snapcraft.io/plotjuggler) - The Time Series Visualization Tool that you Deserve.
- [qtcreator-ros](https://snapcraft.io/qtcreator-ros) - Qt Creator with ROS plugin.
- [ros2-cli](https://snapcraft.io/ros2-cli) - Snap for ROS 2 command line interface tools included with a standard install of any ROS 2 distro.
- [rosshow](https://snapcraft.io/rosshow) - Visualize ROS topics in a terminal with ASCII art.
- [tesseract-ignition](https://snapcraft.io/tesseract-ignition) - This package provides GUI Tools for the Tesseract Motion Planning libraries.
- [webots](https://snapcraft.io/webots) - Webots is a free and open-source 3D robot simulator.


## Documentation

### Snapcraft documentation

- [Snaps for Robotics applications](https://ubuntu.com/robotics/docs) - General introduction.
- [Getting started - ROS](https://snapcraft.io/docs/ros-applications) - How to snap a ROS package.
- [Getting started - ROS 2](https://snapcraft.io/docs/ros2-applications) - How to snap a ROS 2 application.
- [ROS FAQ & Troubleshooting](https://ubuntu.com/robotics/docs/faq-and-troubleshooting) - Reference ROS and ROS 2 snap common questions and troubleshooting.
- [Packaging your ROS project as a snap](http://wiki.ros.org/ROS/Tutorials/Packaging%20your%20ROS%20project%20as%20a%20snap) - ROS wiki.
- [Packaging your ROS 2 application as a snap](https://docs.ros.org/en/foxy/Tutorials/Packaging-your-ROS-2-application-as-a-snap.html) - ROS 2 documentation.
- [Snapcraft Catkin plugin](https://snapcraft.io/docs/catkin-plugin) - Snapcraft Catkin plugin documentation.
- [Snapcraft Catkin-tools plugin](https://snapcraft.io/docs/catkin-tools-plugin) - Snapcraft Catkin-tools plugin documentation.
- [Snapcraft Colcon plugin](https://snapcraft.io/docs/the-colcon-plugin) - Snapcraft Colcon plugin documentation.
- [Snapcraft ROS Noetic extension](https://snapcraft.io/docs/ros1-extension) - Snapcraft ROS Noetic extension.
- [Snapcraft ROS 2 Foxy extension](https://snapcraft.io/docs/ros2-extension) - Snapcraft ROS 2 Foxy extension.
- [Developer guide - Part 1: Distributing ROS apps with snaps](https://ubuntu.com/robotics/docs/ros-deployment-with-snaps-part-1) -  Package a ROS application tutorial (part 1)
- [Developer guide - Part 2: Distributing ROS apps with snaps](https://ubuntu.com/robotics/docs/ros-deployment-with-snaps-part-2) -  Package a ROS application tutorial (part 2)
- [ROS snapcraft How-to-guides](https://ubuntu.com/robotics/docs/how-to-guides) - A collection of official ROS snapcraft how to guides
- [ROS snaps references](https://ubuntu.com/robotics/docs/explanation#heading--snaps) - A collection of official ROS snaps references

### Blog posts

- [Keep enterprise ROS robots up-to-date with snaps](https://ubuntu.com/blog/keep-enterprise-ros-robots-up-to-date-with-snaps)
- [How to build a snap using ROS2 Foxy](https://snapcraft.io/blog/how-to-build-a-snap-using-ros-2-foxy)
- [How to set up TurtleBot3 in minutes with snaps](https://ubuntu.com/blog/how-to-set-up-turtlebot3-in-minutes-with-snaps) (part [two](https://ubuntu.com/blog/how-to-set-up-turtlebot3-in-minutes-with-snaps-2))
- [ROS Docker; 6 reasons why they are not a good fit](https://ubuntu.com/blog/ros-docker)
- [How to use ROS 2 shared memory in snaps](https://ubuntu.com/blog/how-to-use-ros-2-shared-memory-in-snaps)
- [ROS orchestration with snaps](https://ubuntu.com/blog/ros-orchestration-with-snaps)
- [Getting started with ROS security scanning](https://ubuntu.com/blog/getting-started-with-ros-security-scanning)
- [Top 10 robotics snaps in the Snap Store](https://ubuntu.com/blog/top-10-robotics-snaps-p1)
- [Snapping out of Docker: a robotics guide for migrating from Docker to snap](https://ubuntu.com/blog/snapping-out-of-docker)
- [Optimize your ROS snap - part 1](https://ubuntu.com/blog/optimise-your-ros-snap-part-1), [part 2](https://ubuntu.com/blog/optimise-your-ros-snap-part-2), [part 3](https://ubuntu.com/blog/optimise-your-ros-snap-part-3), [part 4](https://ubuntu.com/blog/optimise-your-ros-snap-part-4), [part 5](https://ubuntu.com/blog/optimise-your-ros-snap-part-5) and [part 6](https://ubuntu.com/blog/optimise-your-ros-snap-part-6)
- [ROS architectures with snaps](https://ubuntu.com/blog/ros-architectures-with-snaps)

### Papers

- [Docker & ROS: When all you have is a hammer, everything looks like a nail](https://ubuntu.com/engage/dockerandros?utm_medium=blog&utm_campaign=7014K000000UWJn) - A Docker & ROS whitepaper.

### Examples

- [ubuntu-robotics/ros-snaps-examples](https://github.com/ubuntu-robotics/ros-snaps-examples) - Various examples of ROS and ROS 2 snaps from the Canonical robotics team.

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

- [Ubuntu robotics forum](https://discourse.ubuntu.com/c/robotics/121)
- [Snapcraft forum](https://forum.snapcraft.io/search?q=ROS)

## Operating systems

- [Ubuntu Desktop](https://ubuntu.com/desktop) - The open source Ubuntu desktop operating system powers millions of PCs and laptops around the world.
- [Ubuntu Server](https://ubuntu.com/server) - A lightweight Ubuntu without desktop designed for the cloud.
- [Ubuntu Core](https://ubuntu.com/core) - An operating system designed for IoT & Robotics.
