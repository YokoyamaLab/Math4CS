### 14.7.1 Hands with Four-of-a-kind

* ポーカーの<u>4カード</u>にはいくつの異なる手があるだろうか？

`$ \{8\spadesuit,8\diamondsuit,Q\heartsuit,8\heartsuit,8\clubsuit\} $`

`$ \{A\clubsuit,2\clubsuit,2\heartsuit,2\diamondsuit,2\spadesuit\} $`

* 決定要件
  1. 4枚のカードの**数**
  1. 残りの1枚のカードの**数**
  1. 残りの1枚のカードの**マーク**
* 上記要件は4カードの手の集合の全単射である。

---

#### 14.7.1 Hands with Four-of-a-kind (cont'd)

* 先ほどの<u>4カード</u>を列で表してみよう。

`$ (8,Q,\heartsuit) \leftrightarrow \{8\spadesuit,8\diamondsuit,8\heartsuit,8\clubsuit,Q\heartsuit \} $`

`$ (2,A,\clubsuit) \leftrightarrow \{2\clubsuit,2\heartsuit,2\diamondsuit,2\spadesuit,A\clubsuit \} $`

* 後はこの列の種類を数え上げるだけ
  1. 4枚のカードの**数**`$\rightarrow 13$`
  1. 残りの1枚のカードの**数**`$\rightarrow 12$`
  1. 残りの1枚のカードの**マーク**`$\rightarrow 4$`
* 答：`$ 624 $` (たった4265手に1手が<u>4カード</u>である)
