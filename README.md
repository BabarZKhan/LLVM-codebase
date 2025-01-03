llvm-toy-compiler
==

The repo has a toy-compiler code from LLVM main website. It is caled “My First Language Frontend with LLVM” tutorial. Here we run through the implementation of a simple language, showing how fun and easy it can be. This tutorial will get you up and running fast and show a concrete example of something that uses LLVM to generate code.

This tutorial introduces the simple “Kaleidoscope” language, building it iteratively over the course of several chapters, showing how it is built over time. This lets us cover a range of language design and LLVM-specific ideas, showing and explaining the code for it all along the way, and reduces the overwhelming amount of details up front. We strongly encourage that you work with this code - make a copy and hack it up and experiment.


I am running it on my machine with the following configirutations:

## System Requirements (Linux)

-  Ubuntu 18.04
- Linux 5.4.0-51-generic
- gcc 9.3.0
- clang version 12.0.0

## System Requirements (Windows)

- 
-
-


## Compile (Linux)

run `clang++ -g -O3 toy.cpp llvm-config --cxxflags --ldflags --system-libs --libs core -o toy` 

## Compile (Windows)

run `clang++ -Wall .\toy.cpp -o .\toy`

# Resources
- [MLIR](https://mlir.llvm.org/)
- [MLIR-toy tutorial](https://mlir.llvm.org/docs/Tutorials/Toy/)
- [](https://github.com/skeru/LLVM-intro)
