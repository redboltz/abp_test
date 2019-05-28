cmake_minimum_required (VERSION 2.8.6)

message(STATUS "hello world")
# comment
message(STATUS "CMAKE_CURRENT_SOURCE_DIR:${CMAKE_CURRENT_SOURCE_DIR}")
message(STATUS "CMAKE_CURRENT_BINARY_DIR:${CMAKE_CURRENT_BINARY_DIR}")

include_directories(include)

# sub-directories
add_subdirectory (chat_server)
add_subdirectory (chat_client)
