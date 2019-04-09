# GitHubチュートリアル Linux(Debian系)編

----
更新状況
- 2019年4月8日(月) 新規作成
----

## もくじ
- [GitHubアカウントの取得](#GitHubアカウントの取得)
----

## はじめに
こちらはLinuxでGitを使うためのチュートリアルです。<br>
Windowsとは違い、標準で入っているターミナルソフトを使います。<br>
また、ここではDebianベースのLinuxディストリビューションを使っての説明となりますので、CentOSなどのRedHat系は適宜読み替えるなどして下さい。

## Gitインストール
まずは以下コマンドを実行し、最新の状態へ更新しGitパッケージをインストール<br>
`sudo apt update && sudo apt upgrade -y && sudo apt install -y git vim`<br>
Gitパッケージと同時にvimもインストールしていますが、既にインストール済みであれば省略してください。

## 初期設定
インストールが無事終わったら[こちら](./tutorial_win.md#Cmderの初期設定)で紹介してあるコマンドを入力