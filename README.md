#Basic pointers to keep in mind before going through the code
check about nodes in ros and rosrun commands

commands are rosnode,rosrun,rostopic (should check about possible info about it from pressing tab key twice).

rosrun turtlesim turtlesim_node used to dsipay turtle simulator window.

rostopic info /turtle1/cmd_vel
/turtle1/cmd_vel seems to be address of subscriptions created by command rosnode
rosmsg show geometry_msgs/Twist(some info on movement in space)
rosservice list gives list of services provided by turtle simulator.
rqt_graph is used to check for status of publisher and subscriber
rosrun turtlesim turtle_teleop_key to take input from arrow keys 

roslaunch launches multiple nodes at once

roslaunch sentinel_drone task_1.launch

sentinel_drone is name of package
task_1.launch is name of node
whycon is doing image image detection

In rostopic list only drone command is of use today
