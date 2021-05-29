# darknet-ros-3D
This is a repo created for 2d and 3d object recognition and detection using yolo darknet ros packages 



### How to run:

1. To open cam-bot in Gazebo | Terminal 1: `roslaunch camera_sim cam.launch`
2. To open cam-bot in and initiate darknet   | Terminal 2: `roslaunch my_object_recognition yolo_v2_tiny.launch`
3. To viz point-cloud in ros use | Terminal 3: `roslaunch camera_sim viz.launch` 


# Results :
![](result.gif)


# Tested on System config:
- Hardware: Intel i3 dual-core qual-thread
- ROS: Melodic
- OS: Ubuntu 18.04 LTS
- 2-core AMD
- 8GB RAM

