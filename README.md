# Karnaugh-Map-Solver
The Karnaugh map, also known as the K-map, is a method to simplify boolean algebra expressions.
The required boolean results are transferred from a truth table onto a two-dimensional grid where the cells are ordered in Gray Code(00,01,11,10), and each cell position represents one combination of input conditions, while each cell value represents the corresponding output value.
Optimal groups of 1s or 0s are identified, which represent the terms of a canonical form of the logic in the original truth table. 
These terms can be used to write a minimal boolean expression representing the required logic.  
This project uses the principles of inheritence to create a 2 and 3 variable K-Map Solver.
(The main method of this project is located in KMapSolver)
