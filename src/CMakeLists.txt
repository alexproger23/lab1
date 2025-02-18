add_library(utils utils.hpp utils.cpp)
add_executable(main main.cpp)
target_link_libraries(main utils)