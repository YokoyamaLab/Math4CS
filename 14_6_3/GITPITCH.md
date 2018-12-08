### 14.6.3 The Binominal Theorem

`\begin{eqnarray*}
(a+b)^4 &=& aaaa+bbbb+aaba+aabb \\
        & & +abaa+abab+abba+abbb \\
        & & +baaa+baab+baba+babb \\
        & & +bbaa+bbab+bbba+bbbb
\end{eqnarray*}`

* **a**と**b**の4文字からなる全ての列の足し算(`$2^4$`通り)
* k個の**b**とそれ以外の**a**への分割

`\[
\frac{n!}{k!(n-k)!}=\left(
\begin{array}{c}
  n \\
  k
\end{array}
\right)
\]`

---

#### 14.6.3 The Binominal Theorem (cont'd 1)

* `$n=4$`で`$k={0,1,2,3,4}$`なので

`\[
\tiny{
(a+b)^4=\left(\begin{array}{c}  4 \\  0 \end{array}\right)\cdot a^4b^0+\left(\begin{array}{c}  4 \\  1 \end{array}\right) \cdot a^3b^1+\left(\begin{array}{c}  4 \\  2 \end{array}\right)\cdot a^2b^2\left(\begin{array}{c}  4 \\  3 \end{array}\right)\cdot a^1b^3+\left(\begin{array}{c}  4 \\  4 \end{array}\right)\cdot a^0b^4
}
\]`
* ここで　`$ a^4\cdot b^0 \rightarrow aaaa $`に着目しよう。

`\[
\left(
\begin{array}{c}
  4 \\
  0
\end{array}
\right)=\frac{4!}{0!(4-0)!}=\frac{4!}{4!}=1
\]`

* 前頁の式でaaaaは何個あった？→**1個**

---

#### 14.6.3 The Binominal Theorem (cont'd 2)

`\[
\tiny{
(a+b)^4 &=& \left(\begin{array}{c}  4 \\  0 \end{array}\right)\cdot a^4b^0+\left(\begin{array}{c}  4 \\  1 \end{array}\right) \cdot a^3b^1+\left(\begin{array}{c}  4 \\  2 \end{array}\right)\cdot a^2b^2\left(\begin{array}{c}  4 \\  3 \end{array}\right)\cdot a^1b^3+\left(\begin{array}{c}  4 \\  4 \end{array}\right)\cdot a^0b^4 \\
&=& 1a^4+4a^3b+6a^2b^2+4ab^3+1b^4
}
\]`

*　これを一般化すると二項定理になる

`\[
(a+b)^n=\sum_{k=0}^{n}\left(\begin{array}{c}  n \\  k \end{array}\right)a^{n-k}b^k
\]`

* nは自然数、a,bは実数

---

#### 14.6.3 The Binominal Theorem (cont'd 3)

*　BOOKKEEPERも同様だ

`\[
(b++k+e+*p+r)^10 = \cdots + bo^2k^2e^3pr + \cdots
\]`

*  `$ bo^2k^2e^3pr $`の係数は以下となる

`\[
\left(\begin{array}{c}  10 \\  1,2,2,3,1,1 \end{array}\right)=\frac{10!}{1!2!2!3!1!1!}
\]`

* これは多項定理、係数を多項係数という。

`\[
\tiny{
(z_1+z_2+\cdots +z_m)^n=\sum_{\begin{array}{c} k_1,\cdots,k_m\in N \\ k_1+\cdots +k_m=n\end{array}}\left(\begin{array}{c}n \\ k_1,k_2,\cdots ,k_m\end{array}\right)Z_1^{k_1}Z_2^{k_2}\cdots Z_m^{k_m}
}
\]`
