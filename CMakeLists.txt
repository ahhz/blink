cmake_minimum_required (VERSION 3.0)

set( gtest_force_shared_crt ON CACHE BOOL "Always use msvcrt.dll" FORCE)

project(blink)
add_subdirectory(iterator) 
add_subdirectory(raster)
add_subdirectory(map_algebra)
add_subdirectory(moving_window)
add_subdirectory(raster_tools)
add_subdirectory(resumable_dijkstra)
add_subdirectory(googletest) 
add_subdirectory(blink_test)