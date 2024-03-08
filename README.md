# SAT-AI
This code is used to implement a propositional satisfiability solver program. Specifically, the code for the Custom solver was created for this project. Each solver (Custom, Random, Brute, GSAT, WalkSAT, and DPLL) will attempt to solve a series of SAT problems and be scored based on a number of criteria. The results are then compiled in results.html.

The purposes of each of the following files are stated below:

benchmarks - a folder containg all of the SAT problems that will be used

solvers - a folder containing all solvers that will attempt to solve the SAT problems
- custom.jar
- random.jar
- brute.jar
- gsat.jar
- walksat.jar
- dpll.jar

classes - a folder containing a Java class file
- CustomSolver.class

src - a folder containg the source code
- CustomSolver.java - implements the Custom solver

All other files under the src directory are part of an external SAT framework.

sat.jar - a program to test the provided solvers against a series of SAT problems

To compile and run the program, run the run-sat.bat file (Windows) or the run-sat.sh file (Mac/Linux).

To view the results, open the results.html file.

Code is available upon request.
