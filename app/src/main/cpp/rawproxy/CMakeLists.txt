add_executable(rawproxy ${CMAKE_CURRENT_SOURCE_DIR}/rawproxy.cpp)
# mybinary, in this example, has mylib as dependency
# target_link_libraries( rawproxy mylib)
target_include_directories (rawproxy PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})