# Equation-Solver
This Python project helps solve linear and quadratic equations using object-oriented programming (OOP).

What It Does

Solves equations like 2x + 3 = 0 and x² + 2x + 1 = 0

Tells you more info like slope or shape of the curve

Neatly formats the results so they look clean and easy to read

Main Parts

Equation (base class)

Used by both linear and quadratic equations

Checks if input values are valid

Gives a readable equation string

LinearEquation

Solves ax + b = 0

Tells you the slope and y-intercept

QuadraticEquation

Solves ax² + bx + c = 0

Tells you:

If it opens upwards or downwards

Whether it has a min or max

Where the vertex is

solver(equation)

This function:

Checks the input

Prints the type of equation

Solves and shows the answer(s)

Shows details about the equation

