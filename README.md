# Rover Simulation

## Usage

1. Clone the repo into your catkin workspace in the src folder
2. Then run catkin_make to compile all the packages
3. To launch the gazebo simulation , go into the fb_gazebo folder
4. Then run
```
roslaunch fb.launch
```
5. To launch the rviz simulation , open another terminal and , go into the fb_description folder
6. Then go into the launch folder inside fb_description folder and run
```
roslaunch fb_rviz.launch
```
7. Now open another terminal and run
```
rostopic list
```
8. The above command is for verifying that you have compiled the simulation correctly!
9. You will see camera topics , imu , and skid drive controller topics!
10. Now you can test by publishing commands to the rover and testing!

## Plugins

1. IMU
2. RGBD Camera
3. A Skid Drive controller
