## VS Codeインストール

Vimを使い続けるのをあきらめてしまった。

Vimの設定を凝るようになったこの頃、設定ファイルをGithubに保存して、他のLinux環境でクローンするだけで使えるようにするという野望があった。

Pythonに加え、GoやHaskellといった言語の補完を自動でできるようにして、必要十分な理想の開発環境を築いていたが、Win10のWSLのUbuntu 18.04でうまく動いていた設定がGCPのUbuntu 18.04ではエラーだらけになった。

VS Codeは軽量で、WindowsだけでなくMacやLinuxでも動作するという話なので、Vimの代替案として検討すべきだろうということで、今回インストールしてみる。

### 1. インストーラをダウンロード

[ここ](https://code.visualstudio.com/)でインストーラをダウンロードし、起動する。

### 2. Vimのプラグイン

拡張機能検索で"vim"と検索し、インストールされている数の多いものを入れる。

再起動すると適用される。

### 3. プログラミング言語の開発環境構築

- [Python](https://github.com/cherryk98/install_vscode/blob/master/python.md)
- [Go](https://github.com/cherryk98/install_vscode/blob/master/go.md)
- [haskell](https://github.com/cherryk98/install_vscode/blob/master/haskell.md)

　

　

　

↓Markdownの書き方メモ

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
