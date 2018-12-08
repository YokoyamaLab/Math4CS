### 14.6.2 The Bookkeeper Rule

* 要素に重複のある列ではどうだろうか？
  * 10文字からなる**BOOKKEEPER**の構成要素は？
  
|  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  | 10  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  B  |  O  |  O  |  K  |  K  |  E  |  E  |  P  |  E  |  R  |

* つまり構成要素毎に分割すると

`\[
(\{\underbrace{1}_{B}\},\{\underbrace{2,3}_{O}\},\{\underbrace{4,5}_{K}\},\{\underbrace{6,7,9}_{E}\},\{\underbrace{8}_{P}\},\{\underbrace{10}_{R}\})
\]`

---
#### 14.6.2 The Bookkeeper Rule (cont'd)

* **BOOKKEEPER**を並び替えて得られる単語数は
`\[
\frac{\overbrace{10!}^{total\;letters}}{\underbrace{1!}_{B}\underbrace{2!}_{O}\underbrace{2!}_{K}\underbrace{3!}_{E}\underbrace{1!}_{P}\underbrace{1!}_{R}}
\]`

* この問題は次のように表現される
`\[
\left(\begin{array}{c}      k_1+k_2+\cdots +k_m \\       k_1,\cdots,k_m \end{array}\right)
\]`

<!--
`\[
\frac{20!}{5!)^4}
\]`
-->
