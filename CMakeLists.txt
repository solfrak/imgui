cmake_minimum_required(VERSION 3.28)
project(ImGui)

set(CMAKE_CXX_STANDARD  17)

include_directories(./)
add_library(ImGui imgui.cpp imgui_tables.cpp imgui_widgets.cpp imgui_demo.cpp imgui_draw.cpp backends/imgui_impl_opengl3.cpp backends/imgui_impl_glfw.cpp)