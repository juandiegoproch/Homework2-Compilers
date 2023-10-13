cmake_minimum_required(VERSION 3.26)
project(homework_parser)

set(CMAKE_CXX_STANDARD 17)

add_executable(homework_parser svm_run.cpp svm_parser.cpp svm.cpp)
