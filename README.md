```bash
echo "deb [trusted=yes] https://github.com/nobleo/ros_debian_packages/raw/noble-jazzy/ ./" | sudo tee /etc/apt/sources.list.d/nobleo_ros_debian_packages.list
echo "yaml https://github.com/nobleo/ros_debian_packages/raw/noble-jazzy/local.yaml jazzy" | sudo tee /etc/ros/rosdep/sources.list.d/1-nobleo_ros_debian_packages.list
```
