# python-interfaces
Tutorials for wrapping C++ code with python by 'extending'. Each folder is a tutorial in it's own.

## Tutorial Guide
Since each folder is a tutorial and they have pretty random names, so if you are just gettgin started or exploring start reading folder descriptions:

1. `/rectangle`: writing a simple `Rectangle` class in C++ and `PyRectangle` class in Cython to initialise with some values and return certain attributes.

2. `/pybind11_ex`: examples built using pybind11 library based on boost, simpler does not use `cmake`.

3. `/account`: simple account transaction module, uses pybind11 and uses `cmake`.

4. `/game_sample`: taking experimentation to another level by creating a small world built using multiple files. Learned how to build bigger projects and not just a few files. Proper foldering and compilation using `cmake` and `make`. The idea is to see if multiple files can be used to make package cython.

## Links

#### Youtube Links:

1. [CppCon 2016: “Introduction to C++ python extensions and embedding Python in C++ Apps"](https://www.youtube.com/watch?v=bJq1n4gQFfw)

2. [Ivan Smirnov - pybind11 - seamless operability between C++11 and Python](https://www.youtube.com/watch?v=jQedHfF1Jfw)