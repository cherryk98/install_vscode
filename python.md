## Python開発環境構築

Pythonの実行環境をインストールした後に、VS CodeでPyhonの開発を行いやすくする。

### Pythonインストール

WindowsでPythonを利用する方法として[Anaconda](https://www.anaconda.com/)が有名だが、インストールサイズが大きすぎるので、[公式のPython環境](https://www.python.org/)をインストールする。

Macの人は公式からダウンロードするか"brew"ってやつを使うか、LinuxはAptとかYumとかPacmanとか。

### Python拡張機能

VS Codeの拡張で"python"を検索しインストール、再起動後適用される。

コマンド`python -m pip install -U pylint --user`を実行する。

なお、上のコマンドは自分で実行しなくても、Pythonのプログラム作成中に右下でPyLinkのインストールを促されるので、それに従ってもいい。
