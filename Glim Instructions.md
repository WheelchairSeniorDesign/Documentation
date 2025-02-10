# Steps for Running Glim

To run the Glim node, use the following command:

```sh
ros2 run glim_ros glim_rosnode
```

## If Not Configured in the `src`

If the configuration is not set in the `src` directory, use this command:

```sh
ros2 run glim_ros glim_rosnode --ros-args -p config_path:=$(realpath ~/config)
```

## Editing the Config in `~/ros2_ws/src/glim`

If you edit the config in the `~/ros2_ws/src/glim` folder, then when you build the app and re-source ROS, you can just use:

```sh
ros2 run glim_ros glim_rosnode
```

for the configuration.
