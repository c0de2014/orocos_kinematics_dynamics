Orocos Kinematics and Dynamics Library (KDL)
============================================

## Building KDL

KDL and the Python KDL bindings can either be built normally with CMake, or they
can be built in an isolated [catkin](http://www.ros.org/wiki/catkin) workspace.

## Using KDL

The following  can be used to link against KDL in a CMake-based project:

```cmake
# Find the KDL Package
find_package(Orocos-KDL)
include_directories(${Orocos-KDL_INCLUDE_DIRS})
link_directories(${Orocos-KDL_LIBRARY_DIRS})

# add your target ...

# Link against KDL
target_link_libraries(my_target ${Orocos-KDL_LIBRARIES})
```
