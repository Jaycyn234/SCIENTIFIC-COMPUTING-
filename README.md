BIT 2118 Scientific Computing Group Work

This project implements the coded activities in the supplied assignment PDF. It contains Tasks 02–20; Data Science Essentials with Python is listed as a self-paced prerequisite rather than a program task.

Before Starting

- Complete the Data Science Essentials with Python prerequisite.
- Install Python 3.10 or later.
- Install the project dependencies.
- Run each task and review its explanation in "docs/task-guide.md".
- Record your discussion, screenshots, and individual GitHub repository link for VLMS submission.

The assignment specifies that discussion is group work, but each student must maintain and submit an individual GitHub repository. Do not submit a shared group repository as your individual submission.

Setup

Install the project dependencies:

python -m pip install -r requirements.txt

Run an individual task, for example:

python code/Task_02_numpy_arrays.py

Run the complete assignment check:

python -m unittest discover -s tests -v

Project Layout

- "code/" – Runnable Python programs for Tasks 02–20.
- "docs/" – Task explanations, interpretations and extensions.
- "outputs/" – Generated figures.
- "tests/" – Automated tests for the programs.

Tasks

Task| Topic
02| NumPy arrays and numerical computation
03| Mathematical functions and vectorization
04| Floating-point arithmetic and numerical errors
05| Matrix algebra and matrix operations
06| Systems of linear equations
07| Gaussian elimination and LU decomposition
08| Iterative methods for linear systems
09| Eigenvalues and eigenvectors
10| Bisection and fixed-point root finding
11| Newton-Raphson and secant methods
12| Polynomial and nonlinear equations
13| Interpolation
14| Curve fitting and approximation
15| Numerical differentiation
16| Numerical integration
17| Euler method for ODEs
18| SciPy ODE solution
19| Numerical optimization
20| Random numbers and Monte Carlo

Source Acknowledgement

Original source repository: https://github.com/braineydev/scientific-computing

This repository is maintained as an individual coursework copy. Original authorship and applicable licence notices are retained.