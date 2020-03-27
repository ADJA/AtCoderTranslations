[https://atcoder.jp/contests/arc036/tasks/arc036_d](https://atcoder.jp/contests/arc036/tasks/arc036_d)

There are N cities in the country, and no roads. Biderectional roads will be built, each road will have some length.

Takahashi loves even numbers. For some cities A and B he wants to find if we can travel from A to B such that total distance
traveled is even. On his way, he can visit some vertices multiple times.

Help answer all Takahashi's queries

---
Input:

```
N Q
w1 x1 y1 z1
w2 x2 y2 z2
..
wQ xQ yQ zQ
```

1 <= N, Q <= 10^5 \
1 <= wi <= 2 \
1 <= xi, yi <= N, xi != yi \
1 <= zi <= 10^5

If wi is 1, then road between xi and yi of length zi is built.

If wi is 2, then you need to answer Takahashi's query if you can travel from ai to bi such that total 
distance traveled is even. In this case, zi = 1. \
For each such query, only roads stated before that query are already built.

---
Output:

For queries with wi == 2, output "YES" or "NO" depending on whether you can travel from ai to bi such that total 
distance traveled is even.






