Git チュートリアル - Git 学習用資料
============

マニュアルを書こうかとも思いましたが、
Webサイトに同じ様なものがあるので
以下のもので代用したいと思います。
資料化は別途考えましょう。

ツールとしては [GitHub for Windows](https://windows.github.com) は英語版しか無いので
日本語版の言語設定のある TortoiseGit を使う事にします。

Git入門、Gitとは何かがわかる様な内容が以下のURLに書かれています。

## [Git入門](http://www.backlog.jp/git-guide/)

Gitとは、分散型バージョン管理システムの一つで、もともとLinuxのソースコードを効果的に管理するために開発されました。

Gitのリポジトリは、リモートリポジトリとローカルリポジトリの2種類に分けられます。

+ リモートリポジトリ<br/>
専用のサーバに配置して複数人で共有するためのリポジトリです。
+ ローカルリポジトリ<br/>
ユーザ一人ひとりが利用するために、自分の手元のマシン上に配置するリポジトリです。

リポジトリをリモートとローカルの2種類に分けることで、普段の作業はローカルリポジトリを使って全て手元のマシン上で行うことができます。<br/>
自分のローカルリポジトリで作業した内容を公開したい時は、リモートリポジトリにアップロードして公開(プッシュ)します。また、リモートリポジトリを通してほかの人の作業内容を取得(プル)することもできます。

[目次](http://www.backlog.jp/git-guide/contents/)

+ [1. Gitの基本](http://www.backlog.jp/git-guide/intro/intro1_1.html)
+ [1.1 Gitを使ったバージョン管理](http://www.backlog.jp/git-guide/intro/intro1_1.html)
+ [1.2 履歴を管理するリポジトリ](http://www.backlog.jp/git-guide/intro/intro1_2.html)
+ [1.3 変更を記録するコミット](http://www.backlog.jp/git-guide/intro/intro1_3.html)
+ [1.4 ワークツリーとインデックス](http://www.backlog.jp/git-guide/intro/intro1_4.html)

## [Git関連ツール(msysgitとTortoiseGit)のインストール](http://www.backlog.jp/git-guide/intro/intro2_1.html)

+ [2.1 Git関連ツール(msysgitとTortoiseGit)のインストール](http://www.backlog.jp/git-guide/intro/intro2_1.html)
+ [2.2 初期設定](http://www.backlog.jp/git-guide/intro/intro2_2.html)

ツールのインストと初期設定までをお願いします。
リポジトリの作成は、後回しにします。

## [練習用テストリポジトリのクローン](http://www.backlog.jp/git-guide/intro/intro3_2.html)

[リモートリポジトリをクローンする - 画面例](http://www.backlog.jp/git-guide/intro/intro4_3.html)

練習用テストリポジトリのクローンからやりましょう。

ローカルPCにどこでもいいのでGitワークフォルダとして空のフォルダを作成してください。

`C:\work` でも結構です。


右クリック → Git クローン(複製)...<br/>
![右クリック](images/folder-right-click.png)

以下の画面でURLとして https://github.com/offsiteworks/test を入力してください。

![Gitクローン](images/git-clone.png)

## [ファイルをコミットする](http://www.backlog.jp/git-guide/intro/intro2_4.html)

[ファイルをコミットする - 画面例](http://www.backlog.jp/git-guide/intro/intro2_4.html)

## [リモートリポジトリへプッシュする](http://www.backlog.jp/git-guide/intro/intro3_1.html)

[クローンしたリポジトリからプッシュする - 画面例](http://www.backlog.jp/git-guide/intro/intro4_2.html)

## [リモートリポジトリからプルする](http://www.backlog.jp/git-guide/intro/intro3_3.html)

[リモートリポジトリからプルする - 画面例](http://www.backlog.jp/git-guide/intro/intro4_5.html)
