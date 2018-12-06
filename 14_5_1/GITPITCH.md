### 14.5.1 The Subset Rule
* ***n***個から***k***個選ぶ問題を定式化する。
* 基本的な考え方
`\[
\frac{\mbox{全ての組み合わせ数}}{\mbox{同値と考えられる組み合わせ数}}
\]`
* n個のシーケンス全ての並べ方`$ \rightarrow n! $`
* k個のシーケンス全ての並べ方(同値)`$ \rightarrow k! $`
* K個取った残りの全ての並べ方(同値)`$ \rightarrow (n-k)! $`

---
#### 14.5.1 The Subset Rule (cont'd)

* ***n***個から***k***個選ぶ方法は

`\[
\left(
\begin{array}{ccc}
      n \\ 
      k 
\end{array}
\right)=\frac{n!}{k!(n-k)!}
\]`
