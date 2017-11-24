cmake_minimum_required(VERSION 3.8)
project(PTransE)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        PTransE_add/Test_TransE_path.cpp
        PTransE_add/Train_TransE_path.cpp
        PTransE_mul/Test_TransE_path.cpp
        PTransE_mul/Train_TransE_path.cpp
        PTransE_RNN/Test_TransE_path.cpp
        PTransE_RNN/Train_TransE_path.cpp)

add_executable(PTransE ${SOURCE_FILES} )