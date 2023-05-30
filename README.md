
# Line Following MOGI PORSZI&copy;
This is our assignment for the Robot Systems Laboratory Class 2022/2023 II.
# Table of contents

 1. About the project
 2. Packages needed to work
 3. Starting the line following MOGI PORSZI&copy; 
 4. Development steps
 5. Ways to improve

# About the project
With the help of numerous well-known ros packages a line following robot was made. The robot is called MOGI PORSZI&copy; and uses a camera node from hector_slam packages to see the environment. Furthermore the camera image is used for the algorithm to find and follow the line that is in the surface of our world. The image is processed with the help of openCV. The world was made in gazebo and features a complex route through an artificial house with some obstacles. The MOGI PORSZI&copy;'s great feature is that it can make its way through the obstacles with any real-time factor given in gazebo. This means, that it can work time independent.
# Packages needed to work
 - ros-noetic-desktop-full (especially: rviz, gazebo, openCV)
 - [hector_slam](http://wiki.ros.org/hector_slam) 
 - [rviz-imu-plugin](http://wiki.ros.org/rviz_imu_plugin)
#  Starting the line following MOGI PORSZI&copy; 
We have made our own world to showcase the line following algorithm behind our very own MOGI PORSZI&copy;
To launch the MOGI PORSZI&copy; you have to follow these steps:
 - Clone the repository into your catkin_ws and do a catkin_make
 - Add executable right to /scripts/line_follower.py with chmod -x
 - Start the world with the MOGI PORSZI&copy; `roslaunch line_follower_burger world.launch` 
 - Start the line following algorithm `rosrun line_follower_burger line_follower.py`
 - Enjoy this work of art

# Development steps

 1. Designing and making the MOGI PORSZI&copy;

 2. Making a place for MOGI PORSZI&copy;

3. Making a PID control algorithm that is independent from real time factor

# Ways to improve
Our world is real simple and was made only to present to you the algorithm behind the MOGI PORSZI&copy;.
Much more interesting worlds can be built to test the limits of our MOGI PORSZI&copy;.
The rapid improvements in the computer vision field may give more and more ways to improve the performance of the algorithm. 




