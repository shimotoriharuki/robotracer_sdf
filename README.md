# Overview

This repository contains SDF models of Robotracer and courses that can be used with Gazebo.

[![Image from Gyazo](https://i.gyazo.com/54cb4e3f9a71cce0f993f760ce5acfc0.png)](https://gyazo.com/54cb4e3f9a71cce0f993f760ce5acfc0)
[![Image from Gyazo](https://i.gyazo.com/2eefb19b1df63b6948b77ff164f69d65.png)](https://gyazo.com/2eefb19b1df63b6948b77ff164f69d65)

# Usage

## prerequisite

You need to be able to boot the gazebo on Ubuntu.
The operation was confirmed in the following environment.
- Ubuntu 18.04
- Gazebo 9.0.0

## Clone

Clone with the following command.

```bash
cd ~/.gazebo/models
git clone https://github.com/shimotoriharuki/robotracer_sdf
```
## Run

Long and short courses are available.
Run with the following commands.

### Long course

```bash
cd ~/.gazebo/models/robotracer_sdf/world/
gazebo robotrace_world1.world
```

### Short course

```bash
cd ~/.gazebo/models/robotracer_sdf/world/
gazebo robotrace_world2.world
```

# Simple explanation

This model is skid steer type.The tire is 10mm wide and 10mm radius
The line sensor is a camera with a width of 101 and a height of 1.
The IMU sensor is in the center of rotation of the robot.


# LICENSE

See following link.
- [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)

# Credit 

Some codes use the following credit.

"[gazebo_models](https://github.com/osrf/gazebo_models)" by [Nathan Koenig](https://github.com/nkoenig) is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/deed.en)
