##############################################################################
# CMake
##############################################################################

cmake_minimum_required(VERSION 2.8.3)
project(rocon_android_apps)

##############################################################################
# Catkin
##############################################################################

find_package(catkin REQUIRED rosjava_build_tools)
catkin_android_setup(assembleRelease)
catkin_package()


