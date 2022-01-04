add_library(Mock
    turtle.h painter.h painter.cc)

target_include_directories(Mock INTERFACE $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>)

