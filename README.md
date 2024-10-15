```bash
echo "deb [trusted=yes] https://github.com/nobleo/ros_debian_packages/raw/jammy-iron-amd64/ ./" | sudo tee /etc/apt/sources.list.d/nobleo_ros_debian_packages.list
echo "yaml https://github.com/nobleo/ros_debian_packages/raw/jammy-iron-amd64/local.yaml iron" | sudo tee /etc/ros/rosdep/sources.list.d/1-nobleo_ros_debian_packages.list
```
