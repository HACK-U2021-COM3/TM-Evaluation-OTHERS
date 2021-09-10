# インセプションデッキ

## 当日スライド
- https://www.canva.com/design/DAEpafhpR88/view?utm_content=DAEpafhpR88&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink

## プロジェクトの名前

[Ti.Me.Evaluation]

### 名前をつけた理由

- [時間を見積もるためのアプリだから。]
- [T.M.Revolutionが季節に合ってるから、ギリ夏だし。笑]
- [Yahoo! SAY,夏が 胸をHack-Uする だから。]

<div style="page-break-before:always">
</div>

---
## 1\. 我われはなぜここにいるのか？

1. [技術的挑戦]
2. [RailsでOOP意識して開発したい]
3. [将来に繋がるモノを作りたい・使いたい]


### プロジェクトの根幹に関わる理由

**[遊び心を忘れずにみんなでやり抜く！]**


<div style="page-break-before:always">
</div>

---
## 2\. エレベーターピッチ
- [徒歩での移動時間の見積もりができるように]したい
- [デートや旅行に行く人]向けの、
- [Ti.Me.Evaluation]というプロダクトは、
- [経路のプランを見積もるアプリ]です。
- これは[徒歩での各地点ごとの移動時間が計測や、そこでの滞在時間を含めた合計時間の計算をすること]ができ、
- [ヤフー乗換案内やGoogleMap]とは違って、
- [徒歩に限定した予定の見積もりや移動時間を可視化する機能]が備わっています。

<div style="page-break-before:always">
</div>

## 3\. パッケージデザイン

[Ti.Me.Evaluation]

[![Image from Gyazo](https://i.gyazo.com/b1f4cc9b1b4e578df3d07849b4494f64.jpg)](https://gyazo.com/b1f4cc9b1b4e578df3d07849b4494f64)

### 最高のキャッチコピー

[旅行は、良好に。トラベルは、トラブらないように。]

### ユーザーへのアピール

1. [ユーザーに正確な距離(時間)を見積もることができる]
2. [次同じようにプランニングをするときに前回の見積もりを再利用できる]

<div style="page-break-before:always">
</div>


## 4\. 技術的な解決策の概要

### 技術構成
[![Image from Gyazo](https://i.gyazo.com/d2ba184026dc30958c8078943c32a1e5.png)](https://gyazo.com/d2ba184026dc30958c8078943c32a1e5)

### 採用する技術
- クライアントサイド
    - ホスティングサービス: Firebase
    - 言語(FW): React
    - CSS FW: chakra UI
- サーバーサイド
    - webサーバー: puma web server
    - appサーバー:
        - 言語(FW): Ruby on Rails
        - 外部サーバー: GoogleMapApi
        - 認証基盤: OAuth2.0
    - dbサーバー: postgresql
- インフラ: heroku
- そのほか
    - CI: GithubActions 
        - RSpec
        - Rubocop
    - プロジェクト管理: GithubProjects, Notion
    - アイデア: インセプションデッキ 
    - UML: draw.io
    - ERD: DrawSQL
    - api設計: swagger

<div style="page-break-before:always">
</div>


## 5\.開発工程
1. プロダクトバックログ(ユーザーストーリー)を作成し簡単な見積もりを行う
2. プロダクトバックログ内でイメージしづらい処理はアクティビティ図をかく
3. 画面遷移図をかく
4. 機能設計書をかく
5. ERDをかく
6. API仕様書をかく
7. アーキテクチャ図をかく
8. かんばん方式によるタスク管理


### 1. プロダクトバックログ(ユーザーストーリー)を作成し簡単な見積もりを行う
[![Image from Gyazo](https://i.gyazo.com/42be80b1d87530159bcae994cb7f5834.png)](https://gyazo.com/42be80b1d87530159bcae994cb7f5834) 

### 2. プロダクトバックログ内でイメージしづらい処理はアクティビティ図をかく
[![Image from Gyazo](https://i.gyazo.com/ee193f31289520f7a580bace82c5abae.png)](https://gyazo.com/ee193f31289520f7a580bace82c5abae)

### 3. 画面遷移図をかく
[![Image from Gyazo](https://i.gyazo.com/a9ebdb3738d69752bf9e95f6a4a05f76.png)](https://gyazo.com/a9ebdb3738d69752bf9e95f6a4a05f76)

### 4. 機能設計書をかく
[![Image from Gyazo](https://i.gyazo.com/70dd000a5f951e76ee3afe92ce5b190a.png)](https://gyazo.com/70dd000a5f951e76ee3afe92ce5b190a)

### 5. ERDをかく
[![Image from Gyazo](https://i.gyazo.com/fe27d4f7c026a7c92fa9b2d9a352ec23.png)](https://gyazo.com/fe27d4f7c026a7c92fa9b2d9a352ec23)

### 6. API仕様書をかく
[![Image from Gyazo](https://i.gyazo.com/07a0af426c054089ad1c71b23016fdcf.png)](https://gyazo.com/07a0af426c054089ad1c71b23016fdcf)

### 7. アーキテクチャ図をかく
[![アーキテクチャ図](https://i.gyazo.com/1aeb9a0796a109a42dd042699d807725.png)](https://gyazo.com/1aeb9a0796a109a42dd042699d807725)

### 8. かんばん方式によるタスク管理
[![Image from Gyazo](https://i.gyazo.com/366f68b6fc4851ce6246e8a56eee5582.png)](https://gyazo.com/366f68b6fc4851ce6246e8a56eee5582)
