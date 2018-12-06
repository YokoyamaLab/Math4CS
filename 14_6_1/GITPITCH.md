### 14.6.1 Sequence of Subset

* ***n***要素集合から***k***要素部分集合を取り出す問題は、いわば***n***要素集合を***k***個と***n-k***個に2分割する問題である。
* これを一般化し `$ (k_1,k_2,\cdots ,k_m) $` 要素に分割分割する事を考える。
  * 分割した後の列は次のようになる：`$ A=(A_1,A_2,\cdots ,A_m) $`
* 例：`$ (a,b,c,d,e,f,g,h,i,j,k) $`を`$ (3,2,2,4) $`に分割
  * `$\rightarrow(\{a,b,c\},\{d,e\},\{f,g\},\{h,i,j,k\})$`

---
#### 14.6.1 Sequence of Subset (cont'd)

* `$ k_1+k_2+\cdots +k_m=nを満たすk_1,\cdots,k_m \in \mathbb{N} $`
* ***n***要素集合を`$k_1,\cdots k_m$`要素からなる***m***個の部分集合に分割する方法の総数は

`\[
\left(
\begin{array}{c}
      n \\ 
      k_1,k_2,\cdots,k_m
\end{array}
\right)::=\frac{n!}{k_1!k_2!k\cdots k_m!}
\]`
