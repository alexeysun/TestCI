cmake_minimum_required(VERSION 2.8.7)

project(TestCI CXX)

set(${PROJECT_NAME}_SRC
	src/main.cpp
)

add_executable(${PROJECT_NAME} ${${PROJECT_NAME}_SRC})

set_property(TARGET ${PROJECT_NAME} PROPERTY CXX_STANDARD 11)
