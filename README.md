# MartinezClipper
A C# implementation of a polygon clipping algorithm that enables several boolean operations (union, difference, exclusive-or and intersection) on polygons.

The code is based on an algorithm described in a paper from 2009 called: [*A new algorithm for computing Boolean operations on polygons by Francisco Martı́nez, Antonio Jesús Rueda and Francisco Ramón Feito*](http://www.cs.ucr.edu/~vbz/cs230papers/martinez_boolean.pdf).

The time complexity of this algorithm is __O((n + k) log n)__ where *k* is the number of intersections of all the polygon edges *n*. The authors of the paper claim that this algorithm is much faster than Vatti’s clipping algorithm for the computation of Boolean operations for large polygons due to their more efficient approach for dealing with intersections between edges.

Please note: Martínez published a new paper titled *A simple algorithm for Boolean operations on polygons* with a new version of the algorithm in 2013.
