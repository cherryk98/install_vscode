## HTML開発環境構築

HTMLもJavaScriptも、デフォルトで多くの機能が対応しているので、以下の内容のみ設定をする。

+ Emmetの基本テンプレートの"en"を"ja"に変更する。

+ 左側のエクスプローラでHTMLを右クリックしブラウザで開けるようにする。

### Emmetの設定変更

[File]→[Preferences]→[Settings]で設定を開き、"Emmet: Variables"という項目の"Edit in Settings.json"をクリック。

左側に開かれた設定ファイルの、"emmet.variables"の項目の右側にポインターを持っていき、ペンのアイコンをクリックする。

右側のユーザー設定に"emmet.variables"が追加されるので、追加された部分を以下のように編集する。

```
"emmet.variables": {
  "lang": "ja"
}
```

### ブラウザで開く

"View In Browser"というプラグインをインストールすると、ブラウザで開けるようになる。

ショートカット`Ctrl + F1`がエラーになったので、"view-in-browser"もインストールしたら改善された。
