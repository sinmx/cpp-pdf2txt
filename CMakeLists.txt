cmake_minimum_required(VERSION 2.8)
project( TDN )
find_package( OpenCV REQUIRED )
add_executable( tdn main.cpp )
target_link_libraries( tdn ${OpenCV_LIBS})
