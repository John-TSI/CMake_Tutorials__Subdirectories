add_library(say_hello src/library/hello.hpp src/library/hello.cpp)

target_include_directories(say_hello PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/src")
