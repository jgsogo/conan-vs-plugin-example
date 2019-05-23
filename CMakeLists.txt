cmake_minimum_required(VERSION 2.8)

set(CMAKE_CXX_STANDARD_LIBRARIES "$(CMAKE_CXX_STANDARD_LIBRARIES) %(AdditionalDependencies) ")

add_subdirectory(lib)
add_subdirectory(app)
