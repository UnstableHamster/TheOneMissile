include_directories(SDL2_INCLUDE_DIR)
add_executable(tom main.c)
target_link_libraries(tom ${SDL2_LIBRARY})
