### 14.5.2 Bit Sequence
* ***k***個の1が含まれる***n***ビット列は何個あるか？

`\[
\left(
\begin{array}{cccccccccc}
      \{& x_1 & & & x_4 & x_5 & & & & \} \\ 
      ( & 1, & 0, & 0, & 1, & 1, & 0, & 0, & 0 & ) 
\end{array}
\right)
\]`

* 上記の例の場合3個の1がある
  * ***k***個の1がある***n***ビット列の数は `$ \left( \begin{array}{c} n \\ k\end{array} \right) $`

<!-- The number of ways to select n donuts when k flavors are available is `$ \left( \begin{array}{c} n+(k-1) \\ n \end{array} \right) $` -->
