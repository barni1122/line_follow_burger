# Line Followig MOGI PORSZI&copy;
This is our assignment for the Robot Systems Laboratory Class 2022/2023 II.

# Packages needed to wok

 - hector_slam
 - rviz-imu-plugin
#  Starting the line following MOGI PORSZI&copy; 
We have made our own world to showcase the line following algorithm behind our very own MOGI PORSZI&copy;
To launch the MOGI PORSZI&copy; you have to follow these steps:
 - Clone the repository into your catkin_ws and do a catkin_make
 - Add executable right to /scripts/line_follower.py with chmod -x
 - Start the world with the MOGI PORSZI&copy; `roslaunch line_follower_burger world.launch` 
 - Start the line following algorithm `rosrun line_follower_burger line_follower.py`
 - Enjoy this work of art
# Ways to improve
Our world is real simple and was made only to present to you the algorithm behind the MOGI PORSZI&copy;.
Much more interesting worlds can be built to test the limits of our MOGI PORSZI&copy;.
The rapid improvements in the computer vision field may give more and more ways to improve the performance of the algorithm. 
