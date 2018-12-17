### 14.7.4 Hands with Every Suit

* 最後に全ての**記号**を持つ手札を考える

`$ \{7\diamondsuit,K\clubsuit,3\diamondsuit,A\heartsuit,2\spadesuit\} $`

* 成立要件
  1. 全ての**記号**が1枚ずつ `$ \rightarrow13^4 $`
  1. 残りのカードの**記号** `$ \rightarrow 4 $`
  1. 残りのカードの**数字** `$ \rightarrow 12 $`

`$ (7,K,A,2,\diamondsuit,3)\leftrightarrow\{7\diamondsuit,K\clubsuit,A\heartsuit,2\spadesuit,3\diamondsuit\} $`

---

#### 14.7.4 Hands with Every Suit (cont'd)

* ところがこれも全単射ではない
  * 以下の二手は同じである

`\[
\begin{array}{ccc}
 (7,K,A,2,\diamondsuit,3) & \searrow & \\
 & & \{7\diamondsuit,K\clubsuit,A\heartsuit,2\spadesuit,3\diamondsuit\} \\
 (3,K,A,2,\diamondsuit,7) & \nearrow & \\
\end{array}
\]`

* という訳でDivision Ruleに基づいて、答えは

`\[
\frac{13^4\cdot 4\cdot 12}{2} 
\]`
