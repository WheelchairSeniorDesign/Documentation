# ROS2 Build Instructions

## How to Build ROS2 Packages

1. Navigate to `~/ros2_ws` in the terminal.
2. Type `colcon build`.

## How to Build a Specific Package in ROS2 (Without Building All the Others)

1. Navigate to `~/ros2_ws` in the terminal.
2. Type `colcon build --packages-select packageName` where `packageName` is the name of your package.