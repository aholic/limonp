PROJECT(LIMONP)

cmake_minimum_required(VERSION 2.8)

ADD_DEFINITIONS(-std=c++0x -O3)
ADD_SUBDIRECTORY(limonp)
ADD_SUBDIRECTORY(test)

#ENABLE_TESTING()
