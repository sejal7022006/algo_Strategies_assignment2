🧠 Problem 3 – Sudoku Solver (Backtracking)

Algorithm: Recursive Backtracking
Domain: Gaming / Puzzle Solvers

🔹 Approach

Fill empty cells recursively while checking safety in row, column, and 3×3 box.

Backtrack when no valid placement exists.⚙ Complexities
Metric	Theoretical Complexity
Time	Exponential ≈ O(9ᴱ), E = # of empty cells
Space	O(N² + recursion depth)
📊 Observations

Time grows exponentially with the number of blanks.

Recursion depth adds moderate memory overhead.

Effective pruning significantly reduces runtime on real puzzles.
