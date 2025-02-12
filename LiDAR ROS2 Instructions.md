# To start the lidar sensor in ROS:
1. Open up a new terminal window
2. Type the command `ros2 launch sllidar_ros2 sllidar_a1_launch.py` (without the quotation marks)
   - You could use `ros2 launch sllidar_ros2 view_sllidar_a1_launch.py` if you want the visualization of the LiDAR sensor
3. If you type `ros2 topic list` you should see `/scan` as a topic
4. If you type `rqt`, you should see a node with `/sllidar_node` with an arrow to the `/scan` topic

## For the A2M8:
- `ros2 launch sllidar_ros2 view_sllidar_a2m8_launch.py` - for the viewer
- `ros2 launch sllidar_ros2 sllidar_a2m8_launch.py` - for just the topic

## For Mid-360:
- `ros2 launch livox_ros_driver2 rviz_MID360_launch.py` - for viz
- `ros2 launch livox_ros_driver2 msg_MID360_launch.py` - for msg

## **Mid-360 Config:**
- Need to edit config file (or the file before it builds in `src`):
  - `/ros2_ws/install/livox_ros_driver2/share/livox_ros_driver2/config/MID360_config.json`
  - `/ws_livox/config`
- Can also edit config files to change parameters:
  - `/ros2_ws/install/livox_ros_driver2/share/livox_ros_driver2/launch_ROS2/`