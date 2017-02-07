$ cd dynamics_ws/
$ catkin_make
$ roscore
# open new terminal tab
# this opens moveit!
$ rosrun irb120_moveit moveit_planning_execution sim:=false robot_ip:=<insert_ip_of_abb_arm>
# open new terminal tab
$ rosrun camera_capture camera_capture_node
# open new terminal tab
$ rosrun irb120_tf_calc irb120_tf_calc_node
# open new terminal tab
$ rosrun moveit moveit_node
# open new terminal tab
$ rosrun irb120_perception_pickup irb120_perception_pickup_node
# open new terminal tab
$ rosrun chip_place chip_place_node

