cmake_minimum_required(VERSION 2.8.3)
project(urdf_for_robot_modeling)

## Compile as C++11, supported in ROS Kinetic and newer
add_compile_options(-std=c++11)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED)

## A metapackage is used in a similar fashion as virtual packages are used
## in the debian packaging world. A metapackage simply references one or 
## more related packages which are loosely grouped together.
catkin_metapackage()
