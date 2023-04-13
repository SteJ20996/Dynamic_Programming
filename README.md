# Dynamic_Programming
This is my study report regarding to dynamic programming. 

Dynamic programming is a powerful optimization technique used in solving complex problems that exhibit two key properties: overlapping subproblems and optimal substructure. It essentially involves breaking down a problem into smaller subproblems, solving each subproblem just once, and storing the solutions to these subproblems to avoid redundant computation.

The essence of dynamic programming lies in the following aspects:

1. Overlapping Subproblems: Dynamic programming is most effective when a problem has overlapping subproblems, which means the same subproblems are being solved multiple times. By identifying and storing the solutions to these subproblems, dynamic programming helps to avoid redundant calculations and significantly reduces the overall time complexity.

2. Optimal Substructure: A problem exhibits optimal substructure if the optimal solution to the problem can be constructed from the optimal solutions of its subproblems. Dynamic programming takes advantage of this property by building the solution to the overall problem using the solutions to its subproblems.

3. Memoization (Top-Down Approach): One way to implement dynamic programming is through memoization, a technique that stores the results of expensive function calls and returns the cached result when the same inputs occur again. Memoization is a top-down approach, as it starts with the original problem and recursively breaks it down into smaller subproblems, caching the results along the way.

4. Tabulation (Bottom-Up Approach): Another way to implement dynamic programming is through tabulation, which is an iterative, bottom-up approach. It involves solving the subproblems first and building up the solution to the overall problem using a table to store the results of subproblems. Tabulation is generally more efficient than memoization, as it doesn't involve the overhead of recursion and solves subproblems in a specific order, ensuring that the subproblem solutions are available when needed.

By leveraging these key aspects, dynamic programming enables efficient problem-solving for a wide range of applications, such as sequence alignment, shortest path problems, and resource allocation.
