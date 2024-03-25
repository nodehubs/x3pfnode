English| [简体中文](./README_cn.md)

# Function Introduction

RDK X3 Performance Node, a performance monitoring application for RDK X3 & RDK X3 Module built on the web, monitoring CPU, GPU, Memory, and Disk. Whether it's a computer or a mobile phone of any brand, simply access it in the browser on the same local area network to experience it.

[![desktop_demo](./doc/desktop_demo.jpg)](./doc/desktop_demo.jpg)

[![mult_device](./doc/mult_device.jpg)](./doc/mult_device.jpg)

# Bill of Materials

| Robot Name            | Manufacturer | Reference Link                                 |
| ----------------------| ------------ | ---------------------------------------------- |
| RDK X3 (Any memory version) | Multiple Manufacturers | [Click to jump](https://developer.horizon.cc/rdkx3) |

# Instructions

**Install Flask and psutil**

```
pip install psutil -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com
```

```
pip install flask -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com
```

**After starting RDK X3, connect to the robot via terminal SSH or VNC, copy and run the following commands on the RDK system to complete the installation of the related Node.**

```
sudo apt update
sudo apt install -y tros-x3pfnode
```

**Run**

```
source /opt/tros/setup.bash
ros2 run x3pfnode x3pfnode
```

**Access X3 on port 5000 in the same local area network**

```
IP:5000
```

# Interface Description

None for now, it will be restructured based on the ROS2 topic communication mechanism in the future.# Frequently Asked Questions

See the comments section.

If you find it helpful, please give it a like before you go~