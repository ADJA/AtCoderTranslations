[https://atcoder.jp/contests/arc004/tasks/arc004_3](https://atcoder.jp/contests/arc004/tasks/arc004_3)

Taro is finding average of posivite integers from 1 to N. For this he sums all numbers from 1 to N, and divides the sum by N.

Unfortunately, he forgot to include M (1 <= M <= N) in the sum, and calculated the wrong average. That is, he added all numbers 
from 1 to N except M, and divided the sum by N.

We only know the wrong average. Find all possible original numbers N and M.

---
Input
```
X / Y
```

1 <= X <= 10^18, 1 <= Y <= 10^9. The wrong average is the fraction X/Y (0 < X/Y <= 10^9).

Input is not necessary an irreducible fraction.

---
Output

```
N1 M1
N2 M2
```

Output all possible values N and M (1 <= M <= N) in ascending order of number N.
If there are no such values, output "Impossible"


