Efficient Solving of Fundamental Combinatorial Optimization Problems in AIMMS

Project Overview

This project implements and solves key combinatorial optimization problems using AIMMS. The goal is to efficiently tackle several well-known NP-hard problems, demonstrating the application of branch-and-bound algorithms, linear programming relaxations, and mixed-integer programming (MIP) solvers.


Problems Addressed

The following combinatorial optimization problems were solved:

Set Covering Problem
Implemented and solved for both small and large instances, including the LP relaxation and integer programming (IP) approaches (Branch-and-Bound).

Fixed Charge Transportation Problem
Modeled and solved using MIP, including comparisons of different problem sizes (with increasing depots and clients).

Uncapacitated Facility Location Problem (UFLP)
Formulated and solved with fixed and transportation costs, considering both MIP and LP relaxations.

Linear Assignment Problem (LAP)
Modeled as a classical LAP with a small instance (6 tasks and 6 people), solved using integer programming.


Methodology

Branch-and-Bound: Utilized to explore the solution space efficiently for NP-hard problems.

Linear Programming Relaxations: Used to approximate solutions by relaxing integer constraints and comparing computational performance.

Mixed-Integer Programming (MIP): Employed to handle both integer and continuous decision variables.
Software Used


AIMMS 24.4: AIMMS was used to model and solve the combinatorial optimization problems. The CPLEX solver was configured as the default to ensure efficient solving of MIP and LP problems.

Files Included
AIMMS Project Files: Four project folders, each corresponding to one of the exercises.
Solution Files: Generated solutions from AIMMS for each of the problems tackled, included in the repository.


How to Run

Clone the repository to your local machine.

Open AIMMS and load the relevant project folder.
