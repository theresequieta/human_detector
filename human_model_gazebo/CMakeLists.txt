cmake_minimum_required(VERSION 2.8.3)
project(human_model_gazebo)

find_package(catkin REQUIRED roslaunch)

roslaunch_add_file_check(test/spawn_human_playpen.test.xml)
roslaunch_add_file_check(test/view_human.test.xml)
