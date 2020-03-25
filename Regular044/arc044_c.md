[https://atcoder.jp/contests/arc044/tasks/arc044_c](https://atcoder.jp/contests/arc044/tasks/arc044_c)

Takahashi lives on a grid H x W (width is W, height is H). 1 <= W, H <= 10^5

There are Q beams shooting at the grid (0 <= Q <= 10^5). 
Each beam is described as (T, D, X):
T - time when beam is shot (1 <= T <= 10^5)
D - direction of the beam, 0 if vertical, 1 if horizontal
X - position of the beam. If D == 0, 1 <= X <= W; if D == 1, 1 <= X <= H.

For example beam (5, 0, 3) passes through the whole 3rd column at time 5.

Takahashi can start at any grid cell at time 0. He can at any time do a move to an adjacent cell (he cannot leave the grid) 
- this is counted as exactly 1 move. Takahashi cannot be hit by the beams. He can do any number of moves per unit of time.

If Takahashi can avoid all beams, print the minimum number of moves required, else print -1.

---

First test case:
Takahashi can start at (3, 2), then at time 1.5 move (3, 2)->(2, 2)->(2, 1), then at time 2.5 move (2, 1)->(1, 1). Total is 3 moves.
