# OpenGL-Projects

Sample Project of OpenGL and for references 

Requirement to compile the source code:
1. Linux Operating System or mingw64 
2. GNU Make or GNU GCC or g++ compile
3. GLFW library
4. Glad - a library that helps in loading OpenGL function pointers at runtime, as these functions are not known at compile time
https://glad.dav1d.de/

Each examples has Makefile special text file that you can read how to compile the source code, for example: 

```c
gcc -Wall -g hello.c -o hello -lglfw -lGL
```

How to run make file? 

To execute a make file, simply navigate to the directory containing the `Makefile` in your terminal and type `make`. 
If there is a  specific target (e.g., "build"), you can specify it with `make build`.
Makefiles are used by the make utility to automate tasks like compiling code, and they define dependencies and commands to execute.

Here is a YouTube video that explain it well how to use GNU Make https://www.youtube.com/watch?v=mQupK2oTPF4
