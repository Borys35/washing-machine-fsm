cmake_minimum_required(VERSION 3.30)
project(WashingMachineFSM)

set(CMAKE_CXX_STANDARD 20)

add_executable(WashingMachineFSM main.cpp
        State.h
        State.cpp
        Transition.h
        Transition.cpp
        FSM.h
        FSM.cpp
        WashingMachine.cpp
        WashingMachine.h)
