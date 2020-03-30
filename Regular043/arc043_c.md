[https://atcoder.jp/contests/arc043/tasks/arc043_c](https://atcoder.jp/contests/arc043/tasks/arc043_c)

For two permutations X and Y of equal length, distance between them is the number of pairs that are in the reverse order in 
X and Y.

For example, distance between [3, 1, 4, 2, 5] and [2, 5, 3, 4, 1] is 7. The following pairs are in reverse order in X and Y:
* (1, 2), (1, 4), (1, 5), (2, 3), (2, 4), (3, 5), (4, 5)


You are given two permutations A and B of size N (1 <= N <= 10^5)

Find permutation C such that distance between A and C is equal to the distance between B and C.
If there are multiple answers, output any of them.

If there are no such permutations C, output -1.
