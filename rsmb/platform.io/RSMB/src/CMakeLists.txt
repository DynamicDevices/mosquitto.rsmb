# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

# Our custom source, then RSMB, then components
FILE(GLOB  app_sources ${CMAKE_SOURCE_DIR}/src/*.c
                       ${CMAKE_SOURCE_DIR}/../../src/*.c
                       ${CMAKE_SOURCE_DIR}/components/tft/*.c
                       ${CMAKE_SOURCE_DIR}/components/spidriver/*.c
)

idf_component_register(SRCS ${app_sources})
