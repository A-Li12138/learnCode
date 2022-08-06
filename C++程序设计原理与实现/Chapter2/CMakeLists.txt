cmake_minimum_required(VERSION 3.10)

project(HelloWorld)

set(CXX_STANDARD 14)
set(CXX_STANDARD_REQUIRED True)

add_executable(main main.cpp)

target_include_directories(
    main PUBLIC 
    ${CMAKE_SOURCE_DIR}/../cmn
)