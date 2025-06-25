# Rubics_Cube
# Rubik's Cube Solver

This project is a Rubik's Cube solver built using C++. It includes:

- Multiple cube models (3D array representation, bitboards, etc.)
- Various solving algorithms like BFS, DFS, IDDFS, and IDA*
- A pattern database for efficient cube state lookup
- Clean modular structure with `Model`, `Solver`, and `PatternDatabase` folders

## Features

- Simulates cube moves (U, D, L, R, F, B with all variants)
- Random shuffle and print functionality
- Hashable cube state for search algorithms
- Easily extendable to different solving strategies

## How to Use

1. Clone the repo or download the source.
2. Compile the code using any C++ compiler with C++11 or above.
3. Run the desired solver implementation from the `Solver` folder.


