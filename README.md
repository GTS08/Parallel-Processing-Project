# Parallel Processing Project
This project is part of the Computer Engineering and Informatics Department (CEID) of University of Patras curriculum.

## Summary
The goal of this project was to implement the parallel version of the Kahn algorithm in order to find the topological order of a given graph. This was done using C and the OpenMP API. More specifically, a subset of OpenMP API called tasks were used in order to achieve the parallelization of the algorithm.

### Compilation
gcc -o kahnAlgorithm -O0 -fopenmp kahnAlgorithm.c functions.c linked_list.c

### Run
./kahnAlgorithm x

Where x is the number of threads.

