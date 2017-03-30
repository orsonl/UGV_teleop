cmake_minimum_required(VERSION 2.8.3)
project(ugv_teleop)
find_package(catkin REQUIRED COMPONENTS
  dynamic_reconfigure
  image_transport
  message_generation
  roscpp
  sensor_msgs
  tf
)
find_package( OpenCV)
find_package( OpenCV REQUIRED )


include_directories(
  ${catkin_INCLUDE_DIRS}
  ${OpenCV_INCLUDE_DIRS}
  ${libcurl_INCLUDE_DIRS}
)

## Declare a C++ executable



