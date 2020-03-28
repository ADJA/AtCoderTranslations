[https://atcoder.jp/contests/arc015/tasks/arc015_3](https://atcoder.jp/contests/arc015/tasks/arc015_3)

You are given a unit conversion table. Write a program that will output how the largest unit can be 
expressed with the smallest unit.

For example
* 1 week = 7 day
* 1 day = 24 hour
* 1 hour = 60 min
* 1 min = 60 sec

Output 1week=604800sec 

---
Input format

```
N
large1 m1 small1
large2 m2 small2
...
largeN mN smallN
```

* 1 <= 200 <= N \
large_i = small_i * mi\
mi is an integer\
All unit names are lowercase strings up to 10 letters.
* When the largest unit expressed as the smallest unit as 1 largest unit = M smallest unit, M is integer not exceeding 10^9.
* Units from conversion tables all have different sizes.
* It's guaranteed that the largest and the smallest units can be specified from the input.
* Conversions in the input are given in no particular order. However, there are no contradictions.

--- 
Output format

If largest unit name is A, and smallest unit name is B, output

```1A=MB```

When A is M units of B.





