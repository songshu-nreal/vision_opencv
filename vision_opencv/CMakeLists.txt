cmake_minimum_required(VERSION 2.8.3)
project(vision_opencv)
if(NOT ANDROID_NREAL)
    find_package(catkin REQUIRED)
    catkin_metapackage()
endif()
