add_library(MockTurtle mock_turtle.h mock_turtle.cc)
# set_target_properties(MockTurtle PROPERTIES LINKER_LANGUAGE CXX)
target_link_libraries(MockTurtle gmock_main Mock)

add_executable(mock_turtle_test mock_turtle_test.cc)
target_link_libraries(mock_turtle_test gtest_main gmock_main MockTurtle)
