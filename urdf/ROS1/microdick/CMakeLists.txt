cmake_minimum_required(VERSION 3.0.2)
project(microdick)

find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY config launch meshes textures urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
  OPTIONAL
)
