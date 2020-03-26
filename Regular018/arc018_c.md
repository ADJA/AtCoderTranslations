[https://atcoder.jp/contests/arc018/tasks/arc018_3](https://atcoder.jp/contests/arc018/tasks/arc018_3)

Class has desks arranged in N rows and M columns.
Each desk is occupied by one student, each student has performance G[i][j].

You want to move more gifted students to the back of the class.
Specifically for two students at positions (a, b) and (c, d)
if a > b then G[a][b] >= G[c][d] should be true.

When a student moves from seat (a, b) to seat (c, d), he travels distance of |c - a| + |d - b|

You want to move students such that more gifted students are at the back of the class
(when a > b, G[a][b] >= G[c][d]), and total distance traveled by all students is minimized.

Find minimum total distance.

---

Input: \
N M \
x0 a p

1 <= N, M <= 1000 \
0 <= x0, a <= 10^9 \
N * M <= p <= 10^9, and p is prime

G[i][j] is generated as follows: \
for i == 0: x_i = x0 \
for i >= 0: x_i = (x_(i - 1) + a) MOD p

G[i][j] = x_(i * M + j)

---

Example 2: \
2 3 \
6 55 59 

Generated initial G[i][j] is: \
6 2 57 \
53 49 45 

