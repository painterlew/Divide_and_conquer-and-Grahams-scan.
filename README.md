# divide_and_conquer-and-Graham-s-scan.
Purpose 
 parallelize a convex hull program with multiple processes to 
 improve efficiency.
 combination the algorithm of divide_and_conquer and Graham’s scan.

Divide_and_conquer
divides an entire problem into a tree of sub-spaces,
each small enough to be solved with an independent process.
Fork child processes in a tree as partitioning a problem with 
divide_and_conquer and let these processes work on their own 
sub-space in parallel.
