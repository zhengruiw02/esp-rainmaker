# The following lines of boilerplate have to be in your project's CMakeLists
# in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.5)

# Set relative paths for application components
set(EXTRA_COMPONENT_DIRS ${CMAKE_CURRENT_LIST_DIR}/components ${CMAKE_CURRENT_LIST_DIR}/../../common)

# Include IDF-specific CMake functions
set(PROJECT_VER "1.0")
include($ENV{IDF_PATH}/tools/cmake/project.cmake)

# Define the project name
project(stickcplus_multi_device)

