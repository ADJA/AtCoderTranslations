[https://atcoder.jp/contests/arc042/tasks/arc042_d](https://atcoder.jp/contests/arc042/tasks/arc042_d)

You are given four integers, X, P, A, B (1 <= X < P < 2^31, 0 <= A <= B < 2^31), P is a prime number.

Find minimum value of X^i MOD P, for all A <= i <= B.

Sample 1 doesn't affect the score.
The rest of the tests are generated using [this C++ program](https://atcoder.jp/img/arc/042/adafrrg/generator.cpp).

Test #i is generated with the program with first command line argument i. \
For example test 321 is generated with the generator called with command line argument 321.

Tests for i from 1 to 10000 are [this file](https://atcoder.jp/img/arc/042/adafrrg/input.txt). \
All tests used for system testing match one of the lines in this file.

---
Test 1

```2 11 3 9```

X^i MOD P is 8, 5, 10, 9, 9, 7, 3, 6 for 3 <= i <= 9. Output is the minimum of them, 3.
