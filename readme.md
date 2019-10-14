# YouTube Ad Skip
(開発日：2019年10月15日)
Google Chrome 拡張機能の開発を行いました。

## 仕様
- 名称：「YouTube Ad Skip」
- 使用言語・ツール：JavaScript、json、
- 開発環境：Windows10

## 機能
- YouTubeのバナー広告および動画広告を自動でスキップ

## 説明
URLからホストを特定して、https://www.youtube.com/を含むURLのときだけ動作します。
「広告やバナーを消す」という処理を0.1秒ごとに行います。
広告動画の「5秒後にスキップ」にも5秒待たずとも、適用します。
Javascriptのプログラムファイルとは別に、manifest.jsonで拡張機能についての設定を記述しています。

## 参考記事
- [Chrome 拡張機能のマニフェストファイルの書き方](https://qiita.com/mdstoy/items/9866544e37987337dc79)
- [課金なんて必要ない？YouTubeの広告自動スキップ＆バナー自動削除のChrome拡張作ってみた](https://qiita.com/HirosuguTakeshita/items/fd1da5f6b727fbe611e4)