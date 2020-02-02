include_directories(${myGame_SOURCE_DIR}/include)

set (CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})


add_executable(myGame main.cpp)

target_link_libraries(myGame raylib)
