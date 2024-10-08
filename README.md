# Autonomous Obstacle Bypass Robot [[ACM](https://dl.acm.org/doi/abs/10.1145/3570361.3614066)]

This repository contains the codebase for an autonomous robot capable of bypassing obstacles in cluttered environments using a camera as its sole sensing mechanism. The robot is programmed to follow a predetermined path via a line following module while utilizing a custom object detection model to detect and differentiate obstacles on the road from other objects in the environment.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Demo Video](#demo-video)
- [License](#license)

## Overview

This project focuses on developing a robot that can autonomously navigate through cluttered environments by detecting obstacles and adjusting its path accordingly. The robot utilizes a camera for visual input and employs a YOLOv5-based custom object detection model for obstacle detection.

## Prerequisites

Before running the robot code, make sure you have the following prerequisites:

- NVIDIA Jetson device
- Python 3
- PyTorch
- NVIDIA JetBot library
- Required Python packages (specified in `requirements.txt`)

## Installation

1. Clone this repository:

```bash
git clone https://github.com/ICONgroupCWC/ObstacleBypassing.git
cd autonomous-obstacle-robot
```

2. Install the requirements:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter notebook demo_live.ipynb in a Jupyter environment.

4. Follow the instructions in the notebook to set up the robot, adjust parameters, and execute the obstacle bypass algorithm.

5. Observe the robot's behavior as it autonomously navigates through the controlled environments, detects obstacles, and adjusts its path to bypass them.

Note: Make sure you have access to an NVIDIA Jetson device and have the necessary hardware components connected to run the code successfully.

## Demo Video

Check out the following demo video to see the autonomous obstacle bypass robot in action:

[![Demo Video](http://i3.ytimg.com/vi/zC5y01txFu0/hqdefault.jpg)](https://www.youtube.com/watch?v=zC5y01txFu0)

## License

This project is licensed under the [MIT License](LICENSE).


