cmake_minimum_required(VERSION 2.8)
project(sandbox)

find_package(qibuild)

# Create a executable named sandbox
# with the source file: main.cpp
qi_create_bin(sandbox "main.cpp")

# Add a simple test:
qi_create_test(test_sandbox "test.cpp")
