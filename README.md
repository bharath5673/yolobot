# ROS2 yolobot

##  yolobot_ws
```bash

sudo apt install ros-humble-gazebo-ros
sudo apt-get install ros-humble-gazebo-msgs
sudo apt-get install ros-humble-gazebo-plugins

pip install yolov5
```
___
___


```bash

### steps for setting up
git clone https://github.com/bharath5673/yolobot.git
cd yolobot
colcon build
cd ..


```

___
___



![Screenshot from 2023-01-28 17-31-40](https://user-images.githubusercontent.com/33729709/215265717-6c2092c0-4e0f-4cf3-bec8-51024dfb05bf.png)


```bash

### step for roslaunch
source /opt/ros/humble/setup.bash
source yolobot/install/setup.bash

ros2 launch yolobot_gazebo yolobot_launch.py

```

___
___


![Screenshot from 2023-01-28 16-55-02](https://user-images.githubusercontent.com/33729709/215265729-31d9f9b0-79ff-453e-9941-c39312bd6aa7.png)



```bash

### step for yolobot detetcion 
source /opt/ros/humble/setup.bash
source yolobot/install/setup.bash

python3 yolobot/src/yolobot_recognition/yolobot_recognition/ros_recognition_yolo.py

 

```
