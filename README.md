# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

ポップアップでウィンドウアラート内容の「こんにちは！」が実行された

## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」

ウィンドウアラートを実行しているが、Node.jsはクライアントサイドのプログラムではなくサーバーサイドの実行であり、Window.aleartをそもそも実行するウィンドウが無いためエラーになる

## Chromeデベロッパーツール：Consoleの実行結果

```
GGood morning.
index.html:18 おはよう！
```

## ターミナルの実行結果

```
(base) NeruMac:learning-javascript-01 kouki$ node node-main.js
Goodmorning, Node.js!!
```

