## VS Codeインストール

VS Codeのインストール・設定メモ。

Vimからの乗り換えだから、Vimのキーバインドとプログラミング言語の設定をする。

### 1. インストーラをダウンロード

[ここ](https://code.visualstudio.com/)でインストーラをダウンロードし、起動する。

### 2. Vimのプラグイン

拡張機能検索で"vim"と検索し、インストールされている数の多いものを入れる。

再起動すると適用される。

### 3. プログラミング言語の開発環境構築

- [Python](https://github.com/cherryk98/install_vscode/blob/master/python.md)
- [Go](https://github.com/cherryk98/install_vscode/blob/master/go.md)
- [HTML](https://github.com/cherryk98/install_vscode/blob/master/html.md)
- [CSS](https://github.com/cherryk98/install_vscode/blob/master/css.md)

環境が整ったら、`F5`でデバッグ、`Ctrl+F5`で実行。

### 4. キーボードショートカット

好みのキー設定。

VS Code左下の歯車アイコンから"keyboard shortcuts"を選択。

+ "cursorLeft"に`Ctrl+H`を割り当て、移動できるようにする。

+ "cursorRight"に`Ctrl+L`を割り当て、移動できるようにする。

+ "list.focusDown"に`Ctrl+J`を割り当て、補完候補を選べるようにする。

+ "list.focusUp"に`Ctrl+K`を割り当て、補完候補を選べるようにする。

+ "editor.action.format"に`Ctrl+F`を割り当て、フォーマットできるようにする。

+ "workbench.action.openNextRecentlyUsedEditorInGroup"に`Ctrl+Space`を割り当て、タブを選べるようにする。

設定後、"keybindings.json"を開いて、余計な設定を削除し手直しする。

以下のような設定ファイルになる。

```
// Place your key bindings in this file to overwrite the defaults
[
    {
        "key": "ctrl+h",
        "command": "cursorLeft",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+l",
        "command": "cursorRight",
        "when": "textInputFocus"
    },
    {
        "key": "ctrl+j",
        "command": "list.focusDown",
        "when": "listFocus && !inputFocus"
    },
    {
        "key": "ctrl+k",
        "command": "list.focusUp",
        "when": "listFocus && !inputFocus"
    },
    {
        "key": "ctrl+f",
        "command": "editor.action.format"
    },
    {
        "key": "ctrl+space",
        "command": "workbench.action.openNextRecentlyUsedEditorInGroup"
    }
]
```
