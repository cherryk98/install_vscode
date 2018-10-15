## Go開発環境構築

[このサイト](https://qiita.com/koara-local/items/8642d847831b6268d23e)を参考にした。

### Gitインストール

"go get"を利用するためにGitを入れる。

Windows用のGitは[ここ](https://gitforwindows.org/)でダウンロード。

### Goインストール

[ここ](https://golang.org/)でインストーラをダウンロード。

インストール後何もしなくても環境変数が設定されていたが、そうでなければ環境変数を設定する。

``` env
GOPATH=%USERPROFILE%\go
PATH=%GOPATH%\bin
```

### VS Codeの拡張

VS Code上でGoの拡張機能をインストールする。

また、インストールした拡張機能を動作させるために、以下のコマンドでGoのツール群を入れる。

``` command
go get -u -v github.com/nsf/gocode
go get -u -v github.com/rogpeppe/godef
go get -u -v github.com/zmb3/gogetdoc
go get -u -v golang.org/x/lint/golint
go get -u -v github.com/lukehoban/go-outline
go get -u -v sourcegraph.com/sqs/goreturns
go get -u -v golang.org/x/tools/cmd/gorename
go get -u -v github.com/tpng/gopkgs
go get -u -v github.com/newhook/go-symbols
go get -u -v golang.org/x/tools/cmd/guru
go get -u -v github.com/cweill/gotests/...
```

上のコマンドでインストールした後も、別のパッケージのインストールや更新を求められる場合はその都度従う。

### delveインストール

デバッガdelveをインストールする。

```
go get github.com/derekparker/delve/cmd/dlv
```
