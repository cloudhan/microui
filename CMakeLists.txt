cmake_minimum_required( VERSION 3.6.1 )

include_directories(src)
link_libraries(OpenGL32)
add_executable(main ./demo/main.c ./demo/renderer.c ./src/microui.c)