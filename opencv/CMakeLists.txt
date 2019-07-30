
cmake_minimum_required(VERSION 3.10)
project(HogCode)
find_package(OpenCV REQUIRED)
add_executable(HogCode hog.cpp)
target_link_libraries(HogCode ${OpenCV_LIBS})
