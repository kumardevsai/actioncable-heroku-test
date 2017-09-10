# WebPacker 3.0.1のHerokuエラー
- 問題
  - herokuがyarn0.22.0固定
  - webpacker3系は yarn0.25.2以上が必要
- 対策
  - herokuのbuildpackを修正
  - [こちらを参考](http://docs.komagata.org/5452)
