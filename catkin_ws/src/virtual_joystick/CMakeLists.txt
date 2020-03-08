cmake_minimum_required(VERSION 2.8.3)
project(virtual_joystick)

find_package(catkin REQUIRED COMPONENTS
  duckietown_msgs
  roscpp
  rospy
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

#add_executable(robotik_virtual_joystick src/robotik_virtual_joystick_gui.py)
#target_link_libraries(virtual_jostick ${catkin_LIBRARIES})

