#Insert your code here :)

include_directories(../include/)

add_executable(hello.elf main.c)
target_link_libraries(hello.elf myActionLib myMessageLib)