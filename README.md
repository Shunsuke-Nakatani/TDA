# TDA

### system1_Pigenerator
- python3.8で動作

- 取引記録を基に，NetworkXでグラフを作成，ノードの座標データにパーシステントホモロジーを適用しパーシステントイメージを生成します．提案システム1の前段階です．

### system1_classification
- VGG16の転移学習を用いた学習モデルを作り，2クラス分類をします．提案システム1の後段です．

- google colabで動かしていました．

### system2_graphmaker
- 取引記録から取引グラフ画像を生成します．提案システム2の前段階．

### system2_classification
- python3.9で動作

- Giotto-tdaというツールを用いて特徴量抽出と分類タスクをします．提案システム2の後段．
- 
- Giotto-tdaではPHの種類やフィルトレーション，分類器のカスタマイズが容易にできるので今後はこれを使えば楽だと思います．
