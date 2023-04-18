# A-Star-Path-Planning-using-Stage-simulator-ROS
## Mini Project developed for CSE3102 Simulation and Modeling Course

Autonomously plan and execute a path for a robot in the Stage simulator from a start location to a goal location, given a map.

This project deals with the A* Path planning algorithm in ROS visualization (Stage).

Steps to follow:

1. Create package inside 
    /catkin_ws/src/

    catkin_create_pkg astar std_msgs geometry_msgs rospy roscpp

2. Copy files inside package and follow:

    cd ~/catkin_ws
    catkin_make
    source ~/.bashrc

3. Grant execution permission to the script or .py file

    chmod +x <.py file directory>

4. Run program by roslaunch:

    roslaunch astar astar.launch
