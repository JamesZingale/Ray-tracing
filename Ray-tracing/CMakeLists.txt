﻿# CMakeList.txt : CMake project for Ray-tracing, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (Ray-tracing "Ray-tracing.cpp" "Ray-tracing.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET Ray-tracing PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
