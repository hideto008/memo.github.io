# memo.github.io

## ROS2 hubmle installation for Ubuntu 22.04

- step1 install 'ros-humble-desktop'

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

https://moveit.picknik.ai/humble/doc/tutorials/quickstart_in_rviz/quickstart_in_rviz_tutorial.html

## others

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

