project(hello)
cmake_minimum_required(VERSION 3.16)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(hello main.cpp)

Finally, the actual main.cpp file:

#include <iostream>

int main() {
    std::cout << "Hello world!" << std::endl;
    return 0;
}