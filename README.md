# INF-PI
Kidney

All the codes for test are already in the main functions.

Steps to import the LpSolve library: 
1.Add the lpsolve55j.jar(in lib\lp_solve_5.5.2.11_java\lp_solve_5.5_java\lib) to your classpath.
2.Add the lpsolve55.dll(in lib\lp_solve_5.5.2.11_dev_win64) and lpsolve55j.dll(in lib\lp_solve_5.5.2.11_java\lp_solve_5.5_java\lib\win64) to the path Windows\system32 if you use the Windows operation system

Class explanation:
Data: All the data needed, including two initialising methodes, with path(testfile) or with a number to randomly generate data.
Branch_and_bound: to construct our relaxed LP problem and to construct a branch_and_bound algorithm.

Algorithms implemented:
algo1: direct donation
algo2: 2-way donation
algo3: cycle and w-chain with rule A and B by methode 3A and 3B
Algo_feasible_paths and DFS: two algorithms utilised in searching minimal infeasible paths
BB_algo: the ILP problem with Branch and Bound algo
ExamResults: for question 13 exam the final results
