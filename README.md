```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/nobleo/ros_debian_packages/noble-rolling-amd64/ ./" | sudo tee /etc/apt/sources.list.d/nobleo_ros_debian_packages-noble-rolling-amd64.list
echo "yaml https://github.com/nobleo/ros_debian_packages/raw/noble-rolling-amd64/local.yaml rolling" | sudo tee /etc/ros/rosdep/sources.list.d/1-nobleo_ros_debian_packages-noble-rolling-amd64.list
```
