cmake_minimum_required(VERSION 3.24)
project(tabu)

set(CMAKE_CXX_STANDARD 17)

add_executable(tabu main.cpp structures/Graph.cpp structures/Move.cpp structures/TabuList.cpp algorithm/Solution.cpp algorithm/TabuSearch.cpp utils/Timer.cpp)
