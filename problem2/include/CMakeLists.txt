#Insert your code here :)

#all directories are in the current directory

add_library(myMessageLib message.c message.h)

add_library(myActionLib action.c message.h)
target_link_libraries(myActionLib myMessageLib)