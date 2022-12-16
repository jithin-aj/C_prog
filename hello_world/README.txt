hello world

Building a sample project in CMAKE environment
---

The project is built on the CMAKE environment. Please go through the build Steps for building and
testing this project.

Cmake version used      : v3.22.1
Minimum version required: 3.10

Cmake reference: https://cmake.org
Cmake tutorial : https://cmake.org/cmake/help/latest/guide/tutorial/

Steps to build the project (Linux platform)
---
Step 1: Build the project
> cmake --build .

Below is the log shown if successfully built
[ 50%] Building C object path/main.c.o
[100%] Linking C executable <project_name>
[100%] Built target <project_name>

Step 2: Execute the project
> ./<project_name>

Output:
./hello_world
Hello world
