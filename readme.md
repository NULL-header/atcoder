# For English
# Project Title
One Paragraph of project description goes here
# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
## Prerequisites
What things you need to install the software and how to install them
## Installing
A step by step series of examples that tell you how to get a development env running
# Deployment
Add additional notes about how to deploy this on a live system
# Build With
write the framework used or some method.

# For Japanese
# Project Title
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
    *ないとダウンロードできない。

動作確認がなされているのはWindowsのファストリングのWSL2上でのUbuntuのみ。
## Installing
A step by step series of examples that tell you how to get a development env running
# Deployment
Add additional notes about how to deploy this on a live system
# Build With
write the framework used or some method.
