# OPTIMIZATION-MODEL
📌 Project Title: Product Mix Optimization
🧾 Objective:
The goal of this project is to solve a business optimization problem using Linear Programming (LP). We aim to determine the optimal number of two products a factory should produce to maximize profit, given limited production time.

🧠 Problem Overview:
A factory produces two types of products: Product A and Product B.

Product A requires 3 hours per unit and yields a profit of $20.

Product B requires 2 hours per unit and yields a profit of $15.

The factory has a total of 120 hours available.

We need to find out how many units of each product should be produced to maximize total profit, without exceeding the available production time.

🧰 Tools & Libraries Used:
Python – Programming language for building the model.

PuLP – A powerful linear programming library in Python for optimization problems.

🔧 Steps Performed:
Defined the Optimization Problem
Created a linear programming model to maximize profit.

Set Decision Variables
Let x be the number of Product A units and y be the number of Product B units.

Defined Objective Function
Maximize:
20 * x + 15 * y → (profit from Product A and B)

Added Constraints

3x + 2y ≤ 120 → Time constraint (hours available)

x, y ≥ 0 → Cannot produce negative units

Solved the Problem
Used PuLP’s solver to find the optimal values of x and y.

Interpreted Results
Displayed the number of units to produce and the corresponding maximum profit.

✅ Outcome:
The solution provides the optimal production strategy that maximizes profit within the time constraints. This kind of model helps businesses make informed decisions in resource allocation and planning.
