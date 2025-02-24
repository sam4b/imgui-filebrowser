add_library(imfilebrowser STATIC "imfilebrowser.cpp" "imfilebrowser.h")

find_package(imgui CONFIG REQUIRED)
target_link_libraries(imfilebrowser PRIVATE imgui::imgui)
