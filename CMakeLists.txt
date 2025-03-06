cmake_minimum_required(VERSION 3.30)
project(WashingMachineFSM)

set(CMAKE_CXX_STANDARD 20)

add_executable(WashingMachineFSM main.cpp
        state/State.h
        state/State.cpp
        transition/Transition.h
        transition/Transition.cpp)
