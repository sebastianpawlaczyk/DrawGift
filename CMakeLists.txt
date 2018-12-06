cmake_minimum_required(VERSION 3.10)
PROJECT(DrawGit CXX)


add_subdirectory(src/init)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME}
        DRAW_GIFT_LIB_init)
