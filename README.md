# AI-Problem-RA2411050050004
# Implementation of a Constraint Satisfaction-based Sudoku Solver for AI coursework
##  Sudoku Solver (Constraint Satisfaction Problem - CSP)

###  Problem Description
The goal of this project is to solve a 9×9 Sudoku puzzle using Artificial Intelligence techniques. The puzzle contains empty cells (represented by 0), and the objective is to fill them such that:

- Each row contains numbers from 1 to 9 without repetition
- Each column contains numbers from 1 to 9 without repetition
- Each 3×3 sub-grid contains numbers from 1 to 9 without repetition

This is modeled as a **Constraint Satisfaction Problem (CSP)**.

---

###  Algorithm Used
**Backtracking Algorithm (CSP approach)**

- Tries numbers from 1 to 9 in empty cells
- Checks constraints using:
  - Row validity
  - Column validity
  - 3×3 grid validity
- If a conflict occurs → **Backtrack**
- Continues until solution is found

---

### Execution Steps
1. Run the Python program
2. The predefined Sudoku grid is loaded
3. Empty cells (0) are identified
4. The algorithm tries valid numbers recursively
5. Backtracking ensures correct placement
6. Final solved Sudoku is displayed

---

###  Sample Output
[5, 3, 4, 6, 7, 8, 9, 1, 2]
[6, 7, 2, 1, 9, 5, 3, 4, 8]
[1, 9, 8, 3, 4, 2, 5, 6, 7]
[8, 5, 9, 7, 6, 1, 4, 2, 3]
[4, 2, 6, 8, 5, 3, 7, 9, 1]
[7, 1, 3, 9, 2, 4, 8, 5, 6]
[9, 6, 1, 5, 3, 7, 2, 8, 4]
[2, 8, 7, 4, 1, 9, 6, 3, 5]
[3, 4, 5, 2, 8, 6, 1, 7, 9]


---

###  Conclusion
The Sudoku Solver demonstrates how a **Constraint Satisfaction Problem (CSP)** can be effectively solved using the **Backtracking algorithm**. By systematically trying possible values and rejecting invalid choices, the algorithm ensures that all Sudoku constraints are satisfied.

This project highlights:
- Efficient problem-solving using recursion and backtracking  
- Importance of constraint checking in AI problems  
- Real-world application of CSP techniques  

Overall, the solution guarantees a correct and complete Sudoku grid whenever a valid solution exists, making it a reliable approach for solving such puzzles.


