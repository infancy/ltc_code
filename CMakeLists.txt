cmake_minimum_required(VERSION 3.15)

project(LTC)

set(CMAKE_CXX_STANDARD 20)

include_directories(
  external/CImg
  external/glm
)

add_executable(fitLTC fit/fitLTC.cpp fit/dds.cpp)