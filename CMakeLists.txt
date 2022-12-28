cmake_minimum_required(VERSION 3.23)
project(log4cplustest)

set(CMAKE_CXX_STANDARD 17)
find_package(log4cplus REQUIRED)
add_executable(log4cplustest main.cpp)
target_link_libraries(log4cplustest PRIVATE log4cplus::log4cplus)
add_subdirectory(tests)
