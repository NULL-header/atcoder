# For English
# AtCoder
It is repository to practice Atcoder earnestly.
# Getting Started
That's OK to download this repository and hit run.sh. If you want to hit some file, however, as no there is this method in run.sh, It needs rewriting internal property directly.
## Prerequisites
* Python of the version specified on the internal property of run.sh.
    * As, if no it is there, the Error will ocurre after Warning that the python specified a version is none, it's nothing to hit accidentally, supposedly.
    * It needs to hand over Path of the python specified a version with -p option to make vertial envronment once. Absolute path or relative path from run.sh, It's OK. if it is done once, you can hit run.sh with -v option and without a argument.
* Linux OS
    * Because such as writing of path―difference of split word between some file and directory―or running a command of bash on source code of python, possiblity that it can run is a little.
* git
    * if it is none, no can to download ever.
## Installing
First, you should download this with git. After, ajust run.sh. It's so good to look help of run.sh with --help option.
# Deployment
There is the method that run.sh install packages from requirements.txt automatically, it's good way to hand over path of python to run.sh on you check so that there are packages needed by source code in requirements.txt.
# Build With
On initialize of this repository, I used [this](https://github.com/NULL-header/devinit).
On the way to push a repository cloned to different repository, I looked [this](https://qiita.com/takamicii/items/b0d1cc92fd172468fbf3).

# For Japanese
# AtCoder
Atcoderの練習をひたすらやっていくリポジトリ。
# Getting Started
gitでこのリポジトリをダウンロードしてrun.shを叩けばオーケー。ただし任意のファイルを起動したい場合、その機能はrun.shにないので、run.shの内部のプロパティを直接書き換える必要がある。
## Prerequisites
* run.shの内部プロパティにある指定されたバージョンのPython
    * 指定のバージョンのPythonがないとrun.shが警告をした上でErrorを起こすので、間違って起動されることはおそらくない、はず。
    * 一度仮想環境を作るために指定バージョンのPythonへのパスを-pオプションで渡してやる必要がある。絶対パスでもrun.shからの相対パスでもよい。一度仮想環境が作られれば引数なしの-vオプションで実行可能。
* Linux系OS
    * パスの書き方（個々のファイルやディレクトリ間の区切り文字がスラッシュかバックスラッシュかの違い）やPythonソースコード内でのBashコマンドの実行などでWindowsやMacでは動かない可能性が高い。
* git
    * ないとダウンロードできない。

動作確認がなされているのはWindowsのファストリングのWSL2上でのUbuntuのみ。
## Installing
gitでまずダウンロードする必要がある。その後、適宜run.shを調整すること。--helpオプションをrun.shに実装しているので、それも参照するとよい。
# Deployment
自動でrequirements.txtからパッケージをインストールする機能がrun.shにはあるので、ソースコードに必要なパッケージがrequirements.txtにあるかをチェックした上でPythonへのパスをrun.shに渡してやればよい。
# Build With
リポジトリの初期化に当たって、[devinit](https://github.com/NULL-header/devinit)を使用している。
リポジトリをクローンして別リポジトリにプッシュする方法においては[こちら](https://qiita.com/takamicii/items/b0d1cc92fd172468fbf3)を参照。
