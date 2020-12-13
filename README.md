# auto_reporting
フィヨルドブートキャンプの日報を自動投稿するプログラム

## 使い方
<code>report.rb</code>にログイン名とパスワードを記述。

<code>crontab -e</code>でエディタを起動し以下のフォーマットに沿ってcronを登録。

```
実行タイミング  Rubyのインストール場所  実行するRubyプログラムのフルパス
```

例
```
5 0 * * * /Users/mashio/.rbenv/shims/ruby /Users/mashio/auto-reporting/report.rb   
```
