cmake_minimum_required(VERSION 3.10)
project(main)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXX_FLAGS "-Wall -Wextra -Wpedantic -Werror")

set(SANITIZE_ADDRESS ON)

# find_package(Threads)

add_executable(main src/main.cpp)

# target_link_libraries(main Threads::Threads)
