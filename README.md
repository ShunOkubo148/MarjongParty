# MarjongParty
麻雀大会運営支援ツール　2019年7月までに動く形にし、2020年3月までに最終型にしたい

仕様（以下Keepのコピペ）

○成績集計発表機能
-名前と点棒の額を入れるだけで自動でスコアに変換、データ化、集計してランキングにして発表
-入力フォームはWebページ化されるのでリンクを共有するだけでみんなアクセスできる
-現在のランキングはページに書くよりも外部出力してみんなで観れた方がいいかも
-点棒の設定額と打ち込まれた値の和が合わなければエラーを返すので「○○点足りない」がもう起きない！

○ルール設定機能
-ウマオカ、供託扱いなど事前にルールなどをカスタム可能
-ルール表を周知できる(Webページ化してリンクを共有)
-ルール管理や成績管理は幹事のみがアクセスできるので荒らしの心配なし！

○卓組み表生成機能
-選手名を入れるだけで卓組みを自動生成
-例によってリンクで公表
-個人ごとの卓移動表も見れる
-チーム戦にも対応

○タイマー機能
-制限時間付き対局に対応
-プロジェクター出力でみんな見れる
-0:00になった時、〜分前に通知

○クライアントアプリ(選手用アプリ)
-[現在の全体ランキング/個人成績と卓組み/対局タイマー]をタブ切り替えで観れる
-編集機能はあまりない(並び替える程度)
-個人認識は名前を入れるなど

○ホスト用アプリ(運営用アプリ)
-選手、成績、卓組み、タイマー、ルール、その他設定などをいじれる
-パスワード制
-運営の領域と選手の領域を分けることで荒らし防止
