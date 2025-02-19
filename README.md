# TDA

### system1_Pigenerator
python3.8で動作

取引記録を基に，NetworkXでグラフを作成，ノードの座標データにパーシステントホモロジーを適用しパーシステントイメージを生成します．

### system1_classification
VGG16の転移学習を用いた2クラス分類をします．

### system2_graphmaker
取引記録から取引グラフ画像を生成します．

### system2_classification
python3.9で動作

Giotto-tdaと呼ばれるツールを用いて分類します．Giotto-tdaではPHの種類やフィルトレーション，分類器のカスタマイズが容易にできるので今後はこれで調査すると楽だと思います．VGG16はないですが
