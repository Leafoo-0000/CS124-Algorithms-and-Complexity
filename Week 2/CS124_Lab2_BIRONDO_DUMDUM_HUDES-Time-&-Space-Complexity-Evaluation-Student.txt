Answers:

Conceptual Understanding (20 points)

Time Complexity measures how an algorithm's runtime grows as the input size increases, expressed using asymptotic notation like O(n), for linear searches O(n) the worst case it checks every element once.

 Space Complexity measures how much memory an algorithm uses relative to input size., an O(1) is uses a constant amount of extra memory



Application of Asymptotic Notation (30 points)

a. a single loop running n times with a constant-time operation. The Time complexity is O(n) - Linear time

b. a nested loop running with both loops running n times. the Time complexity is O(n^2) - Quadratic 



Best, Worst, and Average Cases (20 points)

Scenario: Binary Search in a sorted array

-Best case: O(1) - this occurs when the target is in middle of the array.

-Average case: O(log n) - Occurs when the target is randomly located in the array, requiring about log₂ n comparisons.

-Worst case: O(log n) - Occurs when the target is at the first or last position, or not present, requiring the maximum number of comparisons (still logarithmic).



Real-World Application (30 points)

Situation: Optimizing a real-time navigation app (e.g., Google Maps) for route calculation.



Problem: Finding the shortest path between two points in a large road network using a naive approach (checking all possible paths) could take exponential time, making it unusable for real-time directions.



Solution with Complexity Analysis:



Using Dijkstra’s Algorithm with a priority queue reduces time complexity to O(E + V log V), where E is edges and V is vertices.


Understanding space complexity (O(V)) helps ensure the app can handle large maps without exhausting device memory.


Choosing efficient data structures (like adjacency lists) and algorithms enables fast, reliable navigation for millions of users simultaneously.


Impact: This leads to faster route calculations, lower battery consumption, and a smoother user experience—critical for a navigation app’s success.
