cmake_minimum_required(VERSION 3.10.2)
project(PiscineC C)

set(CMAKE_C_STANDARD 99)



# Add an executable compiled from hello.c
add_executable(PiscineC main.c generate.h generate.c compare.h compare.c readXml.c readXml.h)

# Link the target to the GTK+ libraries
TARGET_LINK_LIBRARIES(PiscineC ${GTK3_LIBRARIES})