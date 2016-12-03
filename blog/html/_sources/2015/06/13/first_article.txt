==================================
組み合わせの評価と正規順序の評価
==================================



.. author:: default
.. categories:: none
.. tags:: none
.. comments::

| basic : 組み込み作用素の場合 + - * /
| compound : 自分で定義した作用の場合 square etc
| 組み合わせの評価
| -basic 
| 正確評価
| 部分式の評価から
| -compound
| 正規順序の評価
| lazy 遅延評価
| ((define square x) (* x x ))
| [(square 2 )] not= [(square] [2]
| [(square 2 )] = [(* 2 2)]
| 置き換えモデル
| 関数の部分がシンボルだった場合は
| 展開できるかぎり展開してから評価する 
