cmake_minimum_required(VERSION 2.6)

project(libESDL)
set(LIBRARY_OUTPUT_PATH bin)

include_directories(include/SDL)

file(
        GLOB_RECURSE
        source_files
        src/*
)

add_library(
        ESDL
        STATIC
        ${source_files}
)

INSTALL_TARGETS(/lib ESDL)
INSTALL(FILES include/ESDL.h 
  DESTINATION include/SDL)