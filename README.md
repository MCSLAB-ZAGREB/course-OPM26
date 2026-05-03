# Selected Topics in Mathematics 2025/2026

Course materials for Selected Topics in Mathematics

## Course webpage

Official course webpage at the University of Zagreb Faculty of Electrical Engineering and Computing:

- [Official FER course page](https://www.fer.unizg.hr/predmet/opm)
- [Instructor course page](https://www.fer.unizg.hr/zkist/djelatnici/dario_bojanjac/nastava/opm)

This repository contains Jupyter notebooks, Python code, exercises, and supporting materials for the course. The goal is to make all computational examples reproducible on Windows, macOS, and Linux.

## Course structure

The course is organized into three connected parts:

1. **Computational discrete mathematics**
   - enumeration of finite sets and combinatorial objects
   - generation of subsets, functions, permutations, and partitions
   - explicit computer construction of mathematical structures

2. **Mathematical modelling and numerical simulation**
   - function approximation
   - weak formulation of boundary value problems
   - finite element discretization
   - implementation of the finite element method for the Poisson problem and the heat equation

3. **Probability, Monte Carlo methods, and Markov chains**
   - introduction to Monte Carlo simulation
   - Markov chains and transition matrices
   - classification of states
   - limiting and stationary distributions
   - simulation of stochastic processes

## Repository structure


```text
course-OPM26/
├── README.md          # Main repository description and instructions
├── LICENSE            # License for course materials and code
├── pyproject.toml     # Python project configuration and dependencies
├── uv.lock            # Locked dependency versions for reproducibility
├── .python-version    # Python version used by uv
├── .gitignore         # Files and folders ignored by Git
│
├── notebooks/         # Jupyter notebooks used in lectures
├── lectures/          # Handwritten Lecture notes
└── homework/          # Homework assignments
```

## Requirements

Before using this repository, install:

- [Git](https://git-scm.com/downloads)
- [uv](https://docs.astral.sh/uv/getting-started/installation/)
- [Visual Studio Code](https://code.visualstudio.com/)

Check that Git and uv are installed:

```bash
git --version
uv --version
```

## Clone the repository

Choose a folder where you keep course materials and run:

```bash
git clone https://github.com/MCSLAB-ZAGREB/course-OPM26.git
cd course-OPM26
```

## Create the Python environment

Run:

```bash
uv sync
```

This creates the Python environment defined by the repository.