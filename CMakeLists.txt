cmake_minimum_required (VERSION 3.13)

project (btest LANGUAGES C)

add_executable (
  btest
    btest.c
    md5.c
    timing_mach.c
)
target_link_libraries (
  btest
    pthread
)
