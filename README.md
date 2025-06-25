# Phasma Description

URDF Model of the HILTI Phasma robot for ROS2.

## Building with colcon

To build this package with colcon, follow these steps:

1. Clone this repository into your ROS2 workspace:
   ```
   cd ~/ros2_ws/src
   git clone <repository_url>
   ```

2. Install dependencies:
   ```
   cd ~/ros2_ws
   rosdep install --from-paths src --ignore-src -r -y
   ```

3. Build the package:
   ```
   colcon build --packages-select phasma_description
   ```

4. Source the workspace:
   ```
   source ~/ros2_ws/install/setup.bash
   ```

## Launching the model

To view the URDF model in RViz2:
```
ros2 launch phasma_description view_urdf.py
```

![Halo URDF Model](./doc/phasma_urdf.png  "Phasma URDF Model")

