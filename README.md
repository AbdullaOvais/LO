# Assignment: 1  
# Linear Optimization
**Subject Code**: CS5040  


---


**CS24MTECH12014** : Abdulla Ovais

---

### Assumptions:
1. Polytope is non-degenerate.
2. Polytope is bounded.
3. Rank of A is ` number of columns`.
4. Initial feasible point is given

---

Implement the simplex algorithm to maximize the objective function, You need to implement the method discussed in class.

---

### Input:
- CSV file with `m + 2` rows and `n + 1` columns.
  - The **first row** excluding the last element is the initial feasible point `z` of length `n`
  - The **second row**, excluding the last element, is the cost vector `c` of length `n`.
  - The **last column**, excluding the top two elements, is the constraint vector `b` of length `m`.
  - **Rows third** to m+2 and **column one to n** is the matrix `A` of size `m*n`.

---

### Output:
You need to print the sequence of vertices visited and the value of the objective function at that vertex.

---

### Instructions:
1. You need to implement in google Collab and share the link
2. Implementation language is Python
3. Input CSV file name is Testcase.csv from Collab workspace.

---
