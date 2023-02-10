# github action server has a cmake with version 3.25 on the windows-latest
# github action server has a msvc compiler with version 19.34.31937.0

cmake_minimum_required(VERSION 3.25)
project(learn_github_actions)
enable_language(CXX)

add_executable(a main.cc)
