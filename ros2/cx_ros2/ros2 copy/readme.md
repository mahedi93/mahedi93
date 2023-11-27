
### Build and run  ROS2 nodes 

Source the package in the root directory
```
 source /opt/ros/humble/setup.bash
```
Build the package in the root directory 

```
colcon build --symlink-install
```

#### Run the publisher and subscriber node by following command 

Publisher node

Be sure source is done

```
ros2 run ros2_yolov5 img_publisher
```

subscrier node

```
 source /opt/ros/humble/setup.bash
```

Run the subscriber node
```
ros2 run ros2_yolov5 img_subscriber
```
