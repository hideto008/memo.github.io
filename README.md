# memo.github.io

## ROS2 hubmle installation for Ubuntu 22.04

- step1 install 'ros-humble-desktop' and 'ros-dev-tools'

https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html

- step2 install gazebo
```
sudo apt install ros-humble-gazebo-*
```

- step3 install xacro
```
sudo apt install ros-humble-xacro
```

- step4 install ros2-control
```
sudo apt install ros-humble-ros2-control
```

- step4 install gazebo-ros2-control
```
sudo apt install ros-humble-gazebo-ros2-control-*
```

- step 5 install joystick
```
sudo apt install joystick
sudo apt install jstest-gtk
sudo apt install ros-humble-joy*
```
check joystick status using ros node
```
ros2 run joy_linux joy_linux_node
```
- step 6 install moveit
```
sudo apt install ros-humble-moveit
```

https://moveit.ros.org/install-moveit2/binary/

https://moveit.picknik.ai/humble/doc/tutorials/getting_started/getting_started.html

## moveit tutorial

- down grade setuptool version to build ros2_tutorial repository
```
sudo apt install python3-pip
pip install setuptools==58.2.0
```

https://answers.ros.org/question/396439/setuptoolsdeprecationwarning-setuppy-install-is-deprecated-use-build-and-pip-and-other-standards-based-tools/


- docker

https://moveit.picknik.ai/humble/doc/how_to_guides/how_to_setup_docker_containers_in_ubuntu.html

https://moveit.picknik.ai/humble/doc/tutorials/quickstart_in_rviz/quickstart_in_rviz_tutorial.html

## others

- pip
```
sudo apt install python3-pip
```


- install scilab
```
sudo apt intall scilab
```

- install drawio
```
sudo apt update
sudo apt install snapd
sudo apt install drawio
```

- install octave
```
sudo apt install octave
```

