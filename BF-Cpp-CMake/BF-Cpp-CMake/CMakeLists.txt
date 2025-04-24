# CMakeList.txt : CMake project for BF-Cpp-CMake, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (BF-Cpp-CMake "BF-Cpp-CMake.cpp" "BF-Cpp-CMake.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET BF-Cpp-CMake PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
