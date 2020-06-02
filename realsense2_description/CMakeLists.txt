cmake_minimum_required(VERSION 3.5)
project(realsense2_description)

find_package(ament_cmake REQUIRED
    )

# RealSense description
ament_package(
    )

# Install files
install(DIRECTORY meshes urdf
  DESTINATION share/${PROJECT_NAME})
