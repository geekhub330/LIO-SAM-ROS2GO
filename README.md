# LIO-SAM Modifiled for ROS2GO system 
**针对ROS2GO系统下的ubuntu20.04的简单修改**
 



## Dependency


- [gtsam]
  gtsam-4.0.3

## Install



```
cd ~/catkin_ws/src
git clone https://github.com/geekhub330/LIO-SAM-ROS2GO.git
cd ..
catkin_make
```



## Run the package

1. Run the launch file:
```
roslaunch lio_sam run.launch
```

2. Play existing bag files:
```
rosbag play bagname.bag --clock
```





