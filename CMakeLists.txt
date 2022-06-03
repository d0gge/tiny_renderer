cmake_minimum_required(VERSION 3.20)

set(PROJECT_NAME tiny_renderer)
project(${PROJECT_NAME})

add_executable(
  ${PROJECT_NAME}
  main.cpp
  tgaimage.cpp
  tgaimage.h
)
