# github action server has a cmake with version 3.25 on the windows-latest

cmake_minimum_required(VERSION 3.25)
project(learn_github_actions)
enable_language(CXX)

cmake_minimum_required(MSVC_VERSION 1.19)

add_executable(a main.cc)