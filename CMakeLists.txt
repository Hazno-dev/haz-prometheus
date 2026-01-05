cmake_minimum_required(VERSION 3.31)
include(CMake/Platform/${PRO_PLATFORM}.cmake)

project(Prometheus
        DESCRIPTION "Research and Reverse-Engineering project of Overwatch!"
        HOMEPAGE_URL "https://github.com/BreakingBread0/prometheus")

include_directories(external)

include(CMake/Configure.cmake)
include(CMake/Version.cmake)

add_subdirectory(Prometheus-Core)