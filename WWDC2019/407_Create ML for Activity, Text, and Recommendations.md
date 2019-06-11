# 407_Create ML for Activity, Text, and Recommendations

- 内容
  - テキスト分類
    - 感情分析
    - スパム
    - トピック
  - テキスト分類の転移学習デモ
    - ディレクトリ名のラベルは絵文字でもOK
    - 転移学習は時間がかかる（5分はかからない？）
    - Outputに入力すると、入力中でもリアルタイムで判定される
  - 転移学習とは?
    - 学習済みモデルを利用する
    - 昨年の画像分類だけでなくテキスト分類でも可能に
    - セマンティックな文章解析が可能
  - Tips
    - ユースケースにあったアルゴリズムを選ぶこと
      - Advances in Natural Language Frameworkのセッションで説明
    - クラスのバランス
    - データの一貫性（文章の長さなど）
  - アクティビティ分類
    - Jogging/Standing/Gesture/Gaming/Golf/Swimming...
    - Apple Watchでのフリスビーのモーション分類のデモ
    - CoreMotionのデータを利用
    - 1.1MBのモデルサイズしかない
  - モデルの学習方法
    - CSVデータから学習
    - Prediction Window Size（モーションの長さによって決める）
    - PrecisionとRecallの値からさらに学習すべきか判断する
    - Output
  - Recommender
    - これを買い忘れてませんか？の候補を出す
    - レシピと食材
    - Trail / Rating
    - カラムの種類: Group / Item / Rating
    - ハイキングに行った場所と評価を入力するアプリのデモ
    - Itemの関連性を学び、関連性グラフを構築する
    - CSVかJSONファイルから学習する
    - データがセキュアであることを保証する必要がある
    - ラボは金曜2時~

- 感想
  - テキスト分類はすぐ使えそう
  - アクティビティ分類の場合のデータの集め方がわからなかった
  - Reccomenderは学習の仕方のイメージがつかなかったのでまずは触ってみる

- メモ