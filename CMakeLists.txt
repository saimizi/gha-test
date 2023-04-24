cmake_minimum_required(VERSION 3.10)

set(PROJECT_NAME gha-test)

project(${PROJECT_NAME} VERSION 0.1)

include(GNUInstallDirs)

add_subdirectory(src)
