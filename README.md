#simple_exploration

This is a ROS catkin package that contains specific launch files (and other resources) to use autonomously explore and build a map

##Prerequisites / Installation

catkin package turtlebot_car

##How to use

### Autonomous exploration with Turtlebot

	# the following command runs phrontier_exploration
	# which publishes accessible frontiers to be explored 
	roslaunch simple_exploration simple_exploration_minimal.launch
	
	# this will send frontiers as goals to move_base
	rosrun simple_exploration simple_exploration


