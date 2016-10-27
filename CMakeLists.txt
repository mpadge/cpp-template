cmake_minimum_required(VERSION 2.8.7)
project(junk CXX)
include_directories(include)
ADD_DEFINITIONS(
    -std=c++11 
)
#file(GLOB SOURCES "src/*.c++")
set(SOURCES3 src/junk.c++)

add_executable(junk ${SOURCES3})
target_link_libraries(junk boost_program_options stdc++)
