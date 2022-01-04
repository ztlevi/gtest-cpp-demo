add_library(Turtle
    turtle.h painter.h painter.cc)

target_include_directories(Turtle INTERFACE $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>)

