# ANNapproximator

A program that takes in an equation as input

How to use:

Requires the 'python' programming language and the 'NumPy' library. I recommend downloading 'enthought canopy' which includes the library and also has a nice interface for editing the code.
One you create a copy on your computer, you can edit the designated variables. Those are denoted by comments.
To edit the equation input, edit the equation.py file. The file takes in an input x that the main program chooses, then it returns the value of x after passing through the equation. This value is used in the backpropagation training process.

After the entire program finishes running, the output will be written in the 'output.txt' in the format 

node_number,weight,threshold,

The variables that are editable (without leading to errors) are:
- Number of nodes in hidden layer
- Equation to approximate
- Backpropagation Training Step

Version 0.1

