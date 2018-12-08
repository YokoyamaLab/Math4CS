### 14.7.3 Hands with Two Pairs

* では<u>2ペア</u>はどうだろうか？

`$ \{3\diamondsuit,3\spadesuit,Q\diamondsuit,Q\heartsuit,A\clubsuit\} $`

`$ \{9\heartsuit,9\diamondsuit,5\heartsuit,5\clubsuit,K\spadesuit\} $`

---

#### 14.7.3 Hands with Two Pairs (cont'd)

* <u>2ペア</u>の成立要件を考える
  1. 最初のペアの**数** `$ \rightarrow 13$`
  1. 最初のペアの**記号** `$ \small{\rightarrow \left(\begin{array}{c}4\\2\end{array}\right)}$`
  1. 次のペアの**数** `$ \rightarrow 12$`
  1. 次のペアの**記号** `$ \small{\rightarrow \left(\begin{array}{c}4\\2\end{array}\right)}$`
  1. 残りのカードの**数** `$ \rightarrow 11$`
  1. 残りのカードの**記号**`$ \small{\rightarrow \left(\begin{array}{c}4\\1\end{array}\right)}$`

---

#### 14.7.3 Hands with Two Pairs (cont'd)

`\[
13\cdot\left(\begin{array}{c}4\\2\end{array}\right)\cdot 12\cdot\left(\begin{array}{c}4\\2\end{array}\right)\cdot 11 \cdot 4
\]`

- これでＯＫ？

- No!!

---

#### 14.7.3 Hands with Two Pairs (cont'd)


`\[
\begin{array}{ccc}
 (3,\{\diamondsuit,\spadesuit\},Q,\{\diamondsuit,\heartsuit\},A,\clubsuit) & \searrow & \\
 & & \{3\diamondsuit,3\spadesuit,Q\diamondsuit,Q\heartsuit,A\clubsuit\} \\
 (Q,\{\diamondsuit,\heartsuit\},3,\{\diamondsuit,\spadesuit\},A,\clubsuit) & \nearrow & \\
\end{array}
\]`

`\[
\begin{array}{ccc}
 (9,\{\heartsuit,\diamondsuit\},5,\{\heartsuit,\clubsuit\},K,\spadesuit) & \searrow & \\
 & & \{9\heartsuit,9\diamondsuit,5\heartsuit,5\clubsuit,K\spadesuit\} \\
 (5,\{\heartsuit,\clubsuit\},9,\{\heartsuit,\diamondsuit\},K,\spadesuit) & \nearrow & \\
\end{array}
\]`
