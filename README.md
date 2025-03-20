# Legato ROS2 Integration

## Overview
This repository provides the **ROS2 integration** and [**`ros2_control` support**](https://control.ros.org/latest/index.html) for actuators supported by the [**Legato Unified Actuator SDK**](https://github.com/open-actuator/legato).

You'll need both repositories cloned into your ROS 2 workspace (e.g., `~/colcon_ws/src`):

```bash
$ git clone https://github.com/open-actuator/legato.git
$ git clone https://github.com/open-actuator/legato-ros2.git
```

- **`legato`**: Contains the core unified actuator SDK (C++ library with Python bindings).
- **`legato-ros2`** (this repository): Provides the ROS2 nodes, `ros2_control` integration, and actuator-specific ROS2 interfaces.

Install dependencies using:

```bash
$ rosdep install --from-paths src/ --ignore-src -r -y
```

For building your workspace:

```bash
$ colcon build --symlink-install
```

Detailed documentation for each supported actuator, usage examples, and configuration details will be added shortly.

## License 📃

MIT License. See [LICENSE](LICENSE) for more details.
