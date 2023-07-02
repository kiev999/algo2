PROB 1:


The `FindDistinctSum` algorithm calculates the sum of distinct elements from two sets, `set1` and `set2`. It initializes the `distinctSum` variable to 0. The algorithm iterates through each element in `set1` and checks if it is distinct by calling the `isDistinct` function. If the element is distinct, it adds it to the `distinctSum`. The algorithm performs the same check for each element in `set2` and updates the `distinctSum` accordingly. Finally, it outputs the `distinctSum`. The `isDistinct` function compares an element with the elements in a set and returns `TRUE` if the element is distinct, and `FALSE` otherwise. The algorithm effectively solves the problem of finding the sum of distinct elements from two sets using arrays, nested loops, and the `isDistinct` function.


PROB 2:
The `dot_product` function calculates the dot product of two vectors `v1` and `v2` by iterating through their elements and summing the products. The result is returned as the output.

The `AreVectorsOrthogonal` algorithm takes an array of vectors as input. It iterates through all pairs of vectors using nested loops and calls the `dot_product` function to calculate the dot product of each pair. If the dot product is zero, it indicates that the vectors are orthogonal. The algorithm prints a message accordingly.