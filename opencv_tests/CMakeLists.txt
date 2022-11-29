cmake_minimum_required(VERSION 2.8)
project(opencv_tests)

if(NOT ANDROID_NREAL)
    find_package(catkin REQUIRED)
    catkin_package()
endif()
