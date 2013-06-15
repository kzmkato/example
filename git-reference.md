# Git初心者の備忘録
## 導入
参考になりそうなサイト
* ローカルのヘルプファイルとGoogle先生 $ git [command] --help
* [git簡単ガイド](http://rogerdudler.github.io/git-guide/index.ja.html)
* [Git 使い方 見出し一覧](http://transitive.info/article/git/)

まだあんまりわかってません。
個人でバージョン管理が出来ると聞いていたので、	ほほう使ってみるかという気持ちで使い始めました。
案件でも必要なものに入っていたので本格的に使い始めたとき事故らないように練習を兼ねて。

## コマンド
#### よくつかうgitコマンド
* **status** ローカルリポジトリの新規作成、変更、削除の状態確認

* **add -A** 新規作成、変更、削除をまとめてインデックスにファイルを追加。いつもはこれ。
* **commit -m "msg"** インデックスにメッセージをつけてコミット。"msg(message)"になにを変えたかをメモる。
 * **git commit -a** 更新したファイルをインデックスに加えコミット。こちらも便利そうですね。
* **remote** リモートリポジトリのブランチを探す。色がついてるやつが現在。
* **push** アップロード
 * $ git push origin HEAD 現在いるブランチをリモートにアップロード
* **fetch** ダウンロード
* **merge** ２つのブランチを合流

##### たまに、ひつようなとき
* **clone**
* **branch**
* **checkout**
* **log**

## 使わないほうがいいらしい
**git pull**
* git pullは使わなくてもよい
* 初心者はgit pullを使わない方がよい
はい、初心者なので使いません。

[Git pullを使うべきでない３つの理由](http://dqn.sakusakutto.jp/2012/11/git_pull.html)

このファイルはローカルからpushしました