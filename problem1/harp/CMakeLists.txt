#Insert your code here :) (It's a trap!)

include_directories(../lib)
add_library(harplib harp.c)
target_link_libraries(harplib stringlib)