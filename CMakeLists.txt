cmake_minimum_required(VERSION 3.10)

# set the project name
project(SimpleTest)

add_subdirectory(one)
add_subdirectory(two)
set_target_properties(one PROPERTIES FOLDER "Utilities")
set_target_properties(two PROPERTIES FOLDER "Utilities")
add_subdirectory(three)