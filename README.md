
# Robotics-Challenge

This is a four week robotics challenge with Dr. John Vial, We will implement four different Robots in this journey.

# The Plan

Week 1: Extend KRYTN Robotics
Week 2: Create A Wheeled Robot
Week 3: Create A Robot ARM
Week 4: Create a robot with wheels and arm

Following are the main softwares you need for this challenge 

1. WSL 2 or Ubuntu
2. [Docker](https://docs.docker.com/engine/install/ubuntu/)
3. VS Code
4. FreeCAD

## Day 0: Dr. John Vial free course on "[Start Creating Robots Course](https://github.com/johnny555/start-creating-robots-email/tree/main/course)"



## Day 1: Peering Under the Hood

##### Please don't forget to source it: like
``` export IGN_GAZEBO_RESOURCE_PATH=/home/kxx/Robotics-Challenge/start-creating-robots-email/install/start_creating_robots/share/start_creating_robots/worlds_and_models/ ``` 

In terminal 1:

``` 
ros2 launch start_creating_robots navigation.launch.py
```

##### ROS2 command list
```
ros2 topic list
ros2 topic echo <topic_name>
ros2 topic info /topic_name

ros2 node list
ros2 node info /node_name

ros2 doctor
(This command checks the ROS2 environment for potential issues.)
```

##### Publishing topics
If you want to publish topics, then run the following command
```
ros2 topic pub <your_topic> <hit_tab> <hit_tab>
```

##### Some ROS packages
```
ros2 run rqt_graph rqt_graph
```

```
ros2 run tf2_tools view_frames 
```
![Alt text](<Screenshot from 2023-12-05 18-18-55.png>)