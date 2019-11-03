cmake_minimum_required(VERSION 3.13)
project(AmusementPark)

set(CMAKE_CXX_STANDARD 14)

add_executable(AmusementPark main.cpp Admin.cpp Admin.h Ride.cpp Ride.h User.cpp User.h Application.cpp Application.h)