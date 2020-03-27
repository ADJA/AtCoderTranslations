[https://atcoder.jp/contests/arc044/tasks/arc044_d](https://atcoder.jp/contests/arc044/tasks/arc044_d)

For string S, suffix array contains starting indexes of all suffixes in the string, after the suffixes are sorted.

For example, for string AABA, suffix array is [3, 0, 1, 2], because A < AABA < ABA < BA.

You are given a number N (1 <= N <= 10^6), and a permutation A of length N (for 1 <= i <= N, 1 <= A_i <= N).
Find the lexicographically smallest string S that has A as its suffix array.

Output S, or -1 if such S doesn't exist.
