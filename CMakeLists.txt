﻿cmake_minimum_required (VERSION 3.8)

project (chaosGame)

set(SOURCE_FILES
	main.cpp
	Setup.cpp
	CoreOperations.cpp
	PPMFileManager.cpp
)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable (${PROJECT_NAME} ${SOURCE_FILES})