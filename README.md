# Awesome-ROS-snap
A curated list of awesome ROS{2} snap documentation and resources.

<!--toc-->

## Table of index
- [Awesome-ROS-snap](#awesome-ros-snap)
  - [Table of index](#table-of-index)
  - [Documentation](#documentation)
    - [Snapcraft documentation](#snapcraft-documentation)
    - [Blog posts](#blog-posts)
  - [Examples](#examples)
    - [Basics](#basics)
    - [Advanced](#advanced)
<!--toc-end-->

## Documentation
### Snapcraft documentation
- [ROS Applications](https://snapcraft.io/docs/ros-applications) - Snap an external ROS1 package
- [ROS2 Applications](https://snapcraft.io/docs/ros2-applications) - Snap an external ROS2
- [Catkin plugin](https://snapcraft.io/docs/catkin-plugin) - Catkin plugin for ROS1
- [Catkin-tools plugin](https://snapcraft.io/docs/catkin-tools-plugin) - Catkin-tools plugin for ROS1
- [Colcon plugin](https://snapcraft.io/docs/the-colcon-plugin) - Colcon plugin for ROS2
- [ROS1 extension](https://snapcraft.io/docs/ros1-extension) - ROS1 Noetic extension for core20
- [ROS2 extension](https://snapcraft.io/docs/ros2-extension) - ROS2 Foxy extension for core20
- [Packing your ROS1 project as a snap](http://wiki.ros.org/ROS/Tutorials/Packaging%20your%20ROS%20project%20as%20a%20snap) - Pack a ROS1 Kinetic (core16) project as a snap
### Blog posts
- [how to build a snap using ROS2 Foxy](https://snapcraft.io/blog/how-to-build-a-snap-using-ros-2-foxy) - Build a ROS2 Foxy snap on core20
- [Distributing a ROS system among multiple snaps](https://snapcraft.io/blog/distributing-a-ros-system-among-multiple-snaps) - [outdated] For core16 only, but the idea is here
- [Speed up your ROS snap builds](https://snapcraft.io/blog/speed-up-your-ros-snap-builds) - Build time dependencies between ROS snaps
## Examples
### Basics
- [ROS talker-listener](https://github.com/snapcraft-docs/ros-talker-listener) - ROS1 Melodic core18 talker-listener from ros-tutorials
- [ROS2 talker-listener](https://github.com/snapcraft-docs/ros2-talker-listener) - ROS2 Dashing core18 talker-listener from ROS2 demos
- [ROS talker-listener core20](https://github.com/snapcraft-docs/ros-talker-listener-core20) - ROS1 Noetic core20 talker-listener from ros-tutorials
- [ROS2 talker-listener core20](https://github.com/snapcraft-docs/ros2-talker-listener-core20) - ROS2 Foxy core20 talker-listener from ROS2 demos
- [Snapped ROS1 pkg](https://github.com/Guillaumebeuzeboc/snapped_ros1_pkg) - Snap ROS1 package from source [core20](https://github.com/Guillaumebeuzeboc/snapped_ros1_pkg/tree/main) and [core18](https://github.com/Guillaumebeuzeboc/snapped_ros1_pkg/tree/core18)
- [Snapped ROS2 pkg](https://github.com/Guillaumebeuzeboc/snapped_ros2_pkg) - Snap ROS2 package from source [core20](https://github.com/Guillaumebeuzeboc/snapped_ros2_pkg/tree/main) and [core18](https://github.com/Guillaumebeuzeboc/snapped_ros2_pkg/tree/core18)
### Advanced
- [Snapped ROS2 talker listener components](https://github.com/Guillaumebeuzeboc/snapped_ros2_talker_listener_components) - ROS2 talker listener components from two different snaps
- [Turtlebot snap](https://github.com/canonical/turtlebot3c-snap) - Turtlebot3c packaged as a snap
- [Rosshow snap](https://github.com/dheera/rosshow/blob/main/snap/snapcraft.yaml) - Rosshow ROS1 package as a snap
- [Rosboard snap](https://github.com/dheera/rosboard/pull/83) - Rosboard ROS package as a snap (not merged yet)