
# Parallel Programming Course

## Overview

This repository serves as a central hub for projects completed as part of the Parallel Programming Course. It includes implementations of various parallel computing techniques using OpenMP, POSIX Threads (pthread), and SIMD. Each project is organized in its own submodule repository.

## Table of Contents

1. [Projects](#projects)
2. [Cloning the Repository](#cloning-the-repository)
3. [Usage](#usage)
4. [License](#license)

## Projects

The repository links to the following projects as submodules:

- **Parallel Minimum Element Finder in a Large Array Using SIMD, OpenMP, and Pthread Libraries**
- **Parallel Statistical Computation with Intel MMX SIMD, OpenMP, and Pthread Libraries**
- **Parallel Image Blending using the Same Three Libraries**


## Cloning the Repository

To clone this repository along with all the submodule projects, use the following command:

```sh
git clone --recurse-submodules https://github.com/mohasnik/Parallel-Programming-Course.git
```

If you've already cloned it, initialize and update the submodules with:

```sh
git submodule init
git submodule update
```

## Usage

Navigate into each project directory to see detailed instructions on compiling and running the parallel implementations.

## License

This repository is licensed under the MIT License. See the `LICENSE` file for more information.
