# ROS Bag Instructions

To play a ros2 bag, go to `~/ros_bags`:

```sh
ros2 bag play bag_name
```

To use in the visualizer, first run:

```sh
rviz2
```

Then change the Fixed Frame setting from `map` to `livox_frame`.

To record a bag, use:

```sh
ros2 bag record -o bag_name /livox/lidar /livox/imu
```