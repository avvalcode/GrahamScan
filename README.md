#graham_scan.py

A python implementation of the graham scan algorithm to find the convex hull of a set of points.

Implements a class, Point, for use in the graham_scan() function.

Sorts points with leftmost, lowest point first and then by slope to that point, ascending.

Gives convex hull starting with leftmost, lowest point and continuing counterclockwise.