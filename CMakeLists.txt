cmake_minimum_required(VERSION 2.8.3)
project(android_remocons)

find_package(catkin REQUIRED rosjava_tools)

catkin_android_setup(assembleRelease)

catkin_package()

