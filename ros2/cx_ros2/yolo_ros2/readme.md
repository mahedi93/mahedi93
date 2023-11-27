### Build and RUN Ros2 nodes:

Source the environment first
```
source /opt/ros/foxy/setup.bash
```
Build the package

```
colcon build --symlink-install

```
Run the nodes
```
ros2 run ros2_yolov5_docker ros2_yolov5_docker_node
```


