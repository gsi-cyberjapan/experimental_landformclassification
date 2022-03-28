experimental_landformclassification
================
国土地理院ベクトルタイル提供実験（地形分類）

# 地形分類の GeoJSON タイル
土地条件調査の成果、脆弱地形調査の成果及び治水地形分類図（更新版）を合成し、GeoJSONタイルに変換したものを提供実験いたします。

## 地形分類
### テンプレートURL：
- 地形分類（自然地形）
https://cyberjapandata.gsi.go.jp/xyz/experimental_landformclassification1/{z}/{x}/{y}.geojson
- 地形分類（人工地形）
https://cyberjapandata.gsi.go.jp/xyz/experimental_landformclassification2/{z}/{x}/{y}.geojson

- サンプル：
https://cyberjapandata.gsi.go.jp/xyz/experimental_landformclassification1/14/14555/6446.geojson

### ベクトルタイルスタイル定義： 
- 地形分類（自然地形） 
https://cyberjapandata.gsi.go.jp/xyz/experimental_landformclassification1/style.js
- 地形分類（人工地形） 
https://cyberjapandata.gsi.go.jp/xyz/experimental_landformclassification2/style.js

# データについて
「地形分類（自然地形）」は、ZL5～16において実データが表示されます。

「諸元情報（自然地形『詳細版』）」は、ズームレベル4～13のデータは、
おおよその範囲図ですので、実データではありません。

「地形分類（人工地形）」は、ズームレベル4～13のデータは、おおよその範囲図ですので、実データではありません。
ズームレベル14～16のデータが実データです。

- データ提供範囲とデータ仕様：
http://www.gsi.go.jp/bousaichiri/lfc_index.html

# デモサイトについて
デモサイトを次の場所に用意しております。
- 本レポジトリ
https://gsi-cyberjapan.github.io/experimental_landformclassification/
- 地理院地図
https://maps.gsi.go.jp/#14/38.304419/141.059046/&base=std&ls=std%7Cexperimental_landformclassification1%7Cexperimental_landformclassification2

# 提供の位置づけ
国土地理院ベクトルタイル提供実験におけるデータの提供の位置づけは次のとおりです。
- 本提供実験は、ベクトルタイル提供における技術的・施策的課題を国土地理院が把握するとともに、外部からの技術的な提案を受け取り、外部との技術的な議論を通じてベクトルタイルの適切な提供方法を研究開発することを目的とするものです。
- 本提供実験の期間は、2014年8月1日から本提供実験終了までとなります。
- 本提供実験のデータは、国土地理院コンテンツ利用規約( http://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html )に従って利用できます。
- 本提供実験のベクトルタイルは基本測量成果と位置付けているものではありませんが、基本測量成果としての提供を検討するにあたって、提供を行うものです。
- 本提供実験の利用により生じた損失及び損害等について、国土地理院はいかなる責任も負わないものとします。

# 履歴
2016-03-09 地形分類の提供実験を開始。  
2017-03-29「地形分類（自然地形）」及び「地形分類（人工地形）」の提供実験を開始。  
2022-03-28「地形分類（自然地形）」及び「地形分類（人工地形）」のデータを更新。前者については、ズームレベルに応じて『広域版』、『地域版』、『詳細版』を整備。
