# statistics
Modules for statistics, hand-coded instead of using standard library modules. For "fun".

***

stats_and_regression.py is a generic statistics script used to calculate and print basic statistics including mean, variance, standard deviation, correlation coefficient, and a list of 3 points on a least squares regression line. It can also plot said regression line.

Each function can be called separately to pull out individual stats, or one can call print_statistics(x-values, y-values) to print the basic stats and return a list of 3 points with which to plot a least squares regression line for the given data. 