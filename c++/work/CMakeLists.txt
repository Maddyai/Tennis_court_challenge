cmake_minimum_required(VERSION 2.8)
project( tennis )
find_package( OpenCV REQUIRED )
add_executable( tennis tennis.cpp )
target_link_libraries( tennis  ${OpenCV_LIBS} )
