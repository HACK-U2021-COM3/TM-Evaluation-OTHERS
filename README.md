# インセプションデッキ

## 当日スライド
- https://www.canva.com/design/DAEpafhpR88/view?utm_content=DAEpafhpR88&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink

## プロジェクトの名前

[Ti.Me.Evaluation]

### 名前をつけた理由

- [時間を見積もるためのアプリだから。]
- [T.M.Revolutionが季節に合ってるから、ギリ夏だし。笑]
- [Yahoo! SAY,夏が 胸をHackする だから。]

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
- [ヤフー案内やGoogleMap]とは違って、
- [徒歩に限定した予定の見積もりや移動時間を可視化する機能]が備わっています。

<div style="page-break-before:always">
</div>

## 3\. パッケージデザイン

[Ti.Me.Evaluation]

[![Image from Gyazo](https://i.gyazo.com/b1f4cc9b1b4e578df3d07849b4494f64.jpg)](https://gyazo.com/b1f4cc9b1b4e578df3d07849b4494f64)

### 最高のキャッチコピー

[旅行は、良好に。トラベルは、トラブらないように。]

### ユーザーへのアピール => 最終的に喜んで使ってもらえるようにする。

1. [ユーザーに正確な距離(時間)を見積もることができる]
2. [次同じようにプランニングをするときに前回の見積もりを再利用できる]

<div style="page-break-before:always">
</div>


## 4\. 技術的な解決策の概要

[![アーキテクチャ図](https://i.gyazo.com/1aeb9a0796a109a42dd042699d807725.png)](https://gyazo.com/1aeb9a0796a109a42dd042699d807725)

[![Image from Gyazo](https://i.gyazo.com/5c7fc5e8a64668d5e595a7f05d440618.png)](https://gyazo.com/5c7fc5e8a64668d5e595a7f05d440618)

### 採用する技術
- クライアントサイド
    - ホスティングサービス: netlify
    - 言語(FW): React
    - CSS FW: chakra UI
- サーバーサイド
    - webサーバー: puma web server
    - appサーバー:
        - 言語(FW): Ruby on Rails
        - 外部サーバー: GoogleMapApi
        - 認証基盤: 0Auth2.0
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

## 5\. 夜も眠れなくなるような問題は何だろう？

- [フロントとバックエンドの通信ができるかどうか]
- [GoogleMapAPIの機能で直線ではなくルート案内での距離で出せるか]

<div style="page-break-before:always">
</div>


<div style="page-break-before:always">
</div>


## 6\. 何がどれだけ必要なのか

要素 | 値
--- | -----
人数 | 3名
期間 | 10日
予算 | $5
