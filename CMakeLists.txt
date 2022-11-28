cmake_minimum_required(VERSION 3.23)
project(eloadas11_hetfo)

set(CMAKE_CXX_STANDARD 20)

add_executable(eloadas11_hetfo main.cpp Student.h Student.cpp GraduationDao.h GraduationDaoImpl.h GraduationDaoImpl.cpp)
