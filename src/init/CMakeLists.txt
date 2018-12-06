set(lib_name DRAW_GIFT_LIB_)

PROJECT(${lib_name}init)

add_library(${PROJECT_NAME} STATIC)

target_sources(${PROJECT_NAME}
        PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}/Agent.hpp
        ${CMAKE_CURRENT_SOURCE_DIR}/Agent.cpp
        )

target_include_directories(${PROJECT_NAME}
    PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}
)
