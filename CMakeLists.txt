cmake_minimum_required( VERSION 3.5 )

project( hashes )

### c++11 standards
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable( test_hashes main.cpp )